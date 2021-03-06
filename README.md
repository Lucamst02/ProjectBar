# ProjectBar
###### Mussati, Delaini, Parente, Schembri

------------

![ProjectBar](https://user-images.githubusercontent.com/80251224/110308522-85518680-8000-11eb-80dd-de31063174ad.png)

------------
#### Descrizione
Il nostro gruppo ha ideato e sviluppato la creazione di un bar analizzando e tenendo in considerazione i seguenti punti: 
- Economia (costi)
- Segmenti di clientela
- Tipologia (in questo caso Cocktail bar)
- Possibili eventi a tema
- Planimetria del locale e sito web dedicato

------------

#### A cosa serve
Lo sviluppo di questo progetto serve a chi osserva di poter comprendere (in modo generale) la struttura di un bar, i possibili problemi che si potrebbero incontrare e quali punti analizzare, grazie ad un PowerPoint che sintetizza il tutto.

Questi si possono racchiudere in:
- VPC (Value Proposition Canvas)
- BMC (Business Model Canvas)
- Economia (Analisi dei costi e affluenza settimanale)
- Planimetria Bar
- Sito web ([projectbarvr.altervista.org](http://projectbarvr.altervista.org "projectbarvr.altervista.org"))

------------

#### Creazione sito

Per la creazione del sito web abbiamo seguito i seguenti passaggi:
  - Per iniziare scarica XAMPP direttamente dal sito ufficiale e scegli la versione adatta al tuo sistema operativo

  - Vai nel sito ufficiale di WordPress Italia e scarica l’ultima versione di WordPress cliccando sul pulsante “Download“

  - Dopo aver terminato il download sposta il file appena salvato all’ interno della cartella “HTDOCS” creata da XAMPP nel tuo hard   disk che trovi nel seguente percorso (se hai lasciato tutte le impostazioni di default di XAMPP): C:/xampp/htdocs/

  - Dopo aver spostato il file, estrai l’ archivio e dovresti avere una cartella chiamata “wordpress” come nell’ immagini sottostante. Rinomina quella cartella con il nome del tuo sito, ad esempio “il-mio-primo-sito-web” e cancella l’ archivio salvato in precendenza, oppure conservalo per una futura installazione di un altro sito
(posizione cartella htdocs xampp windows)

  - All’interno della cartella vedrai diversi file che servono a WordPress per poter funzionare correttamente

  NOTA BENE: Segna il nome del database pechè a breve dovrai inserirne il nome in una specifica pagina

  ATTENZIONE! Cancellando uno qualsiasi di quei file rischierai di non fare funzionare correttamente WordPress in locale

  - Avvia XAMPP che avete installato in precedenza. Ti troverai davanti una finestra con varie voci

  Quelle che interessano a noi sono “Apache“, ovvero il server virtuale e “MySQL” che serve per avviare il database collegato al server. Clicca sui pulsanti Start di tutte e due   le voci come nell’ immagine sottostante

E’ giunta l’ora di creare il database di WordPress su phpmyadmin, uno strumento utilizzato dalla maggior parte dei servizi di hosting, che permette di creare database in uno solo click

  - Per prima cosa apri il browser preferito e nella barra degli indirizzi scrivi il seguente indirizzo: localhost/phpmyadmin/

    Se XAMPP funziona correttamente ti si aprirà una pagina come nell’immagine sottostante, nel quale dovrai assicurarti che la lingua settata sia in italiano, poi successivamente clicca nella voce database

  - Creare database wordpress su phpmyadmin

    Nella sezione database troverai il form “Crea un nuovo database” dove dovrete inserire il nome del vostro sito senza spazi

  - Dopodichè clicca su “CREA” e comparirà un messaggio di conferma per l’ avvenuta creazione del database

    NOTA BENE: Segnati il nome del database pechè a breve dovrai inserirlo in una pagina
    
  - apriamo una nuova finestra del browser e nella barra degli indirizzi scrivi quanto segue: 
  
    localhost/nome-sito/wp-admin/install.php (nome-sito deve essere sostituito con il nome che avete assegnato alla cartella di WordPress rinominata in precedenza)

    Se avrai fatto tutto correttamente dovrebbe comparirti una pagina uguale a quella sottostante. Clicca su “Crea un file di configurazione” per proseguire

  - creare file wp-config wordpress

    Ti si aprirà una pagina dove ti verrà riepilogato il necessario per proseguire con l’ installazione di WordPress. Clicca sul pulsante “Iniziamo!” per proseguire

  - A questo punto ti verranno chiesti alcuni dati che dovrai compilare

Installazione wordpress

  - In NOME DATABASE assicurati di aver inserito il nome del database creato in precedenza. Per proseguire clicca su “INVIA“
  
    Se tutto è corretto ti apparirà una pagina in cui ti verrà detto che i dati inseriti sono corretti e potrai quindi procedere con l’ installazione di WordPress! In caso di errore clicca su riprova e controlla di aver inserito correttamente tutti i dati
    
  - Fare il login e procedere con la creazione
  
  - Registrarsi ora su Altervista, scegliere il proprio dominio e seguire tutte le procedure che verranno spiegate dal servizio, dopodichè esportare il database in locale e caricarlo sul servizio phpmyadmin di altervista
  
  - scarichiamo Filezilla poi ed utilizziamola per importare l'intera cartella di Wordpress (che abbiamo precedentemente inserito in C:/xampp/htdocs/ ) in "Spazio web" di Altervista

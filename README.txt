Ciao a tutti e benvenuti nella mia pagina personale su GitHub. 
Vi mostrerò tutti i miei progetti personali.

Iniziamo con l'elenco dei comandi per creazione di una cartella e git utilizzati nel terminale di VS:
1.cd C:\Users\alfie\Desktop --> posizionarsi nella cartella Desktop
2.mkdir Progetti_git --> creazione cartella Progetti_git
3.ni README.txt --> creazione del file di testo README
4.code README.txt --> aprire e modificare il file di testo
5.git init --> Inizializzazione di git
6.git status --> controllo dello status della nostra Staging Area (luogo intermedio in cui posso scegliere quali file all'interno della propria directory di lavoro si vogliono commit)
7.git add README.txt (o '.' per add tutti i file nella directory) --> aggiungere nella Staging Area e iniziare a tracciarne le modifiche 
8.git commit -m "Complete README" --> commit del file e aggiunta di un messaggio (-m) sullo status
9.git log --> vedere storico commit

Suggerimento: quando si fa un errore e si vuole tornare alla modifica precedente si usa questa procedura:
              a. git diff fileinerrore.estensione (premendo invio possiamo vedere in rosso la parte cancellata)
              b. git checkout fileinerrore.estensione

10.git remote add origin https://github.com/nome_utente/nome_cartella.git --> creazione repository remoto. origin (name del tuo remote)
11.git push -u origin main --> passare il nostro repository locale sul nostro repository remoto, che si chiama origin. Opzione u, collega il repository remoto e quello locale

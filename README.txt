MY WORKOUT — prima versione

CONTENUTO
- index.html: app completa
- manifest.webmanifest + icone: installazione PWA
- sw.js: cache offline

FUNZIONI
- Una scheda modificabile con esercizi, serie e recupero predefinito
- Inserimento manuale di kg e ripetizioni per ogni serie
- Timer regolabile, avvio rapido dal singolo esercizio, pausa/reset e +/- 15 secondi
- Storico locale, eliminazione sessioni, esportazione/importazione backup JSON
- Per ogni serie mostra il peso e le ripetizioni dell'ultima sessione salvata dello stesso esercizio

INSTALLAZIONE SU IPHONE
Per installarla come app dalla schermata Home, i file devono essere pubblicati su un hosting HTTPS.
Metodo semplice: crea un repository GitHub, carica tutti i file contenuti in questa cartella e attiva Settings > Pages > Deploy from a branch (branch main, root).
Apri quindi l'indirizzo HTTPS generato in Safari > Condividi > Aggiungi alla schermata Home.

IMPORTANTE
I dati vengono salvati nel browser di quel dispositivo (localStorage), non su cloud. Esporta periodicamente un backup JSON e conservalo in File/iCloud.
Il timer funziona mentre l'app è aperta; iOS può sospendere JavaScript e audio quando lo schermo è bloccato o si passa a un'altra app. Per ora non garantisce una notifica affidabile a schermo spento.

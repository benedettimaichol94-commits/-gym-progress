GYM PROGRESS - PROTOTIPO INIZIALE

Contenuto:
- index.html: app responsive in italiano
- manifest.webmanifest: metadati installazione PWA
- sw.js: cache di base per funzionamento offline

Funzioni incluse:
- Creazione/modifica/eliminazione giornate
- Archivio esercizi con foto, video e spiegazioni
- Registrazione serie con kg, ripetizioni, RIR e cedimento
- Visualizzazione dell'ultimo risultato noto durante il workout
- Storico allenamenti
- Report mensile con allenamenti, serie, volume e cedimenti
- Registrazione peso corporeo
- Esportazione CSV e backup JSON

NOTA TECNICA IMPORTANTE:
Questa è una prima versione web/PWA locale. Per installarla come PWA deve essere pubblicata su un hosting HTTPS (ad esempio GitHub Pages). I dati sono salvati nel browser del dispositivo. Il backup JSON esporta anche i dati testuali e i media incorporati come data URL, ma file video grandi possono generare backup pesanti.
Non è ancora un APK Android nativo né include sincronizzazione cloud. Il passaggio successivo è testarla e poi confezionarla con Capacitor/Android, aggiungendo eventualmente backup cloud.

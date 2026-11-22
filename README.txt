GYM PROGRESS - VERSIONE ANDROID 0.2.0

Questa versione prepara il progetto web esistente per essere incorporato in un'app Android tramite Capacitor.
L'APK viene generato gratuitamente con GitHub Actions.

FILE PRINCIPALI
- index.html: applicazione Gym Progress
- manifest.webmanifest e sw.js: supporto PWA/browser (non necessari nell'app nativa)
- package.json: dipendenze Capacitor
- capacitor.config.json: identificativo e nome dell'app Android
- .github/workflows/build-android-apk.yml: compilazione automatica dell'APK

COME SI OTTIENE L'APK
1. Caricare i file e le cartelle del progetto nella root del repository GitHub.
2. Verificare che il workflow sia presente esattamente in .github/workflows/build-android-apk.yml.
3. Aprire la scheda Actions del repository.
4. Aprire "Build Gym Progress Android APK" e attendere il completamento.
5. Scaricare l'artifact "Gym-Progress-Android-APK" e, al suo interno, app-debug.apk.

NOTA SUI DATI
I dati di allenamento della versione attuale sono memorizzati localmente nel WebView tramite localStorage.
Non vengono inviati a GitHub. Prima di un uso prolungato è consigliato esportare periodicamente il backup dall'app.
La gestione dei file multimediali molto grandi e la persistenza avanzata tramite database locale saranno migliorate nelle prossime versioni.

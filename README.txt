GYM PROGRESS - VERSIONE ANDROID 0.4.0

AGGIORNAMENTI 0.4
- Intensità predefinita per esercizio: Cedimento tecnico oppure RIR 0/1 (un'unica opzione).
- Le vecchie impostazioni RIR 0 e RIR 1 vengono visualizzate come RIR 0/1.
- Le giornate continuano a salvare serie e ripetizioni programmate.
- Durante l'allenamento si registrano separatamente kg, ripetizioni effettive, RIR effettivo e cedimento per ogni serie.
- I risultati effettivi restano distinti dagli obiettivi programmati nello storico.

COMPILAZIONE APK
1. Caricare i file e le cartelle del progetto nella root del repository GitHub.
2. Verificare che .github/workflows/build-android-apk.yml sia presente.
3. Aprire Actions e avviare Build Gym Progress Android APK.
4. A compilazione completata, scaricare l'artifact Gym-Progress-Android-APK.
5. Estrarre l'artifact e installare app-debug.apk su Android.

DATI
I dati sono memorizzati localmente nel WebView tramite localStorage e non vengono inviati a GitHub. Effettuare backup regolari dall'app. Non disinstallare l'app o cancellarne i dati prima di aver esportato un backup.

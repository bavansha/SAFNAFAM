SAFNAFAM - APK build steps (PC il cheyyanam)
1. Node.js (nodejs.org) um Android Studio um install cheyyuka.
2. Ee folder il terminal thurakkuka:
   npm install
   npx cap add android
   npx cap sync android
   npx cap open android
3. Android Studio: Build > Build Bundle(s)/APK(s) > Build APK(s)
4. APK: android/app/build/outputs/apk/debug/app-debug.apk
   Ithu phone il copy cheythu install cheyyam (Unknown sources allow cheyyanam).

AI features (Background remover, Auto captions):
- Modelukal first use il internet vazhi download aakum (background ~15MB, captions ~100-150MB). Pinne device il cache aakum.
- Malayalam captions il accuracy kuravayirikkum. Whisper-base aanu use cheyyunnath; kooduthal accuracy venel www/index.html il 'Xenova/whisper-base' ennathu 'Xenova/whisper-small' aakkuka (valuthum pathukkavum).

PC illathe (GitHub Actions vazhi):
1. github.com il free account undakki oru new repository undakkuka.
2. Ee folder le ellaa files um (.github folder ulppede) repository il upload cheyyuka.
3. Actions tab > "Build APK" > Run workflow. 5-10 minute kazhiyumbol "SAFNAFAM-apk" download cheyyam.

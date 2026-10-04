# Build Belajar AI menjadi APK

## Opsi PC (Android Studio)
1. Install Node.js 18+ dan Android Studio.
2. Buka terminal di folder project.
3. Jalankan:
   npm install
   npm run build
   npx cap add android
   npx cap sync android
   npx cap open android
4. Di Android Studio pilih Build > Build APK(s).
5. APK debug biasanya ada di:
   android/app/build/outputs/apk/debug/app-debug.apk

## Kalau project sudah pernah punya folder android
Gunakan:
   npm install
   npm run build
   npx cap sync android
   npx cap open android

Package ID: com.gian.belajarai
Nama aplikasi: Belajar AI

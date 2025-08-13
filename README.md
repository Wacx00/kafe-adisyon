
# Nokta Tasarım — Offline Adisyon (Vite + Capacitor)

## Geliştirme
```bash
npm i
npm run dev
```

## APK (yerel)
```bash
npm run build
npx cap add android
npx cap copy
npx cap open android
# Android Studio > Build > Generate Signed Bundle/APK (veya Debug için: ./gradlew assembleDebug)
```

## APK (GitHub Actions, telefona gerek yok)
1. Bu projeyi GitHub'da yeni bir repoya yükle (ana branch: main).
2. Repo > Actions sekmesine gir; ilk run otomatik başlayabilir ya da **Run workflow** de.
3. Run tamamlanınca, **Artifacts** bölümünden **app-debug.apk** dosyasını indir.

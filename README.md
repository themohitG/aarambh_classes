# Aarambh Classes App

Official mobile & web app for **Aarambh Classes** 📚

## 🚀 Features
- Android, iOS, Web builds
- Auto-generated app icons from logo
- Firebase Hosting deployment for web

## 🔧 Build & Deploy
This project is set up for **Codemagic** CI/CD.

### Android
- Outputs APK & AAB in `/build/outputs/`

### iOS
- Outputs `.ipa` (unsigned)

### Web
- Built into `build/web`
- Deployed to Firebase Hosting → [aarambh-classes.web.app](https://aarambh-classes.web.app)

## ⚡ Firebase Setup
1. Install Firebase CLI
2. Run `firebase login:ci` → copy token
3. Add `FIREBASE_TOKEN` to Codemagic environment variables

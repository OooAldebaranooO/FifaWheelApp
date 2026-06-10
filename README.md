# ⚽ FIFA 26 – Roue des Buts

Une application Android qui fait tourner une roue pour décider quel type de but marquer sur FIFA 26 !

## 🎯 Types de buts

- 💥 Frappe Lointaine
- 🤯 Tête
- 🔥 Dribble + Tir
- 🌀 Coup Franc
- 📐 Corner
- ⚡ Penalty
- 🚀 Contre-Attaque
- 🎭 Petit Pont + Tir
- ✨ Ciseau / Retourné
- 🦂 Coup du Scorpion

## 📱 Installation de l'APK

1. Va dans **Releases** (colonne de droite sur GitHub) et télécharge `app-release.apk`
2. Sur ton Android : **Paramètres → Sécurité → Autoriser les sources inconnues**
3. Ouvre le fichier APK téléchargé pour l'installer

## 🛠️ Build depuis les sources

### Prérequis
- Android Studio ou JDK 17+
- Android SDK

### Commande
```bash
./gradlew assembleRelease
# APK généré : app/build/outputs/apk/release/app-release.apk
```

## 🤖 CI/CD

À chaque push sur `main`, GitHub Actions compile automatiquement l'APK et crée une Release téléchargeable.

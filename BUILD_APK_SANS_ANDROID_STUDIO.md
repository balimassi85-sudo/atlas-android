# Générer l'APK sans Android Studio

Ce projet inclut une compilation automatique GitHub Actions.

1. Crée un dépôt GitHub vide.
2. Ajoute tout le contenu de ce dossier à la racine du dépôt.
3. Ouvre l'onglet **Actions** du dépôt.
4. Ouvre **Build Atlas Belt Admin APK** puis clique **Run workflow**.
5. Quand le build est terminé, ouvre le build puis télécharge l'artefact **Atlas-Belt-Admin-APK**.
6. Décompresse l'artefact : il contient `Atlas-Belt-Admin.apk`, directement installable sur Android.

L'APK est une build debug signée automatiquement par Android, suffisante pour une installation directe sur téléphone. Pour une publication sur le Play Store, une signature release permanente devra être configurée.

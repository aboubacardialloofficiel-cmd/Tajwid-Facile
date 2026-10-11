# Tajwid Facile – Apprendre le Coran

Projet Android natif en Kotlin + Jetpack Compose, conçu pour fonctionner hors ligne.

## Fonctionnalités incluses
- Accueil avec progression enregistrée localement
- Alphabet arabe et signes vocaliques
- Cours introductifs de Tajwid (Madd, Ghounna, Izhar, Idgham, Iqlab, Ikhfa)
- Sourate Al-Fatiha en arabe avec translittération française indicative et traduction du sens
- Quiz interactif avec score sauvegardé localement
- Navigation simple adaptée aux petits écrans
- Aucune connexion Internet nécessaire

## Ouvrir et compiler
1. Installez Android Studio (version récente).
2. Ouvrez ce dossier dans Android Studio.
3. Laissez Gradle synchroniser le projet.
4. Choisissez un émulateur ou connectez un téléphone Android avec le débogage USB activé.
5. Cliquez sur **Run**.

Pour produire un APK : **Build > Build Bundle(s) / APK(s) > Build APK(s)**.

## Important
Les translittérations ne remplacent pas l'apprentissage oral. Les règles et exemples sont des supports introductifs : faites vérifier la récitation par un enseignant qualifié. La version actuelle ne contient pas de fichiers audio, afin de rester légère et réellement hors ligne.


## Générer automatiquement un APK avec GitHub

Le dossier `.github/workflows/build-apk.yml` permet de compiler l'application sur GitHub Actions.
1. Téléversez les fichiers du projet dans un dépôt GitHub (branche `main` ou `master`).
2. Ouvrez l'onglet **Actions** et sélectionnez **Build Android APK**.
3. Lancez **Run workflow** si nécessaire.
4. À la fin, ouvrez l'exécution réussie et téléchargez l'artefact **Tajwid-Facile-APK**. Il contient `app-debug.apk`.

La compilation nécessite une connexion Internet dans l'environnement de build pour télécharger Gradle et les dépendances Android.

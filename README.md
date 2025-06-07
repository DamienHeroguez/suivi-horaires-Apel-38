
# Suivi des Horaires

Ce dépôt contient les fichiers HTML pour suivre les horaires mensuels de vos salariées, accéder au tableau de bord annuel, et activer GitHub Pages pour héberger le site.

## Contenu du dépôt

- `index.html` : Page d'accueil avec les liens vers chaque mois et le tableau de bord annuel.
- `summary_annual.html` : Tableau de bord annuel avec les totaux des heures travaillées, écarts, et événements.
- `suivi_horaires_september_2025.html` à `suivi_horaires_august_2026.html` : Interfaces mensuelles pour la saisie des horaires.

## Utilisation

1. **Suivi Mensuel** :
   - Ouvrez le fichier HTML correspondant au mois souhaité (ex. `suivi_horaires_september_2025.html`).
   - Saisissez les heures d'arrivée, de départ, les pauses, et les événements.
   - Les heures travaillées et les écarts sont calculés automatiquement.

2. **Tableau de Bord Annuel** :
   - Ouvrez `summary_annual.html` pour voir les totaux des heures travaillées, écarts, et événements pour l'année.

## Hébergement avec GitHub Pages

1. **Créer un dépôt GitHub** :
   - Allez sur [GitHub](https://github.com) et créez un nouveau dépôt nommé `suivi-horaires`.
   - Cochez "Public" et cliquez sur "Create repository".

2. **Téléverser les fichiers** :
   - Cliquez sur "Add file" > "Upload files".
   - Glissez-déposez le contenu de cette archive (pas le fichier `.zip`, mais les fichiers HTML à l'intérieur).
   - Cliquez sur "Commit changes".

3. **Activer GitHub Pages** :
   - Allez dans l'onglet "Settings" du dépôt.
   - Dans le menu de gauche, cliquez sur "Pages".
   - Sous "Source", choisissez "Deploy from a branch".
   - Sélectionnez la branche `main` et le dossier `/root`.
   - Cliquez sur "Save".

4. **Accéder au site** :
   - GitHub vous donnera une URL du type :
     `https://ton-nom-utilisateur.github.io/suivi-horaires/`
   - Ouvrez cette URL dans votre navigateur pour accéder à l'interface.

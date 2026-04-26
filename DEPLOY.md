Guide de déploiement sur GitHub Pages

1) Créer le dépôt GitHub (via l'interface web) ou avec le CLI `gh` :

   gh repo create <USER>/<REPO> --public --source=. --remote=origin --push

2) Commandes Git locales (si vous n'avez pas encore initialisé) :

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin git@github.com:<USER>/<REPO>.git
git push -u origin main
```

3) Ce workflow (`.github/workflows/deploy-pages.yml`) se déclenchera à chaque `push` sur la branche `main` et publiera la racine du dépôt sur GitHub Pages.

4) URL d'accès :
   - Pour un dépôt public : `https://<USER>.github.io/<REPO>/`

5) Remarques :
   - L'action utilise le token `GITHUB_TOKEN` automatiquement fourni par GitHub Actions.
   - Si vous souhaitez un domaine personnalisé, ajoutez un fichier `CNAME` à la racine contenant votre domaine.
   - Si vous préférez utiliser `gh-pages` branch ou une autre méthode, dites-le et j'adapterai le workflow.

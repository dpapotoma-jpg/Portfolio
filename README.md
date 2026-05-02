# Portfolio — Didier

Site personnel présentant compétences, réalisations et contact.

## Structure du projet
- `index.html` : page principale (HTML + CSS + JS). Sections : Compétences, Réalisations, Formation, Contact.
- `public/phone-hero.svg` : bannière optimisée pour mobile.

## Changements récents
- Mise à jour des cartes/accordéon **Compétences**.
- Ajout d'une image mobile (`public/phone-hero.svg`).
- Correction de l'axe de la timeline pour que la ligne traverse les marqueurs.

## Modifier la section "Compétences"
La section se trouve dans `index.html`. Selon la version actuelle il y a deux variantes :

- Cartes interactives (`.sk-grid`) : éditez les titres et listes dans les blocs `div.sk-card`.
- Accordéon (ancienne variante) : éditez les `button.accordion-btn` et `div.accordion-body`.

Pour mettre à jour rapidement les textes, ouvrez `index.html` et modifiez le contenu HTML correspondant, puis enregistrez.

## Lancer en local
1. Ouvrir `index.html` dans un navigateur (double‑clic) pour une visualisation statique.
2. Optionnel — servir via npm `http-server` ou `live-server` pour rechargement automatique :

```bash
# exemple avec http-server (npm)
npm install -g http-server
http-server . -c-1
```

Ouvrir ensuite `http://localhost:8080`.

## Processus de contribution
1. Créez une branche feature/nom (optionnel).
2. Faites vos modifications locales.
3. Committez avec un message clair.
4. Poussez sur `main` (ou soumettez une PR si vous utilisez une branche).

Commandes utiles :

```bash
git checkout -b feature/ma-modif
git add -A
git commit -m "Description de la modif"
git push origin feature/ma-modif
```

## Déploiement
Ce projet est une simple page statique — vous pouvez la déployer sur GitHub Pages, Netlify ou Cloudflare Pages.

## Licence
Ajoutez ici la licence souhaitée (ex : MIT) si vous souhaitez en spécifier une.

## Contact
Didier — papotomadidieressodewa@gmail.com


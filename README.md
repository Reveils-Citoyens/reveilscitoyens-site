# reveilscitoyens-site

Site de présentation de l'association **Réveils Citoyens**, éditrice de
[NosDéputés.fr](https://www.nosdeputes.fr).

Une page statique (`index.html` et `styles.css`), sans dépendance ni étape de
construction. Pour la voir en local, ouvrir `index.html` dans un navigateur, ou :

```bash
python3 -m http.server 8000
```

## Déploiement

Chaque push sur `main` publie le site sur GitHub Pages
(`.github/workflows/pages.yml`). Dans les réglages du dépôt, *Settings → Pages →
Build and deployment*, la source doit être **GitHub Actions**.

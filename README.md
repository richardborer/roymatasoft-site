# roymatasoft.com

Site vitrine de Roymata Soft. Site statique : une page `index.html`, les images dans `assets/`.

- Chaque poussée sur `main` déploie le site sur GitHub Pages (workflow `.github/workflows/pages.yml`).
- Aucune étape de construction : modifier `index.html`, pousser, c'est en ligne une minute plus tard.
- Pour le domaine roymatasoft.com : ajouter un fichier `CNAME` contenant `roymatasoft.com`, puis pointer le DNS (A vers les adresses GitHub Pages, CNAME `www` vers `richardborer.github.io`).

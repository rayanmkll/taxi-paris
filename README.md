# Taxi & Moto-taxi Paris IDF

Site vitrine one-page : taxi, moto-taxi et transport médical conventionné.

## Fichiers
- `index.html` : version statique, pour GitHub Pages, Vercel ou Netlify
- `index.php` : version PHP, pour alwaysdata, o2switch ou Hostinger (infos modifiables dans `$config`)
- `style.css` : styles partagés

> Si tu modifies `$config` dans `index.php`, régénère la version statique avec `php index.php > index.html`.

## Mise en ligne sur GitHub Pages
1. Crée un repo vide `taxi-paris` sur GitHub (sans README)
2. Dans ce dossier :
   ```bash
   git remote add origin https://github.com/TON_USER/taxi-paris.git
   git push -u origin main
   ```
3. Sur GitHub : **Settings → Pages → Source : Deploy from branch → `main` / root → Save**
4. Le site est en ligne après environ 1 min sur `https://TON_USER.github.io/taxi-paris/`

## Mise à jour
```bash
git add .
git commit -m "ma modif"
git push
```

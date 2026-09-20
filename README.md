# Site vitrine — Clément Perez, recrutement freelance

Site vitrine statique (une seule page HTML), optimisé SEO, prêt pour GitHub Pages.

## ⚠️ À faire avant/après mise en ligne

Remplacez `votre-compte.github.io/site-recruteur/` par votre vraie URL GitHub Pages
dans 3 fichiers :
- `index.html` (balises `<link rel="canonical">`, `og:url`, JSON-LD `url`)
- `robots.txt` (ligne Sitemap)
- `sitemap.xml` (balise `<loc>`)

## Déploiement

1. Créez un repo GitHub public (ex. `site-recruteur`)
2. Uploadez tous les fichiers de ce dossier (index.html, robots.txt, sitemap.xml, .nojekyll, README.md)
3. Settings → Pages → Source : branche `main`, dossier `/ (root)` → Save
4. Site en ligne à `https://VOTRE-COMPTE.github.io/site-recruteur/`

## Mettre à jour le site

Remplacez `index.html`, puis committez et pushez (ou ré-uploadez sur GitHub).

## SEO déjà en place
- Title, meta description et mots-clés optimisés
- Open Graph + Twitter Card pour le partage sur les réseaux
- Données structurées JSON-LD (schema.org ProfessionalService)
- Structure sémantique (`<main>`, hiérarchie de titres H1 → H3)
- `robots.txt` + `sitemap.xml`

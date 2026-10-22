# Ainz Web Design — vitrine v2

Site vitrine pour la prospection freelance, Suisse romande.

Identite visuelle identique au site d'origine : noir profond, or, Inter, emojis.
Les corrections portent sur la technique, pas sur l'apparence.

## Deploiement

Pousser sur `main`. GitHub Pages sert `index.html` automatiquement.

## Stack
- HTML / CSS / JS purs, aucune dependance, aucune build
- Police : Inter (Google Fonts)
- Couleurs : `--bg #0a0a0a`, `--gold #d4af37`

## Structure
```
index.html      # hero, services, demo, processus, about, contact, footer
style.css       # theme sombre + or, responsive
script.js       # nav au scroll, menu mobile, reveal au scroll
```

## Corrections par rapport a l'original
- Contraste du texte ameliore : `--text-dim` passe de `#a0a0a0` a `#b4b4b4`
- Plus de `transition: all`, chaque transition nomme ses proprietes
- `:focus-visible` au clavier, partout
- `prefers-reduced-motion` respecte, le contenu reste visible sans JS
- Menu mobile avec fermeture sur Echap et au redimensionnement
- Grille qui tient a 360 px, boutons pleine largeur sur petit ecran
- Schema.org conserve, 3 offres, 6 cantons

## Sections
1. **Hero** — badge, titre, deux CTA, trois stats
2. **Pour qui** — Option A (statique) / Option B (avec CMS)
3. **Demo** — Maison Verte, avec le detail de la stack
4. **Processus** — quatre etapes numerotees
5. **Pourquoi** — la position, sans bullshit
6. **Contact** — tel, WhatsApp, email
7. **Footer** — liens vers le materiel commercial et la demo

## Contact
- Telephone : 076 579 85 30
- Email : nazarick963@gmail.com
- WhatsApp : https://wa.me/41765798530

## Positionnement tarifaire
À partir de **600 CHF** (point d'entrée), 3 niveaux selon la complexité (updated 2026-10-06, formerly 300 / 500-700 / 800-1200) :
- **600 CHF** — site 1 page, présence de base
- **1200 CHF** — site multi-pages, SEO local, design personnalisé
- **2000 CHF** — multi-pages avancé, réservation en ligne, multilingue

## Contact
- Téléphone : 076 579 85 30
- Email : nazarick963@gmail.com
- WhatsApp : https://wa.me/41765798530
- Démo : https://handsonnazarick.github.io/demo-restaurant-public/

## Déploiement

Le site est déjà en ligne sur GitHub Pages : https://handsonnazarick.github.io/ainz-webdesign/

Pour mettre à jour après un commit :
```bash
cd "/c/Users/alaza/projects/ainz-web-design"
git add .
git commit -m "Update"
git push
```

GitHub Pages redéploie automatiquement en ~30 secondes.

## Domaine custom (optionnel, ~15 CHF/an)
Acheter `ainz-webdesign.ch` ou `.com` (Infomaniak / Namecheap).
DNS : CNAME pointant vers `handsonnazarick.github.io`
Ajouter un fichier `CNAME` à la racine avec le domaine.

## Écosystème

| Repo | Rôle |
|---|---|
| **ainz-webdesign** (ce repo) | Vitrine d'entrée, déployée sur GitHub Pages |
| [site-services](https://github.com/HandsOnNazarick/site-services) | Matériel commercial (one-pager, brief, CGV, FAQ, email templates) |
| [demo-restaurant-public](https://github.com/HandsOnNazarick/demo-restaurant-public) | Démo live publique (version anonymisée, déployée sur GitHub Pages) |
| [demo-restaurant-maison-verte](https://github.com/HandsOnNazarick/demo-restaurant-maison-verte) | Repo template interne (privé, complet avec CMS + docs) |
| [lead-gen](https://github.com/HandsOnNazarick/lead-gen) | Pipeline prospection |
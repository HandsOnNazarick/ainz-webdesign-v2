# Ainz Web Design — vitrine (v2)

Site vitrine pour la prospection freelance, Suisse romande.

## Deploiement

Pousser sur la branche `main` de ce repo. GitHub Pages sert `index.html` automatiquement.

## Stack
- HTML / CSS / JS purs, aucune dependance, aucune build
- Polices : Oswald (titres), Archivo (texte), Archivo Narrow (chiffres)
- Theme : Formwork — beton chaud, encre proche du noir, un orange signal

## Structure
```
index.html      # hero, index de projets, formules, processus, contact
style.css       # mise en page et composants
tokens.css      # jetons de couleur, typo, espacement (genere)
base.css        # base commune (genere)
script.js       # menu mobile
```

## Sections
1. **Hero** — titre, promesse courte, deux actions, plaque 600 CHF
2. **Le travail** — index de projets (secteur + date en colonne de gauche)
3. **Deux formules** — Statique 600 CHF / Avec edition 1 200 CHF
4. **Quatre etapes** — bande encre, appel / maquette / realisation / livraison
5. **Contact** — tel, WhatsApp, email, zones couvertes, horaires
6. **Footer** — mast

## Regles de design

Le theme interdit les emojis comme icones, les degrades purple vers bleu, la carte
dans la carte, `transition: all`, et les labels en capitales espacees. Les titres sont
en Oswald 700 capitales, le texte en Archivo. Un seul orange sur l'ecran, sur l'action
principale.

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
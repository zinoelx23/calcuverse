# CalcuVerse.com — configuration finale

Domaine choisi : https://calcuverse.com

## GitHub Pages

Dans le dépôt GitHub :
Settings → Pages → Custom domain → `calcuverse.com`

DNS recommandé :

A @ → 185.199.108.153
A @ → 185.199.109.153
A @ → 185.199.110.153
A @ → 185.199.111.153

CNAME www → TON-UTILISATEUR.github.io

Après propagation :
1. revenir dans Settings → Pages
2. vérifier que `calcuverse.com` est affiché
3. activer `Enforce HTTPS`

Remplacer `TON-UTILISATEUR` par ton vrai identifiant GitHub.

## Google Analytics

Dans `js/config.js`, remplacer :
`G-XXXXXXXXXX`
par ton vrai Measurement ID.

## Google AdSense

Dans `js/config.js`, remplacer :
`ca-pub-XXXXXXXXXXXXXXX`
par ton vrai Publisher ID, uniquement après avoir obtenu/validé ton compte AdSense.

## SEO

Le domaine canonique du projet est maintenant :
`https://calcuverse.com`

Les fichiers robots.txt et sitemap.xml doivent être servis depuis :
`https://calcuverse.com/robots.txt`
`https://calcuverse.com/sitemap.xml`

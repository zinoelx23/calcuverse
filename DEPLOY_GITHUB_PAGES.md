# CalcuVerse — mise en ligne

## 1. Avant publication

Remplace dans `js/config.js` :
- `https://calcuverse.com` par ton domaine réel
- `G-XXXXXXXXXX` par ton identifiant Google Analytics 4
- `ca-pub-XXXXXXXXXXXXXXX` par ton identifiant Google AdSense après approbation

Remplace aussi `calcuverse.com` dans `CNAME`.

## 2. GitHub Pages

1. Crée un dépôt GitHub nommé `calcuverse`.
2. Envoie tout le contenu de ce dossier à la racine du dépôt.
3. GitHub → Settings → Pages.
4. Source : Deploy from a branch.
5. Branch : `main`, dossier `/ (root)`.
6. Enregistre.
7. Dans Custom domain, saisis ton domaine réel.
8. Active Enforce HTTPS quand l'option apparaît.

## 3. DNS si tu utilises un domaine personnalisé

Pour `www`, crée un CNAME vers `TON-UTILISATEUR.github.io`.

Pour un domaine racine, utilise les enregistrements A GitHub Pages :
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153

Et les autres adresses recommandées par GitHub si ton registrar les prend en charge.

## 4. Après publication

Teste :
- accueil
- chaque calculatrice
- version mobile
- pages FR/EN/ES/AR
- privacy / terms / contact
- robots.txt
- sitemap.xml
- HTTPS
- Search Console
- Analytics

Ne soumets pas AdSense avant d'avoir remplacé les placeholders et vérifié que le contenu, la navigation et les pages légales sont réellement prêts.

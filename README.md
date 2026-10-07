# 🎓 CalcuVerse - L'univers Tout-en-un des Calculatrices Scientifiques

> **La boîte à outils mathématiques & scientifiques complète pour les étudiants**, optimisée pour le **SEO**, le **support multilingue (FR, EN, ES, AR)** et la **monétisation publicitaire (Google AdSense)** pour générer des revenus récurrents.

---

## 🚀 Démarrage Rapide (Zéro Installation)

Aucun outil préalable (Node.js, Python, npm) n'est nécessaire !

1. Ouvrez le dossier `calculatrice-etudiant`.
2. Double-cliquez directement sur **`index.html`** pour lancer le site dans n'importe quel navigateur (Google Chrome, Microsoft Edge, Mozilla Firefox, Safari).

---

## 🧮 Les 7 Modules Inclus

1. **Calculatrice Scientifique & Symbolique :** Évaluation des expressions arithmétiques, fonctions trigonométriques ($\sin, \cos, \tan$) en degrés ou radians, logarithmes, exponentielles, constantes ($\pi, e$) et historique des calculs.
2. **Traceur Graphique 2D (Style Desmos) :** Tracé en temps réel de fonctions $f(x)$ et $g(x)$ sur repère cartésien dynamique avec tableau de valeurs automatique.
3. **Solveur d'Équations Pas-à-Pas (Style Symbolab) :** Résolution des équations du premier et second degré ($ax^2 + bx + c = 0$) avec le détail complet du calcul du discriminant $\Delta$, racines réelles ou complexes et sommet de la parabole.
4. **Calculateur de Matrices (Style Matrix Calculator) :** Addition, soustraction, produit matriciel, transposition, calcul de déterminant et inversion de matrices $2 \times 2$ et $3 \times 3$.
5. **Physique & Chimie Appliquée :**
   - Calculateur automatique de **masse molaire** (analyse syntaxique de formules chimiques complexes comme $H_2SO_4$, $Ca(OH)_2$, $C_6H_{12}O_6$).
   - Calculateur de **dilution** ($C_1 \times V_1 = C_2 \times V_2$).
   - **Loi des gaz parfaits** ($P \times V = n \times R \times T$).
   - **Loi d'Ohm** ($U = R \times I$) et puissance dissipée ($P = U \times I$).
6. **Statistiques Descriptives :** Analyse de séries de données (Effectif $N$, Moyenne $\bar{x}$, Médiane, Variance $\sigma^2$, Écart-type $\sigma$, Min/Max, Quartiles $Q_1 / Q_3$).
7. **Informatique & Logique :** Conversion simultanée entre bases décimale, binaire et hexadécimale, opérations logiques booléennes (AND, OR, XOR, NOT, Shift) et convertisseur d'unités de stockage numérique.

---

## 💰 Monétisation & Revenus Récurrents (Google AdSense)

Le site intègre des emplacements publicitaires stratégiques pré-configurés pour respecter les critères **Core Web Vitals** (absence de décalage de page CLS grâce à des hauteurs fixes) :

1. **Top Leaderboard (728x90) :** Placé sous l'en-tête, très visible.
2. **Medium Rectangle (300x250) :** Placé à droite dans la barre latérale.
3. **Bottom Leaderboard (728x90) :** Placé sous le guide pédagogique.

### Pour activer vos revenus AdSense :
1. Créez un compte sur [Google AdSense](https://adsense.google.com/).
2. Ouvrez le fichier `index.html` et remplacez `ca-pub-XXXXXXXXXXXXXXXX` par votre véritable identifiant client AdSense :
   ```html
   <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-VOTRE_ID_ADSENSE" crossorigin="anonymous"></script>
   ```
3. Décommentez les balises `<ins class="adsbygoogle" ...>` correspondantes.

---

## 🔍 Optimisation SEO (Google & Moteurs de Recherche)

- **Balises Meta complètes :** Title, Description optimisées, mots-clés, OpenGraph pour les réseaux sociaux, cartes Twitter.
- **Support Multilingue Hreflang :** Liens alternatifs pour Français (`fr`), Anglais (`en`), Espagnol (`es`) et Arabe (`ar`) avec bascule de texte automatique.
- **Données structurées Schema.org :** Renseignées en format JSON-LD pour catégoriser le site comme `EducationalApplication` dans Google.
- **Fichiers SEO inclus :**
  - `robots.txt` : Autorise l'indexation complète par les robots de recherche.
  - `sitemap.xml` : Liste les versions linguistiques pour un référencement accéléré.

---

## 🌐 Comment Mettre en Ligne Gratuitement

### Option 1 : GitHub Pages (100% gratuit avec nom de domaine ou sous-domaine github.io)
1. Créez un compte sur [GitHub](https://github.com).
2. Créez un nouveau dépôt public (ex: `omnimath-etudiant`).
3. Déposez-y l'ensemble des fichiers de ce dossier.
4. Rendez-vous dans **Settings** > **Pages** et activez **Deploy from a branch** (branche `main`, dossier `/root`).
5. Votre site sera instantanément en ligne !

### Option 2 : Vercel ou Netlify (Déploiement en 1 clic)
1. Glissez-déposez simplement le dossier `calculatrice-etudiant` sur [Netlify Drop](https://app.netlify.com/drop).
2. Le site est en ligne en 10 secondes avec certificat HTTPS / SSL gratuit.


## Mise en production — configuration obligatoire

Avant publication, modifier **un seul fichier** : `js/config.js`.

- `siteUrl` : domaine HTTPS réel du site.
- `ga4MeasurementId` : identifiant Google Analytics 4, si utilisé.
- `adsenseClientId` : identifiant AdSense réel (`ca-pub-...`), si le compte est approuvé.
- `adsenseSlots.top/bottom/sidebar` : IDs des emplacements AdSense.

Puis remplacer `https://calcuverse.com` dans `index.html`, `robots.txt` et `sitemap.xml` par le domaine réel.

### Fichiers ajoutés

- `js/config.js` : configuration publique centralisée.
- `js/analytics.js` : événements GA4 optionnels.
- `js/monetization.js` : AdSense conditionnel, sans requête si non configuré.
- `favicon.svg`, `manifest.webmanifest`, `404.html`.
- `privacy.html`, `terms.html`, `contact.html`.
- `guides/` : pages SEO dédiées aux principaux outils.

### Test local

Le projet est statique. Lancez un serveur local depuis le dossier racine (par exemple `python -m http.server`) puis ouvrez `index.html` via `http://localhost:8000/`.

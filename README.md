# Portfolio — N'Gadi Wassim

## 🔍 Description
Site personnel statique présentant le profil, les compétences, les projets et les moyens de contact de N'Gadi Wassim.

Ce dépôt contient un site HTML/CSS simple sans dépendances externes (hormis une police Google). Il est pensé pour être léger, accessible et facile à déployer comme site statique (GitHub Pages, Netlify, etc.).

---

## 📁 Structure du projet
- `index.html` — page principale (tout le contenu du portfolio)
- `style.css` — styles et thèmes (inclut mode sombre)
- `CVWassim-2026.pdf` — CV utilisé par la modal de visualisation/téléchargement
- `robots.txt`, `sitemap.xml` — fichiers SEO
- `wass1.png`, `favicon.ico` — images et icône

---

## 🛠️ Développement — démarrage rapide
1. Cloner le dépôt

```bash
git clone <url-du-depot>
cd portfolio
```

2. Ouvrir en local (option sans serveur) :
- Double-cliquer sur `index.html` pour l'ouvrir dans le navigateur.

3. Ouvrir avec un petit serveur HTTP (recommandé pour tester les chemins relatifs et l'iframe PDF) :

```bash
# Avec Python 3
python -m http.server 8000
# puis ouvrir http://localhost:8000
```

---

## ⚙️ Personnalisation
- Mettre à jour l'**adresse email** (mailto) : modifier le lien dans `index.html` (rechercher `mailto:`).
- Remplacer `CVWassim-2026.pdf` par la version la plus récente pour que la modal et le lien de téléchargement pointent vers le bon fichier.
- Images et icônes : remplacer `wass1.png` et `favicon.ico` par vos fichiers tout en gardant les mêmes noms ou en modifiant les références dans `index.html`.
- Metadonnées SEO : modifier `<meta name="description">`, `<title>`, et les balises Open Graph/Twitter dans `index.html`."}]}]

---

## ✅ Accessibilité & bonnes pratiques
- Utiliser des attributs `alt` descriptifs pour les images (déjà présents pour la photo de profil).
- Vérifier le contraste des couleurs et les états au focus clavier (tab navigation).
- Tester avec des outils : Lighthouse, Axe (extension), WAVE.

---

## 🚀 Déploiement
Options courantes pour héberger un site statique :
- **GitHub Pages** (branch `main` ou `gh-pages`) — gratuit et simple.
- **Netlify / Vercel** — déploiement continu depuis Git, options de redirections et headers.
- Dépôt FTP / hébergement mutualisé si nécessaire.

Checklist avant déploiement :
- Vérifier `robots.txt` et `sitemap.xml`.
- S'assurer que le `CV` est à jour.
- Vérifier le rendu mobile et desktop.
- Lancer Lighthouse et corriger les recommandations critiques.

---

## 🔐 RGPD & Analytics (si vous ajoutez des trackers)
- Ajouter une **bannière de consentement** avant d'activer Google Analytics ou Matomo.
- Ne pas charger de scripts de tracking avant consentement explicite.

---

## 🧪 Tests et contrôle qualité
- Tester les performances avec **Lighthouse** (audit Performance, Accessibility, Best Practices, SEO).
- Contrôler l’accessibilité avec **axe-core** ou l’extension Axe pour Chrome.
- Vérifier que les liens externes ouvrent en `target="_blank"` et ont `rel="noopener noreferrer"`.

---

## 🧾 Changelog / Historique
- `v1.0` — Version initiale du portfolio (structure, CV intégré, mode sombre).

---

## 🤝 Contribution
Si vous souhaitez contribuer :
1. Forkez le dépôt
2. Créez une branche (`feat/ajout-xyz`)
3. Ouvrez une Pull Request expliquant vos changements

> Note : Ce dépôt contient des informations personnelles. Ne publiez pas de données sensibles.

---

## 📫 Contact
Pour toute question ou modification, contacter : **ngadiwassim@hotmail.com**

---

*Fichier généré pour faciliter la maintenance et le déploiement du portfolio. Mettre à jour ce README à chaque changement majeur.*
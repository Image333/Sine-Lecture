# Site Vitrine Sine-Lecture

Site vitrine statique moderne et responsive avec plusieurs catégories et un lien vers un formulaire Google.

## 🚀 Déploiement sur GitHub Pages

### Étape 1 : Préparer le dépôt GitHub

1. **Créer un nouveau dépôt sur GitHub** (si ce n'est pas déjà fait)
   - Allez sur https://github.com/new
   - Nommez votre dépôt (exemple: `Sine-Lecture`)
   - Choisissez Public ou Private
   - Ne cochez PAS "Initialize with README" (car vous avez déjà des fichiers)
   - Cliquez sur "Create repository"

### Étape 2 : Pousser votre code sur GitHub

Ouvrez un terminal dans le dossier de votre projet et exécutez :

```bash
# Initialiser Git (si pas encore fait)
git init

# Ajouter tous les fichiers
git add .

# Créer le premier commit
git commit -m "Initial commit - Site vitrine Sine-Lecture"

# Ajouter le dépôt distant (remplacez VOTRE_USERNAME par votre nom d'utilisateur GitHub)
git remote add origin https://github.com/Image333/Sine-Lecture.git

# Pousser vers GitHub
git branch -M main
git push -u origin main
```

### Étape 3 : Activer GitHub Pages

1. Allez sur votre dépôt GitHub
2. Cliquez sur **Settings** (Paramètres)
3. Dans le menu de gauche, cliquez sur **Pages**
4. Sous "Build and deployment" :
   - **Source** : Sélectionnez "GitHub Actions"
5. Le site sera automatiquement déployé grâce au workflow GitHub Actions

### Étape 4 : Personnaliser le formulaire Google

1. Créez votre formulaire Google sur https://forms.google.com
2. Cliquez sur "Envoyer" puis sur l'icône de lien
3. Copiez le lien du formulaire
4. Dans `index.html`, ligne 82, remplacez :
   ```html
   <a href="https://forms.google.com/VOTRE_LIEN_ICI" target="_blank" class="btn btn-secondary">
   ```
   par votre lien réel

### Étape 5 : Accéder à votre site

Votre site sera disponible à l'adresse :
```
https://image333.github.io/Sine-Lecture/
```

Le déploiement prend généralement 1-2 minutes. Vous pouvez suivre la progression dans l'onglet **Actions** de votre dépôt.

## 📝 Personnalisation

### Modifier le contenu

- **Titre et textes** : Éditez directement `index.html`
- **Catégories** : Modifiez les sections `.service-card` dans `index.html`
- **Couleurs** : Changez les variables CSS dans `styles.css` (lignes 9-18)
- **Icônes** : Remplacez les emojis par vos propres icônes

### Ajouter des images

Créez un dossier `images/` et modifiez la section `.placeholder-image` dans le CSS et HTML.

## 🛠️ Technologies utilisées

- HTML5
- CSS3 (avec animations et design responsive)
- JavaScript vanilla (navigation fluide, animations)
- GitHub Pages (hébergement)
- GitHub Actions (déploiement automatique)

## 📱 Responsive

Le site est entièrement responsive et s'adapte aux :
- 📱 Mobiles
- 📱 Tablettes
- 💻 Ordinateurs

## 📄 Structure du projet

```
Sine-Lecture/
├── index.html          # Page principale
├── styles.css          # Styles CSS
├── script.js           # JavaScript
├── README.md           # Documentation
└── .github/
    └── workflows/
        └── deploy.yml  # Configuration GitHub Actions
```

## ✨ Fonctionnalités

- ✅ Navigation fluide avec scroll smooth
- ✅ Menu hamburger responsive pour mobile
- ✅ Animations au scroll
- ✅ Design moderne avec dégradés
- ✅ Lien vers formulaire Google
- ✅ Déploiement automatique sur GitHub Pages

## 🔄 Mise à jour du site

Pour mettre à jour le site après modification :

```bash
git add .
git commit -m "Description de vos modifications"
git push
```

Le site sera automatiquement redéployé en 1-2 minutes.

## 📞 Support

Pour toute question, consultez la documentation GitHub Pages : https://docs.github.com/pages

---

Créé avec ❤️ pour Sine-Lecture

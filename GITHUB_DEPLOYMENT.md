# 📋 Guide de Déploiement sur GitHub Pages - Version Simplifiée

## 🚀 Instructions pour publier votre portfolio

### Étape 1 : Préparer le dépôt GitHub

1. **Créer un nouveau dépôt** sur GitHub :
   - Allez sur https://github.com/new
   - Nommez-le : `portfolio` ou `mon-portfolio`
   - Initialisez avec un README (optionnel)
   - Cliquez sur "Create repository"

2. **Cloner le dépôt localement** :
   ```bash
   git clone https://github.com/VOTRE_USERNAME/portfolio.git
   cd portfolio
   ```

### Étape 2 : Ajouter les fichiers du projet

1. **Copier les fichiers** du dossier `portfolio-simple` dans votre dépôt local :
   - `index.html` (le fichier principal)
   - `images/` (dossier avec la photo de profil)

2. **Vérifier la structure** :
   ```
   portfolio/
   ├── index.html
   ├── images/
   │   └── profile.jpg
   └── README.md (optionnel)
   ```

### Étape 3 : Publier sur GitHub Pages

1. **Ajouter les fichiers** :
   ```bash
   git add .
   git commit -m "Initial commit - Portfolio Antoine Desperrier"
   ```

2. **Pousser vers GitHub** :
   ```bash
   git push -u origin main
   ```

3. **Activer GitHub Pages** :
   - Allez sur votre dépôt GitHub
   - Cliquez sur **Settings** → **Pages**
   - Sous "Source", sélectionnez la branche `main`
   - Cliquez sur **Save**

4. **Attendez quelques minutes** et votre site sera disponible à :
   ```
   https://VOTRE_USERNAME.github.io/portfolio/
   ```

---

## 🎯 Avantages de cette version simplifiée

✅ **Un seul fichier HTML** - Facile à maintenir et à déployer  
✅ **Pas de dépendances** - Aucun npm, aucune compilation  
✅ **Temps de chargement rapide** - Tout est optimisé  
✅ **Responsive design** - Fonctionne sur tous les appareils  
✅ **Animations fluides** - CSS et JavaScript natif  
✅ **SEO-friendly** - Bien structuré pour les moteurs de recherche  

---

## 📝 Personnalisation

Si vous voulez modifier le portfolio :

1. **Ouvrez `index.html`** dans un éditeur de texte
2. **Modifiez le contenu** directement dans le fichier
3. **Sauvegardez** et testez localement en ouvrant le fichier dans votre navigateur
4. **Poussez les changements** sur GitHub :
   ```bash
   git add index.html
   git commit -m "Update portfolio content"
   git push
   ```

---

## 🔗 Domaine personnalisé

Si vous avez un domaine personnalisé :

1. Créez un fichier `CNAME` à la racine du projet avec votre domaine :
   ```
   mondomaine.com
   ```

2. Configurez les DNS chez votre registraire pour pointer vers GitHub Pages

3. Poussez le fichier `CNAME` sur GitHub

---

## 💡 Conseils

- **Testez localement** avant de pousser sur GitHub
- **Mettez à jour régulièrement** votre portfolio avec vos nouveaux projets
- **Vérifiez les liens** externes (GitHub, LinkedIn, email)
- **Optimisez les images** pour de meilleures performances

Bon déploiement ! 🚀

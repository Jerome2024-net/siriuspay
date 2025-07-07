# Guide de Déploiement GitHub Pages pour Sirius Pay

## 🚀 Déploiement rapide (5 minutes)

### Étape 1: Créer un compte GitHub
Si vous n'avez pas encore de compte GitHub :
1. Allez sur [github.com](https://github.com)
2. Cliquez sur "Sign up"
3. Suivez les instructions pour créer votre compte

### Étape 2: Créer un nouveau repository
1. Une fois connecté, cliquez sur le bouton vert "New" ou "New repository"
2. Nommez votre repository `sirius-pay`
3. Assurez-vous qu'il soit **Public**
4. Cochez "Add a README file"
5. Cliquez sur "Create repository"

### Étape 3: Uploader vos fichiers
1. Dans votre nouveau repository, cliquez sur "uploading an existing file"
2. Sélectionnez tous les fichiers de votre projet :
   - `index.html`
   - `README.md`
   - `LICENSE`
   - `site.webmanifest`
   - `robots.txt`
   - `.gitignore`
   - Le dossier `.github/` complet
3. Ajoutez un message de commit : "🚀 Initial deployment of Sirius Pay"
4. Cliquez sur "Commit changes"

### Étape 4: Activer GitHub Pages
1. Allez dans l'onglet **"Settings"** de votre repository
2. Dans le menu de gauche, cliquez sur **"Pages"**
3. Dans la section "Source" :
   - Sélectionnez "Deploy from a branch"
   - Choisissez la branche **"main"**
   - Laissez "/ (root)" sélectionné
4. Cliquez sur **"Save"**

### Étape 5: Accéder à votre site
- Votre site sera disponible à : `https://VOTRE_USERNAME.github.io/sirius-pay`
- GitHub vous donnera l'URL exacte dans la section Pages
- ⏱️ **Patience** : Le déploiement prend 2-10 minutes

## 🔧 Déploiement via Git CLI (pour les développeurs)

Si vous préférez utiliser la ligne de commande :

```bash
# 1. Initialisez Git dans votre dossier
git init

# 2. Ajoutez tous les fichiers
git add .

# 3. Créez votre premier commit
git commit -m "🚀 Initial deployment of Sirius Pay"

# 4. Ajoutez l'origin remote (remplacez VOTRE_USERNAME)
git remote add origin https://github.com/VOTRE_USERNAME/sirius-pay.git

# 5. Poussez vers GitHub
git branch -M main
git push -u origin main
```

Ensuite, suivez l'étape 4 ci-dessus pour activer Pages.

## ✅ Vérification du déploiement

### Votre site fonctionne si :
- ✅ L'URL `https://VOTRE_USERNAME.github.io/sirius-pay` s'ouvre
- ✅ Le design est responsive sur mobile/desktop
- ✅ Les animations fonctionnent correctement
- ✅ La navigation smooth scroll fonctionne

### En cas de problème :
1. **404 Error** : Vérifiez que le fichier s'appelle exactement `index.html`
2. **Styles cassés** : Vérifiez que tout le CSS est dans le `<style>` tag
3. **GitHub Pages désactivé** : Retournez dans Settings > Pages

## 🎨 Personnalisation de l'URL

### Option 1: Repository personnalisé
- Renommez votre repository avec le nom que vous voulez
- L'URL sera : `https://VOTRE_USERNAME.github.io/NOM_DU_REPO`

### Option 2: Domaine personnalisé
- Achetez un domaine (ex: siriuspay.com)
- Dans Settings > Pages > Custom domain
- Ajoutez votre domaine et activez HTTPS

## 🔄 Mise à jour du site

Pour mettre à jour votre site :

### Via l'interface GitHub :
1. Cliquez sur le fichier à modifier
2. Cliquez sur l'icône ✏️ "Edit this file"
3. Effectuez vos modifications
4. Commitez avec un message descriptif
5. Le site se met à jour automatiquement en 2-5 minutes

### Via Git CLI :
```bash
git add .
git commit -m "🎨 Update design/content"
git push
```

## 📊 Suivi et Analytics

### Google Analytics (optionnel)
Ajoutez ce code avant `</head>` dans index.html :

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🚨 Troubleshooting

### Problèmes courants :

1. **Le site ne se charge pas**
   - Attendez 10 minutes après l'activation
   - Vérifiez que le repository est public
   - Assurez-vous que `index.html` est à la racine

2. **Erreur 404**
   - Le fichier doit s'appeler exactement `index.html`
   - Vérifiez la casse (majuscules/minuscules)

3. **Styles non appliqués**
   - Tout le CSS doit être inline dans `<style>`
   - Pas de fichiers CSS externes pour GitHub Pages simple

4. **JavaScript ne fonctionne pas**
   - Tout le JS doit être inline dans `<script>`
   - Vérifiez la console du navigateur pour les erreurs

## 📞 Support

Si vous avez des problèmes :
1. Vérifiez la documentation GitHub Pages
2. Regardez les logs dans l'onglet "Actions" de votre repo
3. Testez localement d'abord

---

**🎉 Félicitations ! Votre site Sirius Pay est maintenant en ligne !**

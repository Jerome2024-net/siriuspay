# 🚀 Commandes Git pour Déploiement Automatique

## Méthode recommandée : Upload via GitHub

1. **Allez sur** : https://github.com/Jerome2024-net/siriuspay
2. **Cliquez sur** : "Add file" → "Upload files"
3. **Glissez tous les fichiers** de ce dossier
4. **Commit message** : `🚀 Initial deployment: Sirius Pay landing page`
5. **Activez Pages** : Settings → Pages → Deploy from branch "main"

## Alternative : Git CLI (pour développeurs)

Si vous préférez la ligne de commande :

```powershell
# 1. Initialiser Git dans ce dossier
git init

# 2. Ajouter tous les fichiers
git add .

# 3. Premier commit
git commit -m "🚀 Initial deployment: Sirius Pay landing page

- Complete landing page with modern design
- Responsive mobile-first approach
- SEO optimized with meta tags
- GitHub Pages ready configuration
- Full documentation included"

# 4. Ajouter le remote repository
git remote add origin https://github.com/Jerome2024-net/siriuspay.git

# 5. Créer la branche main et push
git branch -M main
git push -u origin main
```

## 🔄 Pour les mises à jour futures

```powershell
# Ajouter les modifications
git add .

# Commit avec message descriptif
git commit -m "✨ Update: [décrivez vos changements]"

# Push vers GitHub
git push origin main
```

## ⚡ Commandes rapides de maintenance

```powershell
# Vérifier le statut
git status

# Voir l'historique
git log --oneline

# Voir les différences
git diff

# Annuler des changements locaux
git checkout -- .
```

## 🎯 URLs importantes

- **Repository** : https://github.com/Jerome2024-net/siriuspay
- **Site live** : https://jerome2024-net.github.io/siriuspay
- **Issues** : https://github.com/Jerome2024-net/siriuspay/issues
- **Actions** : https://github.com/Jerome2024-net/siriuspay/actions

## 📝 Notes importantes

- Le site sera live à : **https://jerome2024-net.github.io/siriuspay**
- Temps de déploiement : **2-10 minutes** après le push
- Les changements sont **automatiquement déployés** via GitHub Actions
- Vérifiez l'onglet **"Actions"** pour voir le statut du déploiement

---

**🚀 Prêt pour le déploiement !**

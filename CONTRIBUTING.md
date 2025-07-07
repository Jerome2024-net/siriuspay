# Guide de Contribution - Sirius Pay

Merci de votre intérêt pour contribuer à Sirius Pay ! 🎉

## 🤝 Comment contribuer

### Types de contributions

Nous accueillons plusieurs types de contributions :

- 🐛 **Corrections de bugs**
- ✨ **Nouvelles fonctionnalités**
- 📚 **Amélioration de la documentation**
- 🎨 **Améliorations du design**
- ⚡ **Optimisations de performance**
- 🌍 **Traductions**

### Processus de contribution

1. **Fork** le repository
2. **Créez une branche** pour votre fonctionnalité (`git checkout -b feature/ma-fonctionnalite`)
3. **Committez** vos changements (`git commit -m '✨ Ajout ma fonctionnalité'`)
4. **Poussez** vers la branche (`git push origin feature/ma-fonctionnalite`)
5. **Ouvrez une Pull Request**

## 🎯 Guidelines de développement

### Style de code

#### HTML
- Utilisez du HTML5 sémantique
- Indentation de 4 espaces
- Attributs en ordre logique (class, id, data-*)
- Commentaires en français pour les sections importantes

#### CSS
- Utilisez des noms de classes descriptifs
- Suivez la méthodologie BEM si applicable
- Organisez les propriétés par ordre logique
- Utilisez des variables CSS pour les couleurs récurrentes
- Privilégiez `flexbox` et `grid` pour les layouts
- Animations avec `transform` et `opacity` pour la performance

#### JavaScript
- ES6+ uniquement
- Fonctions pures quand possible
- Commentaires explicatifs en français
- Nommage en camelCase
- Évitez les dépendances externes

### Design Guidelines

#### Couleurs
```css
:root {
    --primary-blue: #007aff;
    --text-dark: #1d1d1f;
    --text-light: #6e6e73;
    --background: #fafafa;
    --white: #ffffff;
}
```

#### Typography
- Police principale : SF Pro Display (système Apple)
- Hiérarchie typographique claire
- Contraste minimum AA (4.5:1)

#### Animations
- Durée : 0.3s à 0.6s
- Easing : `cubic-bezier(0.4, 0, 0.2, 1)`
- Privilégier les micro-interactions
- 60fps obligatoire

### Responsive Design

#### Breakpoints
- Mobile : 320px - 768px
- Tablette : 768px - 1024px  
- Desktop : 1024px+

#### Approche
- Mobile-first
- Tests sur vrais appareils
- Touch targets minimum 44px

## 🐛 Signaler un bug

### Avant de créer un issue

1. Vérifiez si le bug n'a pas déjà été signalé
2. Testez sur la dernière version
3. Reproduisez le bug sur différents navigateurs

### Template de bug report

```markdown
**Description du bug**
Description claire et concise du problème.

**Étapes pour reproduire**
1. Allez sur '...'
2. Cliquez sur '...'
3. Scrollez jusqu'à '...'
4. Le bug apparaît

**Comportement attendu**
Description du comportement normal.

**Screenshots**
Si applicable, ajoutez des screenshots.

**Environnement:**
- OS: [ex. Windows 11]
- Navigateur: [ex. Chrome 91.0]
- Version mobile: [ex. iPhone 12, iOS 14.6]
```

## ✨ Proposer une fonctionnalité

### Template de feature request

```markdown
**Problème résolu**
Description claire du problème que cette fonctionnalité résoudrait.

**Solution proposée**
Description détaillée de la solution.

**Alternatives considérées**
Autres solutions envisagées.

**Contexte additionnel**
Screenshots, mockups, ou contexte supplémentaire.
```

## 🎨 Guidelines de design

### Principes de design

1. **Simplicité** : Interface claire et épurée
2. **Cohérence** : Respect de la charte graphique
3. **Accessibilité** : Design inclusif pour tous
4. **Performance** : Optimisation des animations
5. **Mobile-first** : Expérience mobile prioritaire

### Checklist design

- [ ] Contraste suffisant (min 4.5:1)
- [ ] Tailles de police lisibles (min 16px mobile)
- [ ] Zones de touch appropriées (min 44px)
- [ ] Animations fluides (60fps)
- [ ] États de hover/focus définis
- [ ] Responsive sur tous breakpoints

## 📝 Documentation

### Mise à jour de la documentation

Lors de l'ajout de nouvelles fonctionnalités :

1. Mettez à jour le `README.md`
2. Ajoutez une entrée dans `CHANGELOG.md`
3. Documentez dans `TODO.md` si applicable
4. Mettez à jour les commentaires du code

### Style de documentation

- Utilisez des emojis pour la lisibilité
- Sections claires avec headers
- Exemples de code quand nécessaire
- Screenshots pour les features visuelles

## 🔄 Process de review

### Critères d'acceptation

- ✅ Code propre et documenté
- ✅ Tests manuels effectués
- ✅ Responsive design validé
- ✅ Performance maintenue
- ✅ Accessibilité respectée
- ✅ Documentation mise à jour

### Timeline

- Review initiale : 2-3 jours
- Feedback et corrections : 1-2 jours
- Merge final : 1 jour

## 🌍 Traductions

### Langues prioritaires

1. **Français** 🇫🇷
2. **Swahili** 🇰🇪
3. **Hausa** 🇳🇬
4. **Yoruba** 🇳🇬
5. **Amharique** 🇪🇹

### Structure des traductions

```
/i18n
  /en.json
  /fr.json
  /sw.json (swahili)
  /ha.json (hausa)
```

## 📊 Tests

### Tests requis

- [ ] **Cross-browser** : Chrome, Firefox, Safari, Edge
- [ ] **Mobile** : iOS Safari, Chrome Android
- [ ] **Performance** : Lighthouse score > 90
- [ ] **Accessibilité** : Screen reader compatible

### Outils recommandés

- Lighthouse (performance)
- WAVE (accessibilité)
- BrowserStack (cross-browser)

## 💬 Communication

### Channels

- **GitHub Issues** : Bugs et features
- **GitHub Discussions** : Questions générales
- **Pull Requests** : Code reviews

### Code de conduite

- Respectueux et inclusif
- Constructif dans les feedbacks
- Patience avec les nouveaux contributeurs
- Focus sur l'amélioration du produit

## 🏆 Reconnaissance

Les contributeurs seront ajoutés dans :
- Section "Contributors" du README
- Page "About" du site (si applicable)
- Release notes pour les contributions majeures

## 📞 Besoin d'aide ?

- Consultez la [documentation](README.md)
- Créez une [Discussion GitHub](https://github.com/YOUR_USERNAME/sirius-pay/discussions)
- Regardez les [Issues existantes](https://github.com/YOUR_USERNAME/sirius-pay/issues)

---

**Merci de contribuer à rendre Sirius Pay encore meilleur ! 🚀**

# Auto-évaluation CV Web - Moulaoui Noa

## 1. Résultats des validateurs

### Validation W3C HTML
- **Version 1** : 12 erreurs, 5 warnings
- **Version finale** : 0 erreur, 1 warning acceptable
- **Captures d'écran** : voir `/screenshots/w3c-v1.png` et `/screenshots/w3c-final.png`

### Test Outiref
- **SEO** : 75/100 → 92/100
- **Problèmes corrigés** :
  - H1 en double supprimé
  - Meta description ajoutée (148 caractères)
  - Title optimisé

### PageSpeed Insights
- **Mobile** : 68/100 → 91/100 (+23 points)
- **Desktop** : 85/100 → 96/100 (+11 points)
- **Améliorations** :
  - Images compressées (gain 1.8 Mo)
  - CSS minifié
  - Defer ajouté sur scripts

## 2. Analyse des causes

### Problèmes identifiés
1. **Performance faible** : Image photo.jpg non optimisée (2.1 Mo)
2. **SEO insuffisant** : Balises meta manquantes
3. **Accessibilité** : Contrastes insuffisants sur liens (ratio 2.8:1)

### Actions correctives
1. Conversion photo en WebP + compression → 85 Ko
2. Ajout de toutes les balises meta essentielles
3. Modification couleur liens (#0066cc → #0052a3) pour ratio 4.6:1

## 3. Impact mesuré

| Critère | Avant | Après | Gain |
|---------|-------|-------|------|
| Temps de chargement | 1.8s | 0.6s | -67% |
| Score Performance Mobile | 68 | 91 | +34% |
| Score Accessibilité | 78 | 93 | +19% |
| SEO Outiref | 75 | 92 | +23% |

## 4. Difficultés rencontrées

- Compression WebP : apprentissage de GIMP/Squoosh
- Bootstrap responsive : compréhension des breakpoints
- Navigation clavier : tests avec Tab peu intuitifs au début

## 5. Points forts du projet

- Site en ligne fonctionnel
- 0 erreur W3C en version finale
- Performance mobile > 90
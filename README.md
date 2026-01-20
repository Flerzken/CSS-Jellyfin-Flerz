# 🎬 Jellyfin Theme - Flerz Edition

Un thème CSS moderne et élégant pour Jellyfin avec une palette violette premium.

![Preview](https://img.shields.io/badge/Jellyfin-10.8%2B-purple?style=for-the-badge&logo=jellyfin)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

## ✨ Caractéristiques

- 🎨 **Design moderne** - Inspiré des plateformes de streaming actuelles
- 💜 **Palette violette premium** - Look unique et élégant
- 📱 **Full responsive** - Mobile, tablette, desktop et TV
- ⚡ **Animations légères** - Optimisées GPU pour de bonnes performances
- ♿ **Accessible** - Support `prefers-reduced-motion` et focus visible
- 🌙 **Mode sombre** - Confortable pour les yeux

## 📸 Aperçu

### Page d'accueil
- Cartes avec effet de zoom au survol
- Carousels fluides
- Header avec effet blur

### Page de détails
- Backdrop avec dégradé élégant
- Boutons d'action modernes
- Informations bien organisées

### Lecteur vidéo
- Contrôles stylisés
- Barre de progression améliorée
- Animations subtiles

## 🚀 Installation

### Méthode 1 : Via le Dashboard (recommandée)

1. Connectez-vous à votre serveur Jellyfin en tant qu'administrateur
2. Allez dans **Administration** → **Tableau de bord** → **Général**
3. Descendez jusqu'à la section **CSS personnalisé**
4. Copiez le contenu du fichier [`jellyfin-theme.css`](./jellyfin-theme.css)
5. Collez-le dans le champ CSS personnalisé
6. Cliquez sur **Enregistrer**

### Méthode 2 : Import via URL

Dans le champ CSS personnalisé, ajoutez :

```css
@import url('https://raw.githubusercontent.com/Flerzken/CSS-Jellyfin-Flerz/main/jellyfin-theme.css');
```

## 🎨 Personnalisation

### Modifier les couleurs

Les couleurs principales sont définies dans les variables CSS au début du fichier :

```css
:root {
  --accent-primary: #7b2cbf;    /* Couleur principale */
  --accent-secondary: #9d4edd;  /* Couleur secondaire */
  --accent-light: #c77dff;      /* Couleur claire */
  --bg-primary: #0a0a0f;        /* Fond principal */
  --bg-secondary: #16161d;      /* Fond secondaire */
}
```

### Exemples de palettes alternatives

**Bleu océan :**
```css
--accent-primary: #0077b6;
--accent-secondary: #00b4d8;
--accent-light: #90e0ef;
```

**Rouge passion :**
```css
--accent-primary: #c9184a;
--accent-secondary: #ff4d6d;
--accent-light: #ff758f;
```

**Vert nature :**
```css
--accent-primary: #2d6a4f;
--accent-secondary: #40916c;
--accent-light: #74c69d;
```

## 📁 Structure du projet

```
Jellyfin-CSS/
├── README.md              # Ce fichier
├── jellyfin-theme.css     # 🎯 Fichier à utiliser (bundle complet)
└── src/                   # Fichiers sources modulaires
    ├── _variables.css     # Variables CSS
    ├── _base.css          # Styles de base
    ├── _components.css    # Composants UI
    ├── _login.css         # Page de connexion
    ├── _header.css        # Header et navigation
    ├── _dashboard.css     # Page d'accueil
    ├── _library.css       # Bibliothèques
    ├── _details.css       # Pages de détails
    ├── _player.css        # Lecteur vidéo
    └── _animations.css    # Animations
```

## ✅ Compatibilité

| Jellyfin | Statut |
|----------|--------|
| 10.9.x   | ✅ Supporté |
| 10.8.x   | ✅ Supporté |
| < 10.8   | ⚠️ Non testé |

| Navigateur | Statut |
|------------|--------|
| Chrome/Edge | ✅ |
| Firefox | ✅ |
| Safari | ✅ |
| TV WebOS/Tizen | ✅ |

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :
- 🐛 Signaler des bugs
- 💡 Proposer des améliorations
- 🔀 Soumettre des pull requests

## 📄 Licence

MIT License - Libre d'utilisation et de modification.

---

Créé avec 💜 par Flerz

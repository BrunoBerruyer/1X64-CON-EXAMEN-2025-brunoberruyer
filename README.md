# 🧠 Cabinet de Psychologie - Odile Jacmain

Site web professionnel pour le cabinet de psychologie clinique d'Odile Jacmain, développé dans le cadre de l'examen 1X64-CON-EXAMEN-025.

🔗 **Voir le site en ligne** : https://1x64-con-examen-2025-brunoberruyer1x6.netlify.app/

🏆 **Performance validée** : Scores Lighthouse de 94-100/100

## 📋 Table des matières

- [🎯 Contexte du projet](#-contexte-du-projet)
- [🛠️ Technologies utilisées](#️-technologies-utilisées)
- [🚀 Process de développement](#-process-de-développement)
- [📁 Architecture du projet](#-architecture-du-projet)
- [✨ Fonctionnalités implémentées](#-fonctionnalités-implémentées)
- [🏆 Scores Lighthouse](#-scores-lighthouse)
- [💻 Installation et utilisation](#-installation-et-utilisation)
- [🔄 Améliorations futures](#-améliorations-futures)

## 🎯 Contexte du projet

Développement d'une landing page moderne respectant un cahier des charges strict :

- ✅ Site single-page avec navigation par ancrage
- ✅ 3 sections minimum en plein écran (100vh)
- ✅ HTML et CSS purs (aucun framework, aucun JavaScript)
- ✅ Design Desktop-First
- ✅ Utilisation obligatoire de Flexbox et/ou Grid

## 🛠️ Technologies utilisées

- **HTML5** : Structure sémantique complète
- **CSS3** : Styles avancés avec variables personnalisées
- **Google Fonts** : Police Montserrat
- **Web3Forms** : Gestion du formulaire de contact (API externe, sans JS)
- **Git/GitHub** : Versioning
- **Netlify** : Déploiement

**Point fort** : Aucun JavaScript utilisé - site 100% HTML/CSS pur ! 🎯

## 🚀 Process de développement

### 🎨 Phase 1 : Conception initiale

- Analyse approfondie des consignes d'examen
- Recherche d'inspiration pour le design néomorphisme
- Définition de la palette de couleurs (tons verts apaisants)
- Structuration mentale : 3 sections + navigation + footer

### 🏗️ Phase 2 : Développement de base

**Structure HTML**
- Mise en place de la structure sémantique
- Navigation fixe avec liens d'ancrage
- Sections fullscreen avec IDs
- Balises sémantiques : `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`

**Design néomorphisme**
- Variables CSS pour la cohérence
- Effets d'ombres caractéristiques
- Palette de couleurs professionnelle
- Typographie soignée avec Google Fonts

### ⚡ Phase 3 : Fonctionnalités avancées

**Animations CSS pures**
- Smooth scrolling natif (CSS only)
- Transitions sur les liens de navigation
- Effets hover sur les cartes de services
- Animations des boutons (transform, shadow)
- Focus states sur le formulaire

**Formulaire de contact Web3Forms**
- Intégration du service Web3Forms (sans JavaScript)
- Layout en deux colonnes
- Validation HTML5 native
- Protection anti-spam
- Design cohérent avec le reste du site

### 🔧 Phase 4 : Optimisations

**Performance**
- Variables CSS avec `clamp()`, `calc()`, `min()`, `max()`
- Images optimisées
- Structure de code optimale
- Commentaires détaillés
- Aucun script = chargement ultra-rapide

**SEO avancé**
- Meta tags complets (description, keywords, author)
- Open Graph pour les réseaux sociaux
- Twitter Cards
- Données structurées JSON-LD
- URL canonique
- Attributs alt sur les images

### 🏗️ Phase 5 : Architecture CSS modulaire

Refactorisation complète du CSS en architecture modulaire :

**Analyse et planification**
- Identification des composants réutilisables
- Définition de la structure des dossiers
- Sauvegarde du CSS original

**Découpage en modules**
```
styles/
├── main.css          # Fichier principal avec @import
├── base/
│   ├── variables.css # Variables CSS globales
│   └── reset.css     # Reset et styles de base
├── layout/
│   ├── header.css    # Navigation et header
│   ├── sections.css  # Styles communs aux sections
│   └── footer.css    # Footer
├── components/
│   ├── buttons.css   # Tous les styles de boutons
│   ├── cards.css     # Cartes de présentation et services
│   ├── forms.css     # Formulaire de contact
│   ├── hero.css      # Section d'accueil
│   ├── services.css  # Section services
│   └── contact.css   # Section contact
└── utilities/
    ├── animations.css # Animations et transitions
    ├── helpers.css    # Classes utilitaires
    └── responsive.css # Media queries (préparé pour futur)
```

**Réorganisation des assets**
```
assets/
└── images/
    ├── fond_section1_profil.png
    ├── profil.png
    └── favicon.ico
```

## 📁 Architecture du projet

```
1X64-CON-EXAMEN-2025-brunoberruyer/
├── index.html              # Page principale HTML
├── assets/                 # Ressources
│   └── images/            # Images du site
├── styles/                # Architecture CSS modulaire
│   ├── main.css           # Point d'entrée CSS
│   ├── base/              # Fondations
│   ├── layout/            # Structure
│   ├── components/        # Composants
│   └── utilities/         # Utilitaires
├── .gitignore             # Fichiers à ignorer par Git
└── README.md              # Documentation
```

## ✨ Fonctionnalités implémentées

### 🧭 Navigation
- Menu fixe en haut de page
- Navigation par ancrage smooth scroll (CSS only)
- Animations au survol des liens
- Indication visuelle de l'état actif

### 🏠 Section Accueil
- Image de fond atmosphérique
- Carte de présentation avec effet néomorphisme
- Boutons d'appel à l'action
- Texte de présentation professionnelle

### 💼 Section Services
- 3 cartes de services avec icônes SVG
- Effet de lévitation au survol (CSS transform)
- Descriptions détaillées
- Liens vers la section contact

### 📧 Section Contact
- Formulaire fonctionnel via Web3Forms
- Layout responsive en deux colonnes
- Photo professionnelle
- Validation des champs HTML5 native
- Message de confirmation

### 🎨 Design et UX
- Design néomorphisme cohérent
- Palette de couleurs apaisante
- Typographie lisible et professionnelle
- Feedback visuel sur toutes les interactions
- Transitions fluides CSS

## 🏆 Scores Lighthouse

Le projet a obtenu des scores exceptionnels lors de l'audit Lighthouse, démontrant une qualité professionnelle sur tous les critères :

### 📊 Résultats de l'audit

| Critère | Score | Statut |
|---------|-------|--------|
| 🚀 **Performance** | 98/100 | Excellent |
| ♿ **Accessibilité** | 94/100 | Très bien |
| ✅ **Bonnes pratiques** | 100/100 | Parfait |
| 🔍 **SEO** | 100/100 | Parfait |

### 🎯 Points forts identifiés

- **Temps de chargement ultra-rapide** : First Contentful Paint de 0.7s
- **Optimisation des ressources** : Images optimisées et chargement efficace
- **Accessibilité exemplaire** : Navigation au clavier, contrastes respectés
- **SEO parfait** : Toutes les bonnes pratiques respectées
- **Code de qualité** : HTML/CSS pur, aucun JavaScript, CSP configuré

### 📈 Métriques de performance détaillées

- **First Contentful Paint (FCP)** : 0.7s ⚡
- **Largest Contentful Paint (LCP)** : 0.8s ⚡
- **Total Blocking Time (TBT)** : 0ms ✨
- **Cumulative Layout Shift (CLS)** : 0.002 🎯
- **Speed Index** : 1.5s 🚀

Ces scores exceptionnels garantissent une expérience utilisateur optimale et un référencement naturel efficace. L'absence de JavaScript contribue significativement à ces performances.

## 💻 Installation et utilisation

### 📋 Prérequis
- Navigateur web moderne (Chrome, Firefox, Safari, Edge)
- Éditeur de code pour modifications
- Git pour le versioning (optionnel)

### 🚀 Installation locale

```bash
# Cloner le repository
git clone https://github.com/BrunoBerruyer/1X64-CON-EXAMEN-2025-brunoberruyer.git

# Naviguer dans le dossier
cd 1X64-CON-EXAMEN-2025-brunoberruyer

# Ouvrir dans le navigateur
# Option 1 : Double-clic sur index.html
# Option 2 : Utiliser un serveur local (Live Server VS Code)
```

### ⚙️ Configuration du formulaire

Le formulaire utilise Web3Forms. Pour personnaliser :

1. Créer un compte sur [Web3Forms](https://web3forms.com/) 📧
2. Obtenir une clé d'accès 🔑
3. Remplacer la clé dans index.html :

```html
<input type="hidden" name="access_key" value="VOTRE_CLE">
```

## 🔄 Améliorations futures

### 📱 1. Responsive Design complet
- Adaptation mobile (320px - 768px)
- Version tablette (768px - 1024px)
- Navigation burger pour petits écrans
- Images adaptatives avec srcset
- Grilles flexibles

### ♿ 2. Accessibilité renforcée
- Attributs ARIA complets
- Skip navigation
- Meilleur contraste sur certains éléments
- Tests avec lecteurs d'écran
- Navigation complète au clavier

### ⚡ 3. Performance
- Lazy loading des images
- Critical CSS inline
- Minification CSS/HTML
- Compression des images
- Service Worker pour mode offline

### 🚀 4. Fonctionnalités
- Système de prise de rendez-vous intégré
- Blog ou section actualités
- Témoignages patients
- Multi-langue (FR/NL/EN)
- Carte interactive pour localisation

### 📊 5. SEO et Analytics
- Intégration Google Analytics
- Search Console
- Sitemap XML
- Robots.txt
- Rich snippets améliorés

### 🔒 6. Sécurité
- HTTPS obligatoire
- Headers de sécurité
- Protection CSRF sur formulaire
- Validation côté serveur

## ✅ Bonnes pratiques appliquées

- **Clean Code** : Code commenté et organisé
- **DRY** : Pas de répétition inutile
- **Sémantique** : HTML5 sémantique complet
- **Maintenabilité** : Architecture modulaire
- **Performance** : Optimisations CSS modernes, aucun JavaScript
- **Accessibilité** : Standards WCAG de base
- **SEO** : Optimisation pour les moteurs de recherche
- **Qualité mesurée** : Scores Lighthouse de 94-100/100 sur tous les critères
- **Simplicité** : HTML/CSS pur sans dépendances JavaScript

## 👨‍💻 Auteur

**Bruno Berruyer**  
Formation UX/UI Design - EFP  
[LinkedIn](https://www.linkedin.com/in/bruno-berruyer-63a902293/)

---

Projet réalisé dans le cadre de l'examen 1X64-CON-025 - Juin 2025 🎓
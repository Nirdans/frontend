# TechForge - Site Web de Conseil Financier

![Prosperix Logo](img/Prosperix.svg)

## 📋 Description

TechForge est un site web moderne et responsive dédié aux services de conseil financier. Le site présente les services de **Prosperix**, une entreprise spécialisée dans la gestion de patrimoine, la planification financière et les conseils en investissement.

## ✨ Fonctionnalités

- **Design Responsive** : Interface adaptée à tous les appareils (desktop, tablette, mobile)
- **Navigation Intuitive** : Menu de navigation clair avec version mobile hamburger
- **Sections Interactives** :
  - Hero section avec formulaire d'inscription
  - Section expertise avec présentation des services
  - Section services détaillée
  - Témoignages clients
  - Section équipe et services
  - Call-to-action pour inscription gratuite
  - Footer complet avec liens et informations de contact

## 🛠️ Technologies Utilisées

- **HTML5** : Structure sémantique moderne
- **CSS3** : Styles avancés avec animations et transitions
- **Tailwind CSS** : Framework CSS utilitaire via CDN
- **JavaScript Vanilla** : Interactions pour le menu mobile
- **Google Fonts** : Typographie Inter pour une meilleure lisibilité

## 🎨 Design

### Palette de Couleurs

- **Couleur principale** : `#008080` (Teal)
- **Couleur secondaire** : `#20CFC6` (Turquoise clair)
- **Couleur de texte** : `#374151` (Gris foncé)
- **Arrière-plan** : `#FFFFFF` (Blanc)

### Typographie

- **Police** : Inter (Google Fonts)
- **Poids** : 400 (Regular), 600 (Semi-bold), 700 (Bold)

## 📁 Structure du Projet
 
```
techforge/
├── index.html              # Page principale
├── none.html               # Page secondaire
├── tailwind.config.js      # Configuration Tailwind (vide)
├── img/                    # Dossier des images
│   ├── Prosperix.svg       # Logo principal
│   ├── Main image.png      # Image hero section
│   ├── Company logos.png   # Logos des partenaires
│   ├── Experince section.png # Image section expertise
│   ├── Servvice section.png # Image section services
│   ├── Images.png          # Image call-to-action
│   ├── Mask group*.png     # Photos des témoignages
│   ├── Group 29-31.svg     # Icônes réseaux sociaux
│   └── fi-rr-*.svg         # Icônes services
├── .git/                   # Contrôle de version Git
├── .github/                # Configuration GitHub
└── README.md               # Documentation du projet
```

## 🚀 Installation et Utilisation

### Prérequis

- Serveur web local (Apache, Nginx, ou serveur de développement)
- Navigateur web moderne

### Installation

1. Clonez le repository :

```bash
git clone [URL_DU_REPO]
cd techforge
```

2. Lancez un serveur web local :

```bash
# Avec Python 3
python -m http.server 8000

# Avec PHP
php -S localhost:8000

# Avec Node.js (http-server)
npx http-server
```

3. Ouvrez votre navigateur et accédez à `http://localhost:8000`

### Déploiement

Le site peut être déployé sur n'importe quel hébergeur web statique :

- GitHub Pages
- Netlify
- Vercel
- Hébergement traditionnel (cPanel, etc.)

## 📱 Responsive Design

Le site est entièrement responsive avec les breakpoints suivants :

- **Mobile** : < 768px
- **Tablette** : 768px - 1024px
- **Desktop** : > 1024px

## 🎯 Sections Principales

### 1. Header & Navigation

- Logo Prosperix
- Menu de navigation centré
- Boutons d'action (Sign in, Get Started)
- Menu hamburger pour mobile

### 2. Hero Section

- Titre accrocheur avec mot-clé en surbrillance
- Description des services
- Formulaire d'inscription avec email
- Image principale illustrative
- Logos des partenaires

### 3. Section Expertise

- Badge "OUR EXPERTISE"
- Titre de section
- Description détaillée des services
- Bouton d'action
- Image d'illustration

### 4. Section Services

- Badge "OUR SERVICES"
- Présentation des 4 services principaux :
  - Financial Planning
  - Investment Advisory
  - Estate Planning
  - Wealth Management
- Image dashboard

### 5. Témoignages

- 3 témoignages clients avec photos
- Design en carte avec témoignage central mis en valeur
- Citations avec guillemets stylisés

### 6. Services de l'Équipe

- 3 services détaillés avec icônes :
  - Expert Guidance
  - Risk Management
  - Customized Solutions
- Liens "Read more"

### 7. Call-to-Action

- Section d'inscription gratuite
- Formulaire email simplifié
- Image équipe avec overlay dashboard
- Contact direct

### 8. Footer

- Informations de l'entreprise
- Liens des services
- Navigation supplémentaire
- Informations de contact
- Réseaux sociaux
- Copyright et mentions légales

## 🎨 Animations et Interactions

- **Hover Effects** : Boutons avec changement de couleur et échelle
- **Transitions** : Animations fluides (300ms)
- **Focus States** : États de focus accessibles pour les formulaires
- **Menu Mobile** : Animation d'ouverture/fermeture

## 📞 Contact

Pour toute question concernant ce projet :

- **Email** : contact@briofin.com
- **Téléphone** : +1 (555) 123-4567

## 📄 Licence

© DSCODE 2023 - Tous droits réservés

## 🔧 Développement

### Améliorations Possibles

- [ ] Intégration d'un système de gestion de contenu (CMS)
- [ ] Ajout d'animations JavaScript avancées
- [ ] Optimisation SEO avancée
- [ ] Intégration de Google Analytics
- [ ] Système de formulaires fonctionnel
- [ ] Version multilingue
- [ ] Mode sombre/clair

### Contribution

Les contributions sont les bienvenues ! N'hésitez pas à ouvrir une issue ou soumettre une pull request.

---

_Développé avec ❤️ pour offrir la meilleure expérience utilisateur en conseil financier._

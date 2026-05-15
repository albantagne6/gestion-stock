# Frontend - React

## 📋 Description

Interface utilisateur du système de gestion de stock développée avec React.

## 🚀 Installation

### Prérequis
- Node.js 16+
- npm ou yarn

### Étapes

1. **Installer les dépendances**
```bash
npm install
```

2. **Configurer les variables d'environnement**
```bash
cp .env.example .env.local
# Éditez .env.local avec vos paramètres
```

3. **Lancer le serveur de développement**
```bash
npm start
```

L'application sera accessible à `http://localhost:3000`

## 📁 Structure du Projet

```
src/
├── components/           # Composants réutilisables
│   ├── Navbar/
│   ├── Sidebar/
│   ├── Form/
│   └── Table/
├── pages/               # Pages principales
│   ├── Dashboard/
│   ├── Products/
│   ├── Inventory/
│   ├── Orders/
│   ├── Reports/
│   ├── Users/
│   └── Login/
├── services/            # Services API
│   ├── api.js
│   ├── authService.js
│   ├── productService.js
│   ├── inventoryService.js
│   ├── orderService.js
│   └── reportService.js
├── context/             # React Context
│   ├── AuthContext.js
│   └── AppContext.js
├── hooks/               # Custom Hooks
│   ├── useAuth.js
│   ├── useFetch.js
│   └── useForm.js
├── utils/               # Utilitaires
│   ├── constants.js
│   ├── validators.js
│   └── helpers.js
├── styles/              # Styles CSS
│   ├── global.css
│   └── variables.css
├── App.jsx
└── index.js
```

## 📚 Pages Principales

### Dashboard
Tableau de bord avec aperçu des statistiques principales.

### Products
Gestion complète des produits (CRUD).

### Inventory
Suivi des niveaux de stock.

### Orders
Gestion des commandes.

### Reports
Rapports et statistiques détaillés.

### Users
Gestion des utilisateurs et permissions.

## 🔐 Authentification

L'authentification se fait via JWT. Les tokens sont stockés en localStorage.

## 🎨 Styling

Le projet utilise CSS Modules et des variables CSS personnalisées pour le theming.

## 🧪 Tests

Exécuter les tests :
```bash
npm test
```

Avec couverture :
```bash
npm test -- --coverage
```

## 📦 Build de Production

```bash
npm run build
```

Créera un dossier `build/` optimisé pour la production.

## 🚀 Déploiement

Voir le guide de déploiement pour plus d'informations sur le déploiement en production.

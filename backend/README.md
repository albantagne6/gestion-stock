# Backend - Django

## 📋 Description

Backend du système de gestion de stock développé avec Django et Django REST Framework.

## 🚀 Installation

### Prérequis
- Python 3.9+
- pip
- PostgreSQL (optionnel, SQLite par défaut)

### Étapes

1. **Créer un environnement virtuel**
```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\\Scripts\\activate
```

2. **Installer les dépendances**
```bash
pip install -r requirements.txt
```

3. **Configurer les variables d'environnement**
```bash
cp .env.example .env
# Éditez .env avec vos paramètres
```

4. **Appliquer les migrations**
```bash
python manage.py migrate
```

5. **Créer un superutilisateur**
```bash
python manage.py createsuperuser
```

6. **Lancer le serveur de développement**
```bash
python manage.py runserver
```

Le serveur sera accessible à `http://localhost:8000`

## 📁 Structure des Apps

### products
Gestion des produits et articles du stock
- Modèles : Product, Category
- APIs : CRUD operations

### inventory
Suivi des niveaux de stock
- Modèles : InventoryLevel, StockMovement
- APIs : Consultation et mise à jour des stocks

### orders
Gestion des commandes
- Modèles : Order, OrderItem
- APIs : Création, suivi et gestion des commandes

### reports
Rapports et statistiques
- APIs : Rapports sur les stocks, les commandes, les statistiques

### users
Gestion des utilisateurs et permissions
- Modèles : User (extension de Django User)
- APIs : Authentification, profil utilisateur

## 🔐 Authentification

Le système utilise JWT (JSON Web Tokens) pour l'authentification.

### Endpoints d'authentification
- `POST /api/auth/login/` - Connexion
- `POST /api/auth/register/` - Inscription
- `POST /api/auth/refresh/` - Rafraîchir le token
- `POST /api/auth/logout/` - Déconnexion

## 📚 Documentation de l'API

Voir [DOCS.md](./DOCS.md) pour la documentation complète de l'API.

## 🧪 Tests

Exécuter les tests :
```bash
python manage.py test
```

Avec couverture :
```bash
coverage run --source='.' manage.py test
coverage report
```

## 🔧 Configuration

Voir `config/settings.py` pour les paramètres de configuration.

## 📝 Fichiers importants

- `manage.py` - Utilitaire de gestion Django
- `requirements.txt` - Dépendances Python
- `config/settings.py` - Configuration Django
- `config/urls.py` - Routing principal

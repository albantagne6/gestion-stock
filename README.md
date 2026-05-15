# Gestion de Stock

## 📋 Description

Système complet de gestion de stock développé avec **Django** (backend) et **React** (frontend).

### Fonctionnalités principales
- ✅ Suivi des stocks en temps réel
- ✅ Gestion des commandes
- ✅ Rapports et statistiques détaillés
- ✅ Système d'authentification et permissions
- ✅ Gestion des produits/articles

## 🛠️ Stack Technologique

### Backend
- **Django 4.2+** - Framework web Python
- **Django REST Framework** - APIs REST
- **PostgreSQL** - Base de données
- **Python 3.9+**

### Frontend
- **React 18+** - Librairie UI
- **React Router** - Navigation
- **Axios** - HTTP client
- **Node.js 16+**

## 📁 Structure du Projet

```
gestion-stock/
├── backend/                    # Django backend
│   ├── manage.py
│   ├── requirements.txt
│   ├── config/                 # Configuration Django
│   ├── apps/
│   │   ├── products/           # Gestion des produits
│   │   ├── inventory/          # Suivi des stocks
│   │   ├── orders/             # Gestion des commandes
│   │   ├── reports/            # Rapports et statistiques
│   │   └── users/              # Utilisateurs et permissions
│   └── tests/
├── frontend/                   # React frontend
│   ├── package.json
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── App.jsx
│   └── .env.example
├── .github/
│   └── ISSUE_TEMPLATE/         # Templates d'issues
├── .gitignore
└── docker-compose.yml          # Configuration Docker (optionnel)
```

## 🚀 Installation

### Backend (Django)

```bash
cd backend
python -m venv venv
source venv/bin/activate  # Windows: venv\\Scripts\\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

### Frontend (React)

```bash
cd frontend
npm install
npm start
```

Le frontend sera accessible à `http://localhost:3000`
Le backend sera accessible à `http://localhost:8000`

## 📚 Documentation

- [Backend Setup](./backend/README.md)
- [Frontend Setup](./frontend/README.md)
- [API Documentation](./backend/DOCS.md)

## 🔐 Authentification

Le système utilise l'authentification JWT (JSON Web Tokens) pour sécuriser les APIs.

## 👥 Contributeurs

Vous pouvez contribuer en :
1. Forking le projet
2. Créant une branche (`git checkout -b feature/AmazingFeature`)
3. Committing vos changements (`git commit -m 'Add some AmazingFeature'`)
4. Pushant sur la branche (`git push origin feature/AmazingFeature`)
5. Ouvrant une Pull Request

## 📝 License

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

## 📧 Contact

Pour toute question ou suggestion, veuillez créer une issue sur le dépôt.

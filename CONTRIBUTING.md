# Guide de Contribution

Merci de votre intérêt pour la contribution à ce projet ! 🎉

## 📋 Table des matières

1. [Code of Conduct](#code-of-conduct)
2. [Comment Contribuer](#comment-contribuer)
3. [Processus de Pull Request](#processus-de-pull-request)
4. [Conventions de Code](#conventions-de-code)
5. [Signaler un Bug](#signaler-un-bug)
6. [Suggérer une Amélioration](#suggérer-une-amélioration)

## Code of Conduct

Ce projet adhère à un code de conduite dans le but de favoriser un environnement accueillant et inclusif.

### Notre Engagement

Nous nous engageons à faire de la participation à ce projet une expérience sans harcèlement pour tous, indépendamment de l'âge, de la taille du corps, du handicap visible ou invisible, de l'origine ethnique, des caractéristiques sexuelles, de l'identité et de l'expression de genre, du niveau d'expérience, de l'éducation, du statut socio-économique, de la nationalité, de l'apparence personnelle, de la race, de la religion ou de l'identité et orientation sexuelles.

## Comment Contribuer

### Fork et Clone

1. Fork le projet sur GitHub
2. Clonez votre fork : `git clone https://github.com/votre-username/gestion-stock.git`
3. Ajoutez le repository upstream : `git remote add upstream https://github.com/albantagne6/gestion-stock.git`

### Créer une Branche

```bash
git checkout -b feature/votre-feature
# ou
git checkout -b bugfix/votre-bugfix
```

Utilisez les préfixes suivants :
- `feature/` pour une nouvelle fonctionnalité
- `bugfix/` pour corriger un bug
- `docs/` pour la documentation
- `test/` pour les tests

### Faire vos Changements

1. Faites vos modifications
2. Testez votre code
3. Committez avec des messages clairs : `git commit -m 'Add: Description claire du changement'`

### Processus de Pull Request

1. Poussez votre branche : `git push origin feature/votre-feature`
2. Ouvrez une Pull Request sur GitHub
3. Remplissez le template de PR
4. Attendez la review

## Conventions de Code

### Python/Django

- Suivez PEP 8
- Utilisez black pour le formatage : `black .`
- Utilisez flake8 pour la qualité : `flake8`
- Nommez les variables de manière descriptive
- Ajoutez des docstrings aux fonctions et classes

### JavaScript/React

- Utilisez ES6+
- Nommez les composants avec PascalCase
- Nommez les variables et fonctions avec camelCase
- Utilisez des commentaires utiles
- Formatez le code avec Prettier (si configuré)

## Signaler un Bug

Utilisez le template [Bug Report](.github/ISSUE_TEMPLATE/bug_report.md)

Inclure :
- Une description claire du bug
- Les étapes pour reproduire
- Le comportement attendu
- Des captures d'écran si possible
- Votre environnement (OS, navigateur, versions)

## Suggérer une Amélioration

Utilisez le template [Feature Request](.github/ISSUE_TEMPLATE/feature_request.md)

Incluir :
- Une description claire de la fonctionnalité
- Le problème qu'elle résout
- Comment vous l'implémenteriez
- Les alternatives envisagées

## 🎯 Bonnes Pratiques

1. **Un changement par PR** : Gardez vos PRs focalisées
2. **Tests** : Incluez des tests pour vos changements
3. **Documentation** : Mettez à jour la documentation
4. **Messages de commit clairs** : Décrivez ce que vous faites
5. **Rebasez** : Avant de merger, rebasez sur main

## 📚 Ressources

- [Django Documentation](https://docs.djangoproject.com/)
- [React Documentation](https://react.dev/)
- [Django REST Framework](https://www.django-rest-framework.org/)

Merci de votre contribution ! 🚀

# ANDRIEUX_AMBRE_TP

Ce projet s'inscrit dans le cadre d'un exercice visant à maîtriser l’utilisation de **Git** et des bonnes pratiques de collaboration sur GitHub. Il explore des concepts fondamentaux de développement collaboratif, l'intégration continue, et la gestion de projet.

---

## Objectifs du projet

L'objectif principal est de mettre en œuvre un workflow Git structuré, tout en respectant les standards de collaboration et d'automatisation. Plus précisément, ce projet inclut :
- La gestion des branches via **Git Flow**.
- La création et l’utilisation d’**issues**, de **templates** d’issues et de pull requests.
- La mise en place d’un linter et d’une intégration continue avec **GitHub Actions**.
- Le respect des bonnes pratiques de documentation (README, Contributing, Code of Conduct).

---

## Fonctionnalités

- **15 Issues et 15 branches** : Chaque tâche majeure est définie via une issue et résolue sur une branche dédiée.
- **Gestion des pull requests** : Inclut des templates pour uniformiser les contributions.
- **Hooks Git personnalisés** : Un linter est exécuté automatiquement avant chaque commit/push.
- **Intégration continue (CI)** : Vérification automatique du code via GitHub Actions.
- **Protection des branches** : Mise en place de règles pour garantir l'intégrité du code sur `main` et `develop`.

---

## Structure du dépôt

```
├── src/                # Code source principal
├── tests/              # Scripts de tests
├── .github/            # Templates pour issues, PR, workflows CI
├── hooks/              # Scripts Git hooks (linter, autres automatisations)
├── docs/               # Documentation du projet
└── .gitignore          # Fichiers et dossiers ignorés
```

---

## Prérequis techniques

- Git 2.x
- Node.js & npm (pour le linter et les hooks)
- IDE compatible Git (VS Code recommandé)
- Accès à deux dépôts Git remotes (GitHub et une alternative)

---

## Installation et configuration

1. **Cloner le dépôt** :
   ```bash
   git clone git@github.com:Ambreandrieux/ANDRIEUX_AMBRE_TP.git
   ```

2. **Installer les dépendances** :
   ```bash
   npm install
   ```

3. **Configurer les remotes** :
   Ajouter un deuxième remote :
   ```bash
   git remote add secondary <url_du_deuxième_remote>
   ```

4. **Configurer les hooks** :
   Copier les hooks dans le dossier `.git/hooks` :
   ```bash
   cp hooks/* .git/hooks/
   chmod +x .git/hooks/*
   ```

---

## Workflow Git

### Étapes de contribution

1. Créer une issue décrivant votre tâche.
2. Créer une branche dédiée à la tâche :
   ```bash
   git checkout -b feature/nom-de-la-feature
   ```
3. Développer et valider le code (respecter le linter).
4. Soumettre une pull request associée à l’issue.

---

## Intégration continue

- **GitHub Actions** :
  - Analyse du code et exécution du linter sur chaque pull request.
- **Hooks Git** :
  - Validation locale du code avant chaque push.

---

## Documentation supplémentaire

- [Guide de contribution](CONTRIBUTING.md)
- [Code de conduite](CODE_OF_CONDUCT.md)
- [Git Flow détaillé](docs/git-flow.md)

---

## Auteurs

Projet réalisé par :
- Ambre Andrieux
- (Ajoutez vos coéquipiers ici, si applicable)

Pour toute question ou suggestion, veuillez créer une issue sur le dépôt GitHub.

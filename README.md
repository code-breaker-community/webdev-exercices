# webdev-exercices

## Description

Bienvenue dans le dépôt **webdev-exercices** !  
Ici, vous pouvez **soumettre votre travail** en suivant les étapes ci-dessous. Ce dépôt centralise les exercices de l'équipe WebDev de la communauté Code Breaker.

---

## 1. Structure recommandée pour votre projet personnel

Organisez votre travail dans un dossier à votre nom, avec une structure claire, par exemple :

```
Michee/
├── element_graphique/
├── css/
├── html/
└── README_personnel.md  # Présentation ou notes personnelles
```

---

## 2. Démarrer un nouveau projet localement

Dans votre terminal, exécutez les commandes suivantes :

```bash
# Créer un fichier README.md avec un titre
echo "# webdev-exercices" > README.md

# Initialiser un dépôt Git local
git init

# Ajouter le fichier README.md à l’index Git
git add README.md

# Effectuer un premier commit
git commit -m "premier commit"

# Renommer la branche principale en 'main'
git branch -M main
```

---

## 3. Connecter un projet existant à GitHub

Si vous avez déjà un projet local, connectez-le au dépôt distant :

```bash
# Ajouter le dépôt distant
git remote add origin https://github.com/code-breaker-community/webdev-exercices.git

# Renommer la branche courante en 'main' (forcer si nécessaire)
git branch -M main

# Envoyer les commits locaux vers GitHub
git push -u origin main
```

---

## 4. Conseils pour une collaboration efficace

- Travaillez toujours dans votre dossier personnel ou sur une branche dédiée.
- Avant de commencer un exercice, créez une branche :
    ```bash
    git checkout -b votre-nom-exercice-01
    ```
- Envoyez votre travail via une Pull Request pour permettre la revue avant fusion.
- Ne modifiez pas les dossiers ou fichiers des autres membres.

Bonne collaboration à tous et bon courage pour vos exercices ! 🚀
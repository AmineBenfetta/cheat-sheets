# Commandes et astuces Git et GitHub

## Commandes Git principales

### Initialisation et configuration du dépôt

- `git init` : Initialiser un nouveau dépôt Git dans le répertoire courant.
  
- `git clone <url>` : Cloner un dépôt distant dans votre répertoire local.
  - Exemple : `git clone https://github.com/utilisateur/repository.git`.

- `git config --global user.name "Nom"` : Configurer votre nom d'utilisateur global.
  
- `git config --global user.email "email@example.com"` : Configurer votre email global.

- `git config --list` : Afficher la configuration actuelle de Git.

### Gestion des fichiers et des modifications

- `git status` : Afficher l'état des fichiers (modifiés, non suivis, etc.).

- `git add <fichier>` : Ajouter un fichier spécifique à l'index de staging.
  - Exemple : `git add fichier.txt`.

- `git add .` : Ajouter tous les fichiers modifiés et nouveaux fichiers au staging.

- `git commit -m "Message"` : Valider les modifications dans l'historique du dépôt avec un message.

- `git diff` : Afficher les différences entre les fichiers modifiés et l'index (non validées).

- `git diff --staged` : Afficher les différences des fichiers ajoutés au staging.

- `git reset` : Réinitialiser l'index de staging (annule `git add`).
  - Exemple : `git reset fichier.txt`.

- `git rm <fichier>` : Supprimer un fichier du dépôt Git.
  - Exemple : `git rm fichier.txt` pour supprimer un fichier du suivi.

### Gestion des branches

- `git branch` : Afficher la liste des branches locales.

- `git branch <nom>` : Créer une nouvelle branche.
  - Exemple : `git branch feature-x` pour créer une branche `feature-x`.

- `git checkout <nom>` : Basculer vers une autre branche.
  - Exemple : `git checkout feature-x`.

- `git checkout -b <nom>` : Créer et basculer sur une nouvelle branche en une seule commande.
  - Exemple : `git checkout -b feature-x`.

- `git merge <nom>` : Fusionner la branche spécifiée dans la branche actuelle.
  - Exemple : `git merge feature-x` pour fusionner la branche `feature-x` dans la branche courante.

- `git branch -d <nom>` : Supprimer une branche locale.
  - Exemple : `git branch -d feature-x` pour supprimer la branche `feature-x` après sa fusion.

### Suivi des branches distantes

- `git remote add origin <url>` : Ajouter une URL distante (par exemple, GitHub).
  - Exemple : `git remote add origin https://github.com/utilisateur/repository.git`.

- `git fetch` : Récupérer les modifications depuis le dépôt distant sans les fusionner.

- `git pull` : Récupérer les modifications depuis le dépôt distant et les fusionner dans la branche actuelle.

- `git push` : Pousser les commits locaux vers un dépôt distant.
  - Exemple : `git push origin master` pour pousser la branche `master` vers `origin`.

- `git push -u origin <branche>` : Pousser une nouvelle branche vers le dépôt distant et la lier à la branche locale.
  - Exemple : `git push -u origin feature-x`.

- `git push origin --delete <branche>` : Supprimer une branche distante.
  - Exemple : `git push origin --delete feature-x` pour supprimer la branche distante `feature-x`.

### Historique et révisions

- `git log` : Afficher l'historique des commits.

- `git log --oneline` : Afficher l'historique des commits en une seule ligne par commit.

- `git show <commit>` : Afficher les détails d'un commit spécifique.

- `git revert <commit>` : Créer un nouveau commit qui annule les changements d'un commit précédent.

- `git reset <commit>` : Réinitialiser la branche à un commit antérieur.
  - Exemple : `git reset --hard <commit>` pour réinitialiser la branche en écrasant les changements locaux.

- `git stash` : Mettre de côté les modifications non validées et nettoyer le répertoire de travail.

- `git stash pop` : Appliquer et supprimer les modifications stockées avec `git stash`.

## Astuces pour travailler avec GitHub

### Créer un dépôt GitHub

- Allez sur GitHub, créez un nouveau dépôt (public ou privé).
- Après avoir créé le dépôt, vous recevrez l'URL pour le cloner dans votre répertoire local.

### Travailler avec les Pull Requests (PR)

- **Créer une Pull Request** : Une fois votre branche prête à être fusionnée, allez sur GitHub, dans le dépôt, puis créez une Pull Request (PR) pour proposer la fusion.
- **Fusionner une PR** : Si la PR est approuvée, vous pouvez la fusionner dans la branche principale (souvent `master` ou `main`).

### Collaborer avec plusieurs personnes

- **Fork** : Si vous souhaitez contribuer à un projet, vous pouvez "forker" un dépôt GitHub. Cela crée une copie du dépôt sous votre compte, vous permettant d'y apporter des modifications avant de proposer des changements via une Pull Request.
- **Issues** : Utilisez les "issues" (problèmes) sur GitHub pour signaler des bugs ou discuter de nouvelles fonctionnalités avec les contributeurs.

### Gérer les secrets et les tokens d'authentification

- **Authentification avec SSH** : Configurez une clé SSH pour pousser et cloner des dépôts GitHub de manière sécurisée sans mot de passe.  
  - Exemple : `ssh-keygen -t rsa -b 4096 -C "email@example.com"` pour générer une clé SSH.

- **GitHub Token** : Utilisez un token d'accès personnel si vous préférez ne pas utiliser votre mot de passe GitHub pour l'authentification.

### Astuces diverses

- **.gitignore** : Créez un fichier `.gitignore` pour ignorer des fichiers/dossiers spécifiques du suivi Git. Exemple de contenu :

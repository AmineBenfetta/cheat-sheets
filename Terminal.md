# Raccourcis clavier importants du terminal Linux en Zsh

## Manipulation du curseur
- `Ctrl + A` : Aller au début de la ligne.
- `Ctrl + E` : Aller à la fin de la ligne.
- `Ctrl + U` : Supprimer tout avant le curseur.
- `Ctrl + K` : Supprimer tout après le curseur.
- `Ctrl + W` : Supprimer le mot précédent.
- `Ctrl + Y` : Coller le texte supprimé précédemment (buffer).
- `Ctrl + L` : Effacer l'écran (comme `clear`).
- `Alt + B` : Aller d'un mot en arrière.
- `Alt + F` : Aller d'un mot en avant.
- `Ctrl + T` : Échanger les caractères avant et après le curseur.

## Historique et navigation des commandes
- `Ctrl + R` : Recherche dans l'historique (reverse search).
- `Ctrl + P` : Commande précédente.
- `Ctrl + N` : Commande suivante.
- `Alt + .` : Insérer le dernier argument de la commande précédente.
- `Ctrl + G` : Quitter la recherche dans l'historique.
- `!!` : Réexécuter la dernière commande.
- `!<numéro>` : Exécuter la commande avec le numéro d'historique spécifié.

## Gestion des processus
- `Ctrl + C` : Interrompre un processus en cours.
- `Ctrl + Z` : Suspendre un processus en cours.
- `fg` : Reprendre le processus suspendu en avant-plan.
- `bg` : Reprendre le processus suspendu en arrière-plan.

## Autocomplétion
- `Tab` : Complétion automatique des commandes et fichiers.
- `Ctrl + D` : Quitter le terminal (ferme la session en cours).

## Autres raccourcis utiles
- `Ctrl + D` : Quitter le terminal (si rien n'est dans le buffer).
- `Ctrl + S` : Suspendre l'affichage dans le terminal (suspend l'écran de sortie).
- `Ctrl + Q` : Reprendre l'affichage du terminal après un `Ctrl + S`.
- `Alt + C` : Capitaliser la lettre sous le curseur.
- `Alt + U` : Mettre en majuscule tous les caractères avant le curseur.
- `Alt + L` : Mettre en minuscule tous les caractères avant le curseur.

## Raccourcis Zsh spécifiques
- `Ctrl + X` puis `Ctrl + E` : Ouvrir l'éditeur pour modifier la commande en cours.
- `Alt + ~` : Aller dans votre répertoire personnel.
- `Ctrl + D` : Quitter Zsh (si aucune commande n'est en cours d'exécution).

# Commandes principales et importantes

## Commandes de gestion des fichiers et répertoires

- `ls` : Afficher la liste des fichiers et répertoires dans le répertoire courant.
  - Exemple : `ls -l` pour une liste détaillée.
  
- `cd` : Changer de répertoire.
  - Exemple : `cd /chemin/vers/répertoire`.

- `pwd` : Afficher le chemin complet du répertoire courant.

- `cp` : Copier des fichiers ou répertoires.
  - Exemple : `cp fichier1.txt fichier2.txt` pour copier `fichier1.txt` vers `fichier2.txt`.

- `mv` : Déplacer ou renommer des fichiers ou répertoires.
  - Exemple : `mv fichier1.txt /nouveau/répertoire/`.

- `rm` : Supprimer des fichiers ou répertoires.
  - Exemple : `rm fichier.txt` pour supprimer un fichier, ou `rm -r répertoire` pour supprimer un répertoire et son contenu.

- `touch` : Créer un fichier vide.
  - Exemple : `touch fichier.txt` pour créer un fichier vide nommé `fichier.txt`.

- `mkdir` : Créer un répertoire.
  - Exemple : `mkdir mon_répertoire`.

- `rmdir` : Supprimer un répertoire vide.
  
## Commandes de gestion des processus

- `ps` : Afficher les processus en cours.
  - Exemple : `ps aux` pour une liste complète des processus.

- `top` : Afficher en temps réel l'utilisation des ressources système (CPU, mémoire).

- `kill` : Terminer un processus par son identifiant (PID).
  - Exemple : `kill 1234` pour tuer le processus avec l'ID 1234.

- `jobs` : Afficher les processus en arrière-plan.

- `bg` : Relancer un processus suspendu en arrière-plan.

- `fg` : Ramener un processus en arrière-plan au premier plan.

## Commandes d'archive et de compression

- `tar` : Créer ou extraire des archives.
  - Exemple : `tar -czvf archive.tar.gz /chemin/du/répertoire` pour créer une archive compressée.
  - Exemple : `tar -xzvf archive.tar.gz` pour extraire une archive.

- `zip` / `unzip` : Compresser et décompresser des fichiers ZIP.
  - Exemple : `zip archive.zip fichier1.txt fichier2.txt` pour créer une archive ZIP.
  - Exemple : `unzip archive.zip` pour extraire une archive ZIP.

## Commandes d'administration système

- `sudo` : Exécuter une commande avec les privilèges administratifs.
  - Exemple : `sudo apt update` pour mettre à jour la liste des paquets sur une distribution basée sur Debian.

- `chmod` : Modifier les permissions d'un fichier ou répertoire.
  - Exemple : `chmod 755 fichier.sh` pour définir les permissions d'exécution sur un fichier.

- `chown` : Changer le propriétaire et/ou le groupe d'un fichier ou répertoire.
  - Exemple : `sudo chown utilisateur:utilisateur fichier.txt` pour changer le propriétaire d'un fichier.

- `df` : Afficher l'espace disque disponible.
  - Exemple : `df -h` pour afficher l'espace disque en format lisible (Go, Mo).

- `du` : Afficher l'espace utilisé par les fichiers et répertoires.
  - Exemple : `du -sh /chemin/vers/répertoire` pour afficher la taille totale d'un répertoire.

## Commandes réseau

- `ping` : Tester la connectivité réseau.
  - Exemple : `ping google.com` pour vérifier la connexion à Google.

- `ifconfig` / `ip` : Afficher ou configurer les interfaces réseau.
  - Exemple : `ifconfig` ou `ip a` pour afficher les interfaces réseau.

- `netstat` : Afficher les connexions réseau et les informations liées.
  - Exemple : `netstat -tuln` pour afficher les ports utilisés par les services.

## Commandes pour la gestion de l'historique

- `history` : Afficher l'historique des commandes précédentes.

- `!<numéro>` : Réexécuter une commande en fonction de son numéro dans l'historique.
  - Exemple : `!2` pour réexécuter la deuxième commande dans l'historique.

- `clear` : Effacer l'écran du terminal.

---

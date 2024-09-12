# Commandes de base Linux


## 1. Gestion des fichiers et répertoires

- **`ls`** : Lister les fichiers dans un répertoire.
- **`cd <répertoire>`** : Changer de répertoire.
- **`pwd`** : Afficher le chemin du répertoire courant.
- **`mkdir <nom_du_répertoire>`** : Créer un nouveau répertoire.
- **`rmdir <nom_du_répertoire>`** : Supprimer un répertoire vide.
- **`touch <nom_du_fichier>`** : Créer un nouveau fichier vide.
- **`cp <source> <destination>`** : Copier un fichier ou un répertoire.
- **`mv <source> <destination>`** : Déplacer ou renommer un fichier ou répertoire.
- **`rm <nom_du_fichier>`** : Supprimer un fichier.
- **`rm -r <nom_du_répertoire>`** : Supprimer un répertoire et son contenu.



## 2. Visualisation et manipulation des fichiers

- **`cat <nom_du_fichier>`** : Afficher le contenu d'un fichier.
- **`less <nom_du_fichier>`** : Lire un fichier page par page.
- **`head <nom_du_fichier>`** : Afficher les premières lignes d'un fichier.
- **`tail <nom_du_fichier>`** : Afficher les dernières lignes d'un fichier.
- **`grep '<mot>' <nom_du_fichier>`** : Chercher un mot ou une expression dans un fichier.


## 3. Gestion des utilisateurs et permissions

- **`whoami`** : Afficher l’utilisateur actuel.
- **`sudo <commande>`** : Exécuter une commande avec les privilèges de superutilisateur.
- **`chmod <permissions> <fichier>`** : Modifier les permissions d’un fichier ou d’un répertoire.
- **`chown <utilisateur>:<groupe> <fichier>`** : Changer le propriétaire et le groupe d’un fichier ou d’un répertoire.



## 4. Gestion des processus

- **`ps`** : Afficher les processus en cours.
- **`top`** : Afficher les processus en temps réel.
- **`kill <PID>`** : Terminer un processus en utilisant son PID (Process ID).
- **`killall <nom_du_processus>`** : Terminer tous les processus avec un nom spécifique.



## 5. Gestion du réseau

- **`ifconfig`** : Afficher ou configurer les interfaces réseau.
- **`ping <adresse>`** : Tester la connectivité avec une machine distante.
- **`netstat`** : Afficher les connexions réseau, les tables de routage et les statistiques des interfaces.
- **`ssh <utilisateur>@<adresse IP>`** : Se connecter à une machine distante via SSH.
- **`scp <fichier_source> <utilisateur>@<adresse IP>:<chemin_destination>`** : Copier un fichier vers une machine distante.



## 6. Gestion des paquets 
- **`apt update`** : Mettre à jour la liste des paquets.
- **`apt upgrade`** : Mettre à jour tous les paquets installés.
- **`apt install <nom_du_paquet>`** : Installer un nouveau paquet.
- **`apt remove <nom_du_paquet>`** : Supprimer un paquet installé.

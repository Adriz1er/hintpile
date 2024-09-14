
programme qui tourne, et toujours exécuté par un processus père ; et représenté par un numéro `pid` ^98babb

Pour executer un processus en avant plan il faut taper `son nom`, et optionnellement avec un paramètre `celui-ci` ; lancer un processus en arrière plan il faut rajouter `&`. `FG` fait revenir en avant plan le dernier processus en arrière plan, `BG` passe le processus en avant plan en arrière plan
Pour fermer un processus en avant plan : `[ctrl + C]` ou `kill -9 [pid]` (`-9` indique à son processus père qu'un de ses processus fils ne tourne plus pour éviter des processus zombies)
Pour stopper un processus en (arrière plan) `[ctrl + Z]`
Pour avoir la liste des processus qui tournent, on utilise la commande `ps`
- `UID`  identifiant de l'utilisateur ayant lancé le processus
- `PID` identifiant du processus
- `PPID` identifiant du processus père
- `PRI` priorité
- `STAT` 

Il peut y avoir des processus *zombies* qui tournent mais ne font rien

un processus bash est un processus qui fait tourner le terminal et contient les commandes de linux. Le [[fichiers et répertoires|répertoire]] `~/.bashrc` est le dossier de configuration.
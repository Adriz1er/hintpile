- Mise en ligne de modifications  : Dans le menu Branche  ![[les dossiers onedrive/OneDrive/second_cerveau/mes notes/pris dans la boite de réception/Pasted image 20240605172543.png|75]] , mettre un nom pour la modification apportée ![[les dossiers onedrive/OneDrive/second_cerveau/mes notes/pris dans la boite de réception/Pasted image 20240605173605.png|300]]
- Récupération de modifications : Dans le menu Branche  ![[les dossiers onedrive/OneDrive/second_cerveau/mes notes/pris dans la boite de réception/Pasted image 20240605172543.png|75]] , dans le sous-menu exécution de pull : ![[les dossiers onedrive/OneDrive/second_cerveau/mes notes/pris dans la boite de réception/Pasted image 20240605173338.png|300]]
## 2. Etiqueter pour ajouter des numéros de versions
- ouvrir deux git bash et mettre une fenêtre par moitié d'écran
- sur l'un : exécuter *git log* et trouver le commit qui va être associé à un numéro de version, copier (en faisant un clique droit pour ouvrir le menu contextuel) le numéro SHA qui est toujours au niveau de ce qui est sélectionné : ![[les dossiers onedrive/OneDrive/second_cerveau/mes notes/pris dans la boite de réception/Pasted image 20240605174252.png]]
- sur l'autre : exécuter *git tag v'n° version' 'SHA'*
- A savoir la numérotation de version qu'on a utilisé : 
	- le numéro de gauche est pour des changements très majeurs
	- le numéro du milieu est pour des fonctionnalités
	- le numéro de droite est pour des correctifs ou des changements mineurs
	Si un numéro plus à gauche qu'un autre ce dernier se change en 0 à moins de changement(s) à propos de ce dernier
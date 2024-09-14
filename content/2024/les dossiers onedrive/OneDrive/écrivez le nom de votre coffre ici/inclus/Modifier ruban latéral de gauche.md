---
auteur: Samuel
aspiration: 
tag:
  - concept
cards-deck:
---

Le ruban latéral de gauche se modifie grace à un extrait CSS (sans le CSS, avec les nouvelles commandes et maj tout bouge). Pour accéder à cet extrait CSS il faut aller dans Paramètre => Apparence => Extrait CSS puis cliquer sur l'icone dossier et ouvrir "Ruban lateral gauche.css".
Chaque paragraphe dans ce code correspond à un groupe de commande .

Pour choisir l'emplacement d'une commande il faut le faire avec cette ligne de code :  `div[aria-label="Open graph view"] { order: 1; }`
Ce qui se trouve entre guillemets doit être le nom de la commande. Le nombre à l'intérieur des deux accolades est le rang que va occuper cette commande. ^c6cc1b

Pour créer un diviseur il faut marquer cette ligne de code : `.ribbon-divider { order: 9 !important; }`
Vous devez changer que l' "`order`", c'est le rang que va occuper le diviseur. (Remarque : vous n'êtes pas obligé de mettre le diviseur tout de suite après la dernière commande. Si vous faites cela, il sera plus dur d'ajouter une commande)
Attention pour chaque séparateur ajouté, il faudra utiliser un sélecteur adjacent en plus (c'est le signe +).
Premier séparateur : `.ribbon-divider`
Deuxième : `.ribbon-divider + .ribbon-divider`
Quatrième : `.ribbon-divider + .ribbon-divider + .ribbon-divider + .ribbon-divider`

Enfin, vous devez créer le même nombre de diviseurs qu'il y a dans l'extrait CSS dans les paramètres de "Ribbon Divider". Pour en créer un, il suffit de cliquer sur le bouton "New divider".
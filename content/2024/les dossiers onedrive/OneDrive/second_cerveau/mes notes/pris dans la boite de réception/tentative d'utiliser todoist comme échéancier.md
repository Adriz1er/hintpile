---
aspiration: "[[assumer efficacement ses engagements internes avec GTD]]"
---
Pour cela il faut installer le plugin communautaire *ultimate todoist sync*, puis le configurer : 
- copier coller votre api de todoist que vous pourrez trouver [ici](https://todoist.com/app/settings/integrations/developer), et appuyer sur le bouton qui a l'apparence d'un avion en papier
- *check database* pour que le plugin détecte toutes vos cases à cocher écrites de cette manière là : 
`- [ ] #todoist 📅` 
- **==désactiver==** la synchronisation pour tous le coffre : *full vault sync*


Il permet de synchroniser toutes vos *actions suivantes* ^[[[clarifier ses intrants pour passer à la réalité#les projets sur obsidian]]], mais là où todoist ^[[[choisir ses actions avec GTD grâce à obsidian#^ad201d]]] se révèle vraiment utile c'est qu'il peut nous permettre de choisir quelque chose à faire vraiment rapidement ^[[[choisir ses actions avec GTD grâce à obsidian#^1ebcab]]]. 

Malheureusement les récurrences ne marchent pas avec celle du plugin task, on va donc les écrire comme ça
`- [ ] #todoist [link] %%todoist id%% tout les jours/mois/... semaines📅truc en anglais` 
Et ouvrir le lien vers la tâche dans todoist et **rajouter un espace** à la fin de la tâche (soit après la "récurrence" en français), pour que todoist la détecte.
### connecter todoist à agenda pour les notifications
Pour ça vous aurez obligatoirement besoin d'aller à cette adresse [Todoist](https://todoist.com/app/settings/integrations/installed) sur votre ordinateur, puis de connecter à todoist à un *nouveau* calendrier, je recommande les paramètres suivants : 
Une fois cela fait un nouveau calendrier va apparaitre sur [Google Agenda](https://calendar.google.com/), allez dans les paramètres, puis mettez le paramètre de notification , et aussi pour les évènements "toute la journée" : 
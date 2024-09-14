
![[boîte de réception qui commence à partir du bas]]





<% tp.file.cursor(1) %>
___
# revoir les projets en cours
 ```button
name Ouvrir la liste des projets
type link
action obsidian://advanced-uri?vault=second_cerveau&filepath=projets.md
```
^button-2hq2
___
# revoir l'agenda et les éléments reportés

```button
name Voir les évènemets planifiés
type command
action Google Calendar: Open gCal Schedule View
```
^button-4ms1
```button
name Voir les évènements en fonction des semaines
type command
action Google Calendar: Open gCal week view
```
^button-0fiy
## tout les éléments reportés
```tasks
tag does not include #noté 
sort by urgency reverse
sort by filename reverse
sort by created 
sort by filename reverse
status.name includes reporté
hide created date
```



<% tp.file.cursor(2) %>
___
# en attente
```tasks
tag does not include #noté 
sort by urgency 
sort by created reverse
sort by filename 
status.name includes en attente
hide created date
```
___
```button
name Ouvre les signets pour revoir les horizons
type command
action Signet: Afficher les signets
```
^button-uu4i
___
## liste des vérifications
```tasks
tag does not include #noté 
sort by urgency 
sort by created reverse
sort by filename 
status.name includes vérification
hide created date
```

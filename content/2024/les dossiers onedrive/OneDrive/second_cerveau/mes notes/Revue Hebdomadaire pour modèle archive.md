

!écrivez le nom de votre coffre ici (version sans google agenda)/pour boîte de réception/boîte de réception





<% tp.file.cursor(1) %>
___
# revoir les projets en cours
```button
name Ouvrir la liste des projets
type link
action obsidian://advanced-uri?vault=%C3%A9crivez%20le%20nom%20de%20votre%20coffre%20ici&filepath=inclus%252Fmes%2520projets.md
```
^button-dk5x
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
sort by created 
sort by filename reverse
status.name includes reporté
hide created date
```
___
# en attente
```tasks
tag does not include #noté 
sort by urgency reverse
sort by created 
sort by filename reverse
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
```tasks
tag does not include #noté 
sort by urgency reverse
sort by created 
sort by filename reverse
status.name includes vérification
hide created date
```

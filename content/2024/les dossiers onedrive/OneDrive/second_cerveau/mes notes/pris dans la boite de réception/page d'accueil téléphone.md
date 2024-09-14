
```button
name Créer un nouveau projet
type command
action Créer une nouvelle note
```
^button-v07j8
```button
name Saisir un intrant
type command
action QuickAdd: saisir un intrant
```
^button-7tc5
```button
name saisir un concept
type command
action QuickAdd: saisir un concept
```
^button-8bou
```button
name saisir une habitude
type command
action QuickAdd: saisir une habitude
```
^button-4s8s
## boîte de réception
```tasks
tag does not include #noté 
sort by urgency 
sort by created reverse
sort by filename 
sort by heading
status.name includes idée
hide created date
(starts before today) OR (starts on today) OR (no start date)
path does not include notes quotidiennes
hide edit button
```
___
## éléments récurrents passés (non finis)
```tasks
(is recurring) AND (starts before today) AND (has start date)
tag does not include #noté 
status.type is not DONE
status.type is not CANCELLED
sort by start
sort by filename 
sort by heading
sort by urgency
```
## notes récurrentes reportées avant ce jour
```dataview
table date(due_at) as revoir_le , repeat as se_répète_tout_les
from "" and -"Modèles (inclus)/modèle templater pour boîte de réception" and -"Modèles (inclus)/modèle pour module principal"
where due_at != null AND date(due_at) <= date(today)
sort due_at desc
```
```button
name Revoir les projets récurrents
type command
action Repeat: Review due notes
```
^button-y45u
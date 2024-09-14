```button
name saisir un intrant
type command
action QuickAdd: saisir un intrant
color default
```

```button
name saisir un concept
type command
action QuickAdd: saisir un concept
```
^button-8bou
```button
name Afficher un projet aléatoirement
type command
action Advanced Random Note: projet
color blue
```
^button-jm6f
```dataviewjs
dv.taskList(dv.pages('"" and -"les dossiers onedrive/OneDrive/écrivez le nom de votre coffre ici" and -#noté').file.tasks
.where(t => ['I'].includes(t.status)) 
.sort(() => Math.random() - 0.5)
.limit(1));
``` 
```button
name refresh
type line(21) text
action ```dataviewjs
replace [21,21]
```
^button-3ueq
```dataviewjs
dv.taskList(dv.pages('"" and -"les dossiers onedrive/OneDrive/écrivez le nom de votre coffre ici" and -#noté').file.tasks
.limit(1));
``` 
```button
name refresh
type line(34) text
action ```dataviewjs
replace [34,34]
```
^button-bf73
> [!tip] Google task refresh token
> 1//03CuEtPMMlVmPCgYIARAAGAMSNwF-L9Ir5CsKthjgBEPHBbHjzm6nyqkOt_a1NcKHm_ujj9FJIPPDbx2aaild0EgQEqt5vGaFXaY
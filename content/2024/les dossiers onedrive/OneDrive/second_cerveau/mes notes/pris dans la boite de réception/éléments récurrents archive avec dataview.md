⚠️ ne pas cocher les [[éléments récurrents archive avec dataview]] dans cette note car la récurrence ne fonctionne pas
```dataview
task
from !"les dossiers onedrive/OneDrive/écrivez le nom de votre coffre ici"
where !contains(tag, "noté")
where repeat != null
where start or contains(file.path, "notes quotidiennes")
sort choice(start != null, start, date(file.name))
sort due desc
sort priority desc
sort scheduled desc
where !completed
WHERE status != "-"
WHERE status != "X"
```
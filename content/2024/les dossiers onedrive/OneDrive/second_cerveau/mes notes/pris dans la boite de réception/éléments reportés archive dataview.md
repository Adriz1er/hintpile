---
date: 2024-08-27
---

```dataview
task
from !"les dossiers onedrive/OneDrive/écrivez le nom de votre coffre ici"
where !contains(tag, "noté")
where repeat = null
where start or contains(file.path, "notes quotidiennes")
sort choice(start != null, start, date(file.name))
sort due desc
sort priority desc
sort scheduled desc
where !completed
WHERE status != "-"
WHERE status != "X"
```

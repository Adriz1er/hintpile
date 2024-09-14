---
aspiration: 
tag:
  - concept
cards-deck:
---

```dataview
task
where repeat = null
where !contains(tag, "inclus")
where !contains(tag, "noté")
where !contains(file.path, "Modèles (inclus)/Modèle pour tache dans note quotidienne")
where start or contains(file.path, "notes quotidiennes")
sort choice(start != null, start, date(file.name))
sort due desc
sort priority desc
sort scheduled desc
where !completed
WHERE status != "-"
WHERE status != "X"
```
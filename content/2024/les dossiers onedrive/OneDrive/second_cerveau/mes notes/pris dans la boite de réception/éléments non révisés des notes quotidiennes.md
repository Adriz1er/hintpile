
```dataview
task
from "notes quotidiennes"
where !contains(tag, "noté")
where start = null
where !completed
WHERE status != "-"
WHERE status != "X"
group by file.name
sort due
sort priority
sort scheduled
```
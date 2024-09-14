---
tag:
---

```dataview
TABLE
WHERE
  (due - date(now) <= dur(30 days) and due - date(now) >= dur(1 days)) OR
  any(map(filter(file.tasks, (t) => t.due), (k) => k.due - date(now) <= dur(30 days) AND k.due - date(now) >= dur(1 days)))
```

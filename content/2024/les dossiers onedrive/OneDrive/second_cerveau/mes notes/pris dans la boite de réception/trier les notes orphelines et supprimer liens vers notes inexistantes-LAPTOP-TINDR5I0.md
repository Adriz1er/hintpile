---
date de création: 2023-07-04 16:50
date de modification: 2023-07-04 16:50
tags: []
---
- [-] Find orphaned files and broken links
- [ ] passer en revue [[#liste des notes inexistantes]]
## liste des notes inexistantes
```dataview
TABLE WITHOUT ID key AS "unresolved link", rows.file.link AS "referencing file"
FROM ""
FLATTEN file.outlinks as outlinks
WHERE !(outlinks.file) AND !(contains(meta(outlinks).path, "/"))
GROUP BY outlinks
```
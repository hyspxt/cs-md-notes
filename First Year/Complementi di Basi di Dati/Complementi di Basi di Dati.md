---
tags: MOCs
---

```dataviewjs
const folder = dv.current().file.folder;
dv.list(
  dv.pages(`"${folder}"`)
    .where(p => p.file.name !== dv.current().file.name) // esclude se stesso
    .sort(p => p.file.name, 'asc')
    .map(p => p.file.link) // wikilink veri
);
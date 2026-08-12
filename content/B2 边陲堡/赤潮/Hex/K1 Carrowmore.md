---
date: 2025-03-04
tags:
  - campaign/redtide/hex
---

# K1 Carrowmore

深碳观测站

```dataview
Table without id file.link AS "§", item.text as "交互"
From !"_template" and #campaign/redtide/session 
Flatten file.lists as item
where contains(item.text, this.file.name)
sort file.name DESC
```
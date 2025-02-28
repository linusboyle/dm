---
date: <% tp.date.now("YYYY-MM-DD") %>
tags:
  - campaign/redtide/faction
---

<%*
let title = tp.file.title
if (title.startsWith("Untitled") ) {
	title = await tp.system.prompt("File name: ")
} 
await tp.file.move("/worldbuilding/赤潮/派系/" + title)
_%>

# <% title %>

<% tp.file.cursor(0) %>

```dataview
Table without id file.link AS "§", item.text as "交互"
From !"_template" and #campaign/redtide/session 
Flatten file.lists as item
where contains(item.text, this.file.name)
sort file.name DESC
```
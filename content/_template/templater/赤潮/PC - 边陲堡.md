---
date: <% tp.file.creation_date("YYYY-MM-DD")%>
description: 
tags: 
- campaign/redtide/PC
status:
---

<%*
let title = tp.file.title
if (title.startsWith("Untitled") ) {
	title = await tp.system.prompt("File name: ")
} 
await tp.file.move("/B2 边陲堡/PC/" + title)
_%>

# <% title %>

<% tp.file.cursor(0) %>

```dataview
Table without id file.link AS "§", item.text as "交互"
From !"_template" and #campaign/redtide/session 
Flatten file.lists as item
where contains(item.text, this.file.name)
sort file.name DESC
````
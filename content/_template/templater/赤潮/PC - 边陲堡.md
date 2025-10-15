---
{"publish":true,"created":"<% tp.file.creation_date(\"YYYY-MM-DD\")%>","tags":["campaign/redtide/PC"],"cssclasses":""}
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

| § | 交互 |
| - | -- |

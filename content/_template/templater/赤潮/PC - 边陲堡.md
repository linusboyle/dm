---
{"publish":true,"tags":["campaign/redtide/PC"],"cssclasses":""}
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

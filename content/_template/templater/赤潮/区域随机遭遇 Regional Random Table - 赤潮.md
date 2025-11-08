---
{"publish":true,"tags":["table"],"cssclasses":""}
---


<%*
let title = tp.file.title
if (title.startsWith("Untitled") ) {
	title = await tp.system.prompt("File name: ")
} 
await tp.file.move("/worldbuilding/赤潮/随机表/" + title)
_%>

# <% title %>

<% tp.file.cursor(0) %>

`dice: [[<% title %>^table]]`

| dice: 1d6  | <% title %> |
| ---------- | ------- |
| 1 |  |
| 2 |  |
| 3 |  |
| 4 |  |
| 5 |  |
| 6 |  |
^table

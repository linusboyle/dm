```dataview
Table without id file.link AS "§", item.text as "交互"
From "worldbuilding" and #campaign/ash/session 
Flatten file.lists as item
where contains(item.text, this.file.name)
sort file.name DESC
```
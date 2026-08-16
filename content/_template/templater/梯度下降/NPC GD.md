<%*
let title = tp.file.title;

if (title.startsWith("Untitled")) {
    title = await tp.system.prompt("Enter the New Title: ");
	await tp.file.rename(title);
}

tp.hooks.on_all_templates_executed(async () => {
  const file = tp.file.find_tfile(tp.file.path(true));
  await tp.app.fileManager.processFrontMatter(file, (frontmatter) => {
    frontmatter["title"] = title;
    frontmatter["date"] = frontmatter["date"] || tp.file.creation_date("YYYY-MM-DD");
    frontmatter["aliases"] = frontmatter["aliases"] || [];
    frontmatter["tags"] = frontmatter["tags"] || [];
    frontmatter["instinct"] = frontmatter["instinct"] ||60;
    frontmatter["combat"] = frontmatter["combat"] || 40;
    frontmatter["wound"] = frontmatter["wound"] || 3;
  });
});
-%>

<%tp.file.cursor(0)%>

## 知道……


## 想要……


## 秘密

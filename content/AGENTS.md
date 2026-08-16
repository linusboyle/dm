
## General Guidelines

1. Use Obsidian CLI to determine currently opened file, if needed.
2. It is very possible that I modify notes. Always read content of a note, instead of relying on cached text in conversation history.
3. Any nested `AGENTS.md` along the path to project root should be read before modifying any subdirectory.

## Converting a source to Rollable Random Table

First locate a markdown file that matches the table theme. Otherwise create one. 

When converting, do not add or modify anything, just keep the entries as is.  Exception: dice formula in entry should be wrapped by `dice: <formula>` for the plugin to recognize it.

Put the table at the end, and add an inline dice roll.  Example:

```
`dice: [[filename^table]]`

| dice: 1d20 | Table Name                                                                                                                                                                                         |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1-4         | Entry 1                                                                                                                                      |
| 5-10       | Entry 2                                                                                                                              | 
| 11-20      | Entry 3                                                                                                                                      |
^table
```

If there is already table(s) in the same file, change the block-id ('table') to avoid collision.
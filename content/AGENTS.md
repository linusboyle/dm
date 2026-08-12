Use Obsidian CLI to determine currently opened file, if needed.

## Converting a source to Rollable Random Table

First locate a markdown file that matches the table theme. Otherwise create one. 

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

If there is already table(s) in the same file, change the block-id ('table') to avoid collison
```dataview
table file.mtime as "Last modified" where file.name != this.file.name SORT file.mtime DESC LIMIT 20
```

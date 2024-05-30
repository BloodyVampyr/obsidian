---
date: 2024-05-29
type: Notes
---



list from "Citations"
list from "Films"

list from "Films" where genre="S.F."
list from "Films" where genre="Animation"

table file.ctime, file.mtime
table file.mtime  where file.mtime>=date(today) - dur(2 day)

table where type="Film"
table where type="Citation" 
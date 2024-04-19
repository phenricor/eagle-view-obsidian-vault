# What did I create this week?
```dataview  
TABLE  
WHERE dateformat(file.cday, "yyyy-'W'WW") = "{{title}}"  
SORT file.cday DESC  
```
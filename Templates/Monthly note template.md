# What did I create this month?
```dataview  
TABLE dateformat(file.cday, "yyyy-'W'WW") AS "Week"  
WHERE dateformat(file.cday, "yyyy-MM") = "{{title}}"  
```
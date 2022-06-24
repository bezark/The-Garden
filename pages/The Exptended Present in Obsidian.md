An attempt to implement a sort of [[The Exptended Present]] in my view of [[Obsidian]]

First attempt: Dataview query. Real simple: show all files modified in the last 3 days:
# 1
```dataview
list file.mtime
from ""
where file.mtime > (date(now) - dur(1 days))
sort file.mtime desc
```

# 2
```dataview
list file.mtime
from ""
where file.mtime > (date(now) - dur(2 days))& (file.mtime < (date(now) - dur(1 days)))
sort file.mtime desc
```

# 3
```dataview
list file.mtime
from ""
where file.mtime > (date(now) - dur(3 days))& (file.mtime < (date(now) - dur(2 days)))
sort file.mtime desc
```

# Next
This is Nice and all, but I really want to see these in the graph view.
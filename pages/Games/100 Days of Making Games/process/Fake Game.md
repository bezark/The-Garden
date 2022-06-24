---
publish: true
tags:
  [game/dev/active]
players: 
genre: 
playtests: null
---

# Brainstorms
```dataview
table Iteration, file.cday AS Created FROM #game/dev/brainstorm WHERE parentGame = [[Fake Game]]
```

```button  
name New Brainstorm 
type note(\<\% tp.date.now()\%\> Fake Game Brainstorm) template  
action Game Brainstorm
templater true
```


# Iterations
```dataview
table file.cday AS Created FROM #game/dev/iteration WHERE parentGame = [[Fake Game]]
```


Should:
- [x] List all relevant brainstorms a
- [x] and all Iterations
- [ ] Buttons for creating brainstorms specifically for this game
- [ ] creating iterations specifically for this game
- [ ] Reflections specific to the project
- [ ] Could even have specific todoist views for the project

Maybe there is a Kanban Board that has
Brainstorms, Iterations, Playtests and Final?


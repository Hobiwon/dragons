---
title: Tyrany of Dragons
description: Campaign dashboard
---

Welcome to the campaign hub for our adventures across the Sword Coast.  

> Dragons stir. Cultists gather. The Sword Coast waits to see who will stand against the coming tyranny.

---

## The Party

<div class="pc-grid">  

<a class="pc-card" href="/Characters/Clérwen">
<img src="/Assets/characters/clerwen.png">
<h3>Clérwen</h3>
<p>Elf Cleric</p>
</a>

</div>

---  

## Latest Session Notes

```dataview
LIST
FROM "Sessions"
SORT date DESC
LIMIT 10
```

[[Sessions/Sessions Archive|View full session archive →]]

---

## NPCs

```dataview
TABLE faction, status
FROM #npc
SORT location
```


## Campaign Quick Links

| Area | Link |
|---|---|
| Campaign Overview | [[Campaign/Overview]] |
| Recap So Far | [[Campaign/Recap So Far]] |
| Important NPCs | [[Campaign/Important NPCs]] |
| Factions | [[Campaign/Factions]] |
| Sword Coast Guide | [[Setting/Sword Coast]] |
| House Rules | [[Campaign/House Rules]] |

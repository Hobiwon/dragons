---
tags:
  - SessionNote
aliases:
whichParty:
sessionDate:
recapPlayer:
fc-calendar: Example Calendar
fc-category: Session Notes
fc-date: YYY-MM-DD
fc-end: YYY-MM-DD
summary: ""
---

## Quick References
> [!grid|col-3]
> ```dataview
> LIST
> FROM outgoing([[]])
> WHERE econtains(tags,"Character")
> SORT file.name ASC
> ```
> 
> ```dataview
> LIST
> FROM outgoing([[]])
> WHERE econtains(tags,"Location")
> SORT file.name ASC
> ```
> 
> ```dataview
> LIST
> FROM outgoing([[]])
> WHERE !econtains(tags,"Character") AND !econtains(tags,"Location")
> SORT file.folder DESC
> ```

## Session Notes
- 

## Next Session Reminders
- 

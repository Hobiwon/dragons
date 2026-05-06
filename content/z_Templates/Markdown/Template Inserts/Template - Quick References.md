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
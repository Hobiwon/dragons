---
tags:
  - Vehicle
art: "[[Placeholder_Vehicle.jpg]]"
aliases:
vehicleType:
owners:
affiliations:
located:
---

> [!infobox | no-blending black]+ <font color="#ffffff">Infobox</font>
> 
> `VIEW[!{art}][text(renderMarkdown)]`
> 
> # Information
> | | |
> |---|---|
> | **Aliases** | `VIEW[{aliases}][text]` |
> | **Type** | `VIEW[{vehicleType}][text]` |
> | **Owners** | `VIEW[{owners}][link]` |
> | **Affiliations** | `VIEW[{affiliations}][link]` |
> | **Located** | `VIEW[{located}][link]` |

~~~meta-bind-button
label: Insert Pronounced
style: primary
action:
  type: replaceSelf
  templater: true
  replacement: "z_Templates/Markdown/Template Inserts/Template - Pronounced.md"
~~~

> [!poem|directory]- Directory
> ![[Database - Vehicle Note.base]]

<font color="#7f7f7f">A short overview summarizing what this vehicle is, its purpose, and its role or significance.</font>

## Description
<font color="#7f7f7f">Describe the exterior of this vehicle, focusing on its structure, materials, layout, and any visible features.</font>

## Map
> [!kirk|blank]
> ```leaflet
> ### By using ### at the start of a line, we "comment" it out. We can use this to either leave notes or disable lines if we don't need them.
> ### Once you are familiar with how Leaflet works, I recommend removing the commented tips so you have a cleaner setup.
> ### Video Tutorial: https://youtu.be/47gVvg06jNM
>  
> ### Height and Width allow you to determine the size of the map interface. These have been commented out by default for you.
> ### height: 500px
> ### width: 640px
>  
> ### ID is a Unique ID that allows you to define the map. So you can have multiple maps that use the same image, but are used for different things. I have left an example ID in here for you.
> id: Example
>  
> ### Image is the main image for the map. I have left an example image in here for you.
> image: 
> - [[PlaceholderImage.png|Main]]
>  
> ### Image Overlays are images we can put on top of another, allowing us to display information such as territories or districts. I have left an example image in here for you.
> imageOverlay:
> - [[[PlaceholderImage.png|TBD]]]
>  
> ### Lock means we can't edit the map by default; this can be set to false or toggled using the lock in the UI.
> lock: true
>  
> ### Recenter will recenter the map each time you come back to it.
> recenter: true
>  
> ### No scroll zoom will disable the use of the scroll wheel to zoom in and out of your maps.
> noScrollZoom: false
>  
> ### Bounds sets the size of the map, which is determined by the pixels height and width of your image. Keep the first [0,0] as it is, then set the second as [HEIGHT,WIDTH]. I have left an example for you.
> bounds: [[0, 0], [4388, 3823]]
>  
> ### Lat (Latitude) & long (Longitude) are used to set the default location of your map. 0 & 0 is the centre. Use can use Left SHIFT + Left Click to get the coordinates of a location on your map to change the default position.
> lat: 0
> long: 0
>  
> ### Min & max zooms are used to set how far you can zoom in and out of our map.
> minZoom: -3.5
> maxZoom: 3
>  
> ### Default zoom is the zoom level you start at.
> defaultZoom: -3.5
>  
> ### The zoom delta is the increment that you zoom in or out by.
> zoomDelta: 0.5
>  
> ### Unit is what you measure your distance by. We can measure the distance between two points by using Left ALT & Left Click.
> unit: miles
>  
> ### Scale is used to determine the size of the image. We use this to fine-tune our maps to the correct scale so that our measurement tools are accurate.
> scale: 0.0404
>  
> ### Marker tags are a tag we can use the tags property to tell a map we want a specific note to be marked onto it. Change TBD to something relevant, such as #MapIt-London".
> markerTag: 
> - "#MapIt-TBD"
> ```

## Notable
### Figures
<font color="#7f7f7f">Who are the notable individuals?</font>
- <font color="#7f7f7f">TBD</font>, _Captain_
	- <font color="#7f7f7f">Details</font>

### Locations
<font color="#7f7f7f">What important rooms or areas make up this vehicle?</font>
- <font color="#7f7f7f">TBD</font>, _Captain's Quarters_
	- <font color="#7f7f7f">Details</font>

~~~meta-bind-button
label: Insert Crafting
style: primary
action:
  type: replaceSelf
  templater: true
  replacement: "z_Templates/Markdown/Template Inserts/Template - Crafting.md"
~~~

## History
### Background
<font color="#7f7f7f">Significant events, changes, or how its past influences its current purpose or reputation. Are there any rumours or legends surrounding this vehicle?</font>
- <font color="#7f7f7f">TBD</font>
	- <font color="#7f7f7f">Details</font>

## Notes

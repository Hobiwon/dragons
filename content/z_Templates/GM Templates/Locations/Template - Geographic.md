---
cssclasses:
  - banner
  - banner-gradient
tags:
  - Location
  - Geographic
location:
mapmarker:
art: "[[Placeholder_Geographic.jpg]]"
aliases:
geographicType:
  - Continent
  - Island
  - Ocean
affiliations:
located:
---
![[Placeholder_Geographic.jpg]]

> [!infobox | no-blending black]+ <font color="#ffffff">Infobox</font>
> 
> `VIEW[!{art}][text(renderMarkdown)]`
> 
> # Information
> | | |
> |---|---|
> | **Aliases** | `VIEW[{aliases}][text]` |
> | **Type** | `VIEW[{geographicType}][text]` |
> | **Affiliations** | `VIEW[{affiliations}][link]` |
> | **Located** | `VIEW[{located}][link]` |

~~~meta-bind-button
label: Insert Pronounced
style: primary
action:
  type: replaceSelf
  templater: true
  replacement: "z_Templates/Markdown/Template Inserts/Pronounced.md"
~~~

> [!poem|directory]- Directory
> ![[Database - Geographic Note.base]]

<font color="#7f7f7f">Provide an overview that summarizes the area. Focusing on its scale, geography, and importance to the world as a whole.</font>

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

## Regions
<font color="#7f7f7f">Describe the climate, using real world examples to set expectations. For larger areas with varying climates, break down where it gets hotter and colder.</font>

### Region Example
<font color="#7f7f7f">Describe any key details about this region, from unique features to ongoing tensions.</font>
- **<font color="#ffc000">Settlements</font>**
	-  <font color="#7f7f7f">Example</font>: <font color="#7f7f7f">Details</font>
- **<font color="#92d050">Points of Interest</font>**
	-  <font color="#7f7f7f">Example</font>: <font color="#7f7f7f">Details</font>

## Society
### Demographics
_100% Human, 0% Dwarf, 0% Elf, 0% Gnome, 0% Halfling, 0% Other_
<font color="#7f7f7f">Outline the dominant ancestries or cultures in this area and briefly explain what historical, geographical or political factors helped shaped the population.</font>
- <font color="#7f7f7f">Example</font>: <font color="#7f7f7f">Details</font>

### Politics
<font color="#7f7f7f">Outline the governing structure of this area, including who holds power, how authority is enforces, and any major factions, noble houses, or guilds that influence this area. Note key laws, political tensions and how control is established.</font>
- <font color="#7f7f7f">Example</font>: <font color="#7f7f7f">Details</font>

## History
<font color="#7f7f7f">Outline the major eras, conflicts, and transformations that define this area’s past, explaining how history shaped its current political, cultural, and environmental state.</font>
- <font color="#7f7f7f">Example</font>: <font color="#7f7f7f">Details</font>

## Notes

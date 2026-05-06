---
tags:
  - Location
  - Region
art: "[[Placeholder_Basic.jpg]]"
aliases:
organizations:
located:
---

> [!infobox | no-blending black]+ <font color="#ffffff">Infobox</font>
>
> `VIEW[!{art}][text(renderMarkdown)]`
>
> # Info
> |  |  |
> |---|---|
> | **Aliases** | `VIEW[{aliases}][text]` |
> | **Dominion** | `VIEW[{organizations}][link]` |
> | **Located** | `VIEW[{located}][link]` |

<font color="#7f7f7f">Write a brief summary of the region, highlighting its defining features, climate, and overall significance.</font>

## Database

![[Database - Region Note.base]]

## Maps

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

## Present
### Travel

| `dice: 1d4\|noform` (Result) | Event                           | Information / Description                                                                                     |
| ---------------------------- | ------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| 1                            | Nothing                         | Nothing eventful happens on this leg of the journey.                                                          |
| 2                            | Pass Traveling NPC              | You cross paths with a NPC(s), they are either uninterested with the party or are willing to have small talk. |
| 3                            | Interesting Sighting            | You spot something interesting, either something beautiful within nature or maybe a forgotten pouch of gold.  |
| 4                            | <font color="#ffff00">Encounter | Use the Random Encounter table below.                                                                         |

### Local Inhabitants (Random Encounter)

| `dice: 1d4\|noform` (Result) | Name   | Information / Description                                                        |
| ---------------------------- | ------ | -------------------------------------------------------------------------------- |
| 1                            | Bandit | A group of bandits are roaming the area, looking to score some gold.             |
| 2                            | Wolves | A hungry pack of wolves roam the treelines.                                      |
| 3                            | Troll  | A troll has wandered too far from it's cave... I thought you would like to know. |
| 4                            | Dragon | A dragon nests in the area, looking for a meal for it's hatchlings.              |


### Current Events
- <font color="#7f7f7f">Example Quest</font>
    -  <font color="#7f7f7f">Summary of a quest the player can get involved in.</font>
- <font color="#7f7f7f">Example Event</font>
    - <font color="#7f7f7f">Summary of an event that's going on on this region which may not relate to a specific quest or may relate to multiple.</font>

## Past
### History
<font color="#7f7f7f">Describe the history of the region, including its origin, important past events, and how those shaped its current identity.</font>

### Secrets, Rumours & Legends
<font color="#7f7f7f">Describe the secrets, rumours, and legends tied to the region, including hidden truths, whispered stories, and myths that influence how it is seen.</font>

## Notes


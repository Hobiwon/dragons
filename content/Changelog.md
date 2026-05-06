---
tags:
  - Changelog
---

> [!infobox | no-blending black]+ <font color="#ffffff">Infobox</font>
> 
> ![[ObsidianGemBOT.jpg]]
> 
> # **Join the Community**
> | | |
> | --- | --- |
> | **Discord** | [Join](https://discord.gg/Rn5PSAPTpH) |
> | **Reddit** | [Join](https://www.reddit.com/r/BagOfTips/) |
> | **Bluesky** | [Follow](https://bsky.app/profile/bagoftips.bsky.social) |
> | **YouTube** | [Subscribe](https://www.youtube.com/@BagOfTips?sub_confirmation=1) |
> | **Twitch** | [Follow](https://www.twitch.tv/bagoftips) |
> | **Ko-fi** | [Support](https://ko-fi.com/bagoftips) |

## 2.1 Release | 23/08/25 (DD/MM/YY)

There are a LOT of changes from 2.0 to 2.1, too many to cover for each and every small change. What I recommend is having a read through the [[README]] to best understand the vault as a whole. If you are coming from 2.0, the methodology of the notes are mostly the same, but with some improvements. But now we are doing a lot of our organisation of data through bases.

## 26/08/25

- Added [[Template - Creature]]
- Added [[PlaceholderCreature.png]]
- Added Creature QuickAdd and Button to [[Buttons]].
- Various spells or grammar corrections in [[README]]
- Changed the [[Notepad]] '#Notepad' tag to 'Notepad'.
- Fixed the display for linkedAdventure in [[Template - Quest]]
- Removed references of the old 'domain' property in databases.
- Deleted an unused Database.

## 03/09/25

- Replaced the Manual Sorting plugin with Custom File Explorer plugin [[README#[Custom File Explorer Sorting](https //github.com/SebastianMC/obsidian-custom-sort)]]. This **SHOULD** help resolve some lag issues.
- Fixed the second Aliases in [[Template - Deity]] to say pronouns.
- Disabled SCallouts snippet by default
	- Changed ITS/SCallouts to FaS by default. If you change themes, you will need to edit these yourself.
- Updated leaflets to include the formatting to allow multiple layers as standard.

## 12/09/25

- Cleaned up various infoboxes.
- Added `pronounced` property and display to the following:
	- [[Template - Player]]
	- [[Template - Deity]]
	- [[Template - NPC]]
	- [[Template - NPC (Tabs)]]
- Added `titles` property and Infobox dIsplay to the following:
	- [[Template - Player]]
	- [[Template - NPC]]
	- [[Template - NPC (Tabs)]]

## 05/10/25

- Added the [Retroma](https://github.com/emarpiee/Retroma) theme as an option within the vault.
- Update Maps to have a overlay by default to better showcase the available feature.
- Moved all location folders to a parent Locations folder in campaign.
	- Updated all QuickAdd options to use these new folders.
	- Updated all bases to use these new folders.
- Added the [[Database - Location Master.base]], see [[README#Database - Location Master.base]] for more details.
- Enabled property viewer in the left-hand pane by default. This can be removed if you don't like it.
- Updated the README to explain more about the removal of metadata tabs and how to best use properties. See [[README#Where did the Metadata tab go from 2.0?]]

## 02/11/25

- Updated the [[Database - Location Master.base]] formula to include an additional step.
- Updated the Leaflet Maps.
	- Neatened the code for better Tutorialization.
	- Changed their callout to be blank.
	- Added the video tutorial to both the code & [[README]].
- Updated the README with various fixes and clarifications.
- Updated the [[Vault Hub]] with better Age Calculator clarifications.
- Various spelling & grammar fixes

## 02/12/25
### New
- Enabled 'Show Inline Title' in appearance settings.
- Header 2 is now normal, Header 1 is set to stroke in FaS Style Settings.
- Set FaS Banner Height to 100.
- Set FaS Banner style in edit mode to icon.
- [[Database - Quests References.base]]
	- Lets you see all quests that reference a note.
- [[Database - References.base]]
	- Lets you see all notes that reference a note.
- [[Template - Goods & Services]]
- [[Template - Pronounced]]
- Bigger inline title css. ([[README#BiggerInlineTitles]])
-  **READ THIS** >[[README#How should I format my notes?]]

---

### Updated
- All template headers.
- BOTCalloutsDarkmode
- Enabled Hover Editor plugin
- Updated page preview settings.

#### [[Template - Settlement]]
- New formatting.
- Properties
	- added cssformatting property.
		- Added banner option.
		- Added banner-gradient option.
	- Removed the following properties;
		- tradePartners
		- leaders
		- defence
	- Changed Infobox Dominion to Affiliation

#### [[Template - District]]
- New formatting.
- Properties
	- Added cssformatting property.
		- Added banner option.
		- Added banner-gradient option.
	- Removed the following properties;
		- districtType
	- Changed Infobox Dominion to Affiliation

#### [[Template - Point of Interest]]
- New formatting.
- Properties
	- added cssformatting property.
		- Added banner option.
		- Added banner-gradient option.
	- Changed Infobox Dominion to Affiliation
- Updated the POI Supercharged link
- Updated Quickadd Options

#### Database Updates
Updated the bases to have customized "steps" when looking for notes using currentLocation.
- [[Database - Settlement Note.base]]
- [[Database - District Note.base]]
- [[Database - POI Note.base]]

### [[Rollable Table - Travel & Encounter]]
- New formatting.

---

### Removed
- Template - Point of Interest (Shop)

## 07/01/26
### New
- Added [[README#BetterListSpacing]]
- Added [[README#HideStatusBar]]

---

### Updated
- All 'organizations' properties changed to 'affiliations'
	- Updated all infoboxes to match
- Header changes reverted from last update.
- Small changes in the Fancy a Story Style Settings.
- All 'currentLocation' properties renamed to -> 'located'
	- For those that already have made loads of notes, this isn't a change you NEED to make. Just a good change for new users.

#### [[Template - NPC]]
- New formatting.

#### [[Template - NPC (Tabs)]]
- New formatting.

#### [[Template - Player]]
- New Formatting

#### [[Template - Deity]]
- New Formatting
- deityPower property -> deityType
- Added Gender property

#### [[Template - Faction]]
- Name Change: Organization -> Faction
	- Some people have been confused with the usage of the word Organization, though it is a better word that covers the notes use. However, it's just a word. My hopes are this name change makes it clearer what this note is for, as it's usage is still the same.
- New Formatting
- organiztionType -> factionType
- parentOrganization -> parentFaction
- New members property
- Updated folder name
- Updated QuickAdd
- Updated Meta Bind button

#### [[Template - Point of Interest]]
- Updated Formatting

#### [[Template - District]]
- Updated Formatting
	- I have personally stopped using this note. I keep it in here as an example for what you could possibly use it for.

#### [[Template - Settlement]]
- Updated Formatting
- rulers -> leaders

#### Databases
- [[Database - POI Note.base]]
- [[Database - District Note.base]]
- [[Database - Settlement Note.base]]
- [[Database - Factions Note.base]]

#### Other
- Various spelling and grammar corrections

---

### Removed
#### [[Template - Faction]]
- worships property
  
## 17/02/26
### [[Template - Geographic]]
- Template - Topography > [[Template - Geographic]]
- Database - Topography Note > [[Database - Geographic Note.base]]
- topographyType > grographicType
	- Added Continent, Island and Ocean options for better understanding of properties.
- Dominion Infobox Section > Affiliations
- organizations property > affiliations
- Added cssclasses property with banner and banner-gradient options
- General note rework
- Updated Metabind button & quickadd option.

### [[Template - World]]
- Dominion Infobox Section > Affiliations
- organizations property > affiliations
- Added Planet and Moon options to the worldType property for better understanding of properties.
- Added cssclasses property with banner and banner-gradient options
- General note rework

### [[Template - Deity]]
- Fixed [[Database - Deity Note.base]] reference issue

### Depreciated
Moved the following templates to a Depreciated Folder as I no longer plan on maintaining them as part of the main workflow. I will however periodically update these when needed for those that use them. 
- [[Template - Region]]
- [[Template - Area]]
- [[Template - District]]

With this, I have updated the following bases to remove reference to them. You are welcome to add them back if you wish to use them.
- [[Template - Settlement]]
- [[Template - Geographic]]

### Other
- Updated [[sortspec]] to adjust for changes with [[Template - Geographic]] & Depreciated templates.
- [[Buttons]] refresh.
- Various spelling/grammar corrections
- Added BasesCalloutConflictFix.css
- Updated [[README]]

## 18/03/26
### Updated
- [[Template - Plane]] updated with new formatting.
	- [[Database - Plane Note.base]] updated with new specifications.
- [[Template - Vehicle]] updated with new formatting.
	- [[Database - Vehicle Note.base]] updated with new specifications.
- [[Campaign Stat Tracker]]: Fixed POI Types not displaying as I never updated the folder it was looking for.
- [[Template - Adventure]] now uses the Tag 'Adventure' rather than '#Adventure'

## 13/04/26
### New
- Placeholder Image
	- Replaced the old placeholder images with a new version.
		- These will be expanded on soon!
- [[Template - Crafting]]
	- New template designed to be inserted into the [[Template - Item]] template. However, it could be used for other notes such as [[Template - Vehicle]] or [[Template - Spell]].

### Updated
- [[Template - NPC]], [[Template - NPC (Tabs)]] & [[Template - Player]]
After putting it to the community to see if they used the age calculation systems, the majority do not. So, I have removed this system from the template Vault.
	- Removed _fc-date_, _birthday_ & _year_ properties.
	- Removed the birthday date selectors.
	- Replaced the age VIEW from the infobox with a default VIEW.
- [[Vault Hub]]
	- Removed the Age Calculation JS along with the properties needed.
-  [[Template - Session Note]], [[Template - Adventure]] & [[Notepad]]
	- Updated the quick references Dataview.
- [[Template - Item]]
	- New Formatting
	- New button to use the [[Template - Crafting]].
- [[Template - Vehicle]]
	- New button to use the [[Template - Crafting]].
- [[Template - Letter]]
	- New Formatting
	- Removed the _recipient_, _sentTo_, _sender_, _sentFrom_, _fc-calendar_, _fc-category_ & _fc-date_ properties.
- [[Template - Service]]
	- Removed the _fc-calendar_, _fc-category_ & _fc-date_ properties.
	- Added _dueDate_ property.
	- Renamed the _serviceCost_ property to _cost_.
- [[README]]
	- Removed the JS Plugin section.
	- Updated properties breakdown for templates.

### Removed
- Javascript Plugin
	- We only used this for the age calculation, with that being removed there is no longer a need for this.
	- My goal with this vault is to be as straightforward as possible, so if you want to install Javascript and use it, by all means feel free to do so.

<p style= "center">
<img src="https://i.pinimg.com/600x315/54/b9/f3/54b9f38814469280a8489a66ed90c3a2.jpg"></img>
</p>

# G.I. Joe Dataset

A dataset for G.I. Joe action figures from 1980s to 2002. Action figures continued to be made up to year 2017 but this dataset is long enough for one person to put together, web scraping was not applicable in my case. 
Action figure sizes are 3 3/4" for G.I. Joe Action Figures in this dataset.

Note: *This dataset is not extensive.*
The data is from the yojoe.com database. 

Dataset curated by **Zane Dax** (@StarTrek_Lt)

## Color Palette
- GI Joe: #02498E, #FFF, #E50414
- COBRA: #000 and #FE0000

## Logos 
This folder has GI Joe and Cobra icon logos with transparent backgrounds to aid your data visualizations

## Some preliminary questions 
* how many *distinct* GI Joes are there? 
* how many COBRA enemies are there?
* what is the sex ratio for GI Joe soldiers vs COBRA?
* what states are GI Joes most commonly from?
* what rank is most common?
* what year had the most GI Joes?
* what year did GI Joe take on environmental concerns?

## Data dictionary

| key | explanation |
|-----|-------------|
|name | G.I Joe known name|
|year | year action figure made | 
|file_name | official name on file| 
|version | the version of action figure | 
|grade or rank | rank of soldier |  
|birthplace | origin of birth | 
|Primary_Specialty | main combat skillset or training | 
|Secondary_Specialty| second combat skillset or training | 
|Q_E | qualified expert in technical skill |
|S_E | specialized education in technical skill |
|sex | the sex of the action figure | 
|race | the race of action figure |
|team | team associated with action figure GI Joe or COBRA|

* COBRA is a group of GI Joe enemies, officially named Cobra Command. This dataset simplifies all enemies of GI Joe military personnel as COBRA even though there are other factions such as the Dreadnoks, Iron Grenadiers, and the Oktober Guard. Most of these Cobra Command figures packaging has COBRA logo and is reason behind the binary classification. *For futher information see [GI Joe wiki]("https://en.wikipedia.org/wiki/Oktober_Guard#G.I._Joe_Team)*

* Sex and Race columns were added to dataset and not entirely part of the website's original data. *Race is a guess based on the figure's plastic outside coating when no information is provided in the 'Filecard Information' section. This data is included only to provide some demographic data, and not to be taken as fact.*


## US Army Ranks
| key | explanation |
|-----|-------------|
|E-1 | Private |
|E-2 | Private 2nd Class |
|E-3 | Private 1st Class|
|E-4 | Corporal |
|E-5 | Sergeant |
|E-6 | Staff Sergeant |
|E-7 : E-9 | Senior Non-Commissioned Officer |
|E-7 | Sergeant 1st Class |
|E-8 | Master/ First Sergeant |
|E-9 | Command/ Sergeant Major |
|WO-1 | Warrant Officer 1 |
|WO-2 | Warrant Officer 2 |
|WO-3 | Warrant Officer 3 |
|WO-4 | Warrant Officer 4 |
|WO-5 | Warrant Officer 5 |
|OF-1 | Lieutenant junior grade |
|O-1 | Second Lieutenant |
|O-1 | First Lieutenant |
|O-2 | Captain |
|O-3 | Major |
|O-4 | Lietenant Colonel |
|O-5 | Colonel |
|O-6 | Brigadier General |
|O-7 | Major General |
|O-8 | Lietenant General (Commander) |
|O-9 | General |



## US Air Force Ranks
| key | explanation |
|-----|-------------|
|E-1 | Graduate, Basic |
|E-2 | Basic Training |
|E-3 | Journeyman, First Class |
|E-4 | Senior, Non-Commissioned Officer |
|E-5 & E-6 | Non-Commissioned Officer |
|E-5 | Staff Sergeant (-5 Journeyman, - 7 craftsman) |
|E-6 | Technical Sergeant |
|E-7 : E-9 | Senior Non-Commissioned Officer |
|E-7 | Master Sergeant |
|E-8 | Senior Master Sergeant |
|E-9 | Command/ Chief Senior Master Sergeant |



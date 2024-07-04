# Coral-Reef-Dashboard
An interactive dashboard displaying coral reef pollution and health at local, regional, and global scales.

<img alt = "Coral Reef Dashboard GIF" img src="./Coral Reef Bleaching Dashboard_EmekaEmeche (1).gif"/>

## How It's Made:

**Tech used:** ArcGIS Online, ArcGIS Dashboards

I first went on ArcGIS Online to search for the NOAA Coral Reef Watch data. I opened it in Map Viewer to prepare the web map for the dashboard and I examined all the layers and features. I saw the attribute table showing Degree Heating Weeks and Alert Level which is the crucial information central to the dashboard I'll be making. I clicked the Basemap button and slected the Human Geography Dark Map and zoomed the map in to fill the map view, I saved the map and filled in the appropariate information. I created a new Dashboard and chose the Dark, while doing this I changed the header to display the title of the dashboard.

Next up was adding list elements to show the monitoring status at each virtual station (feature), which is sorted with the highest accumulated heat stress at the very top by clicking the Add Element button and choosing List. I put in on the left side of the dashboard and linked the layers from Coral Reef Bleaching web map I created and expanded the NOAA Coral Reef Watch (CRW) Virtual Stations layer. I sorted the Degree Heating Weeks, which reprsents accumulated heat stress, into descending order and updated the text from that list to dynamically show the monitoring status at each virtual station. After that, on the Actions tab, I clciked the Show Pop-Up and turned on the Coral Reef Bleaching option to show the pop-ups whenever a location is selected.

## Optimizations
*(optional)*

You don't have to include this section but interviewers *love* that you can not only deliver a final product that looks great but also functions efficiently. Did you write something then refactor it later and the result was 5x faster than the original implementation? Did you cache your assets? Things that you write in this section are **GREAT** to bring up in interviews and you can use this section as reference when studying for technical interviews!

## Lessons Learned:

No matter what your experience level, being an engineer means continuously learning. Every time you build something you always have those *whoa this is awesome* or *wow I actually did it!* moments. This is where you should share those moments! Recruiters and interviewers love to see that you're self-aware and passionate about growing.

## Repositories
**GIS Climate Action Repository:** https://github.com/T3ch12et/GIS-Data-Science-Portfolio/tree/main/ESRI-MOOC-GIS-for-Climate-Action <br>
<br>
**Main Repository:** https://github.com/T3ch12et/GIS-Data-Science-Portfolio

## Examples:
Take a look at these couple examples that I have in my own portfolio:

**Miami Sea Level Rise:** https://github.com/T3ch12et/GIS-Data-Science-Portfolio/tree/main/ESRI-MOOC-GIS-for-Climate-Action/3D-Miami-Beach-Sea-Level-Rise <br>
<br>
**Athens Heat Risk Index:** https://github.com/T3ch12et/GIS-Data-Science-Portfolio/tree/main/ESRI-MOOC-GIS-for-Climate-Action/Athens-Heat-Risk-Index <br>
<br>
**Oso Mudslide:** https://github.com/T3ch12et/GIS-Data-Science-Portfolio/tree/main/ESRI-MOOC-Cartography/Oso-Mudslide <br>
<br>
**Hurricanes since 1851:** https://github.com/T3ch12et/GIS-Data-Science-Portfolio/tree/main/ESRI-MOOC-Cartography/Hurricanes-since-1851

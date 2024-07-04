# Coral-Reef-Dashboard
An interactive dashboard displaying coral reef pollution and health at local, regional, and global scales.

<img alt = "Coral Reef Dashboard GIF" img src="./Coral Reef Bleaching Dashboard_EmekaEmeche (1).gif"/>

## How It's Made:

**Tech used:** ArcGIS Online, ArcGIS Dashboards

I began by accessing ArcGIS Online to search for the NOAA Coral Reef Watch data. I opened it in Map Viewer to prepare the web map for the dashboard, thoroughly examining all the layers and features. The attribute table displayed crucial information such as Degree Heating Weeks and Alert Level, which are central to the dashboard I was creating. I selected the Human Geography Dark Map from the Basemap options and zoomed in to fill the map view. After saving the map and entering the appropriate information, I proceeded to create a new dashboard and chose the dark theme, updating the header to display the dashboard's title.

Next, I added list elements to show the monitoring status at each virtual station (feature), sorting them by the highest accumulated heat stress. By clicking the "Add Element" button and selecting "List," I placed it on the left side of the dashboard. I linked the layers from the Coral Reef Bleaching web map I had created and expanded the NOAA Coral Reef Watch (CRW) Virtual Stations layer. I sorted the Degree Heating Weeks, representing accumulated heat stress, in descending order and updated the list text to dynamically display the monitoring status at each virtual station.

On the Actions tab, I enabled the "Show Pop-Up" option for the Coral Reef Bleaching feature to display pop-ups whenever a location was selected. I then added a serial chart to show the number of virtual stations by alert level, ranging from 0 (no bleaching) to 4 (severe bleaching). I placed the chart on the left side of the dashboard, sourcing the layer from the Coral Reef Bleaching web map and expanding the NOAA Coral Reef Watch (CRW) Virtual Stations layer. In the Data Options pane, I selected "Alert Level" for the Category Field. I adjusted the labels for each category on the x-axis in the Category Axis tab and changed the y-axis label to "Number of Coral Stations" in the Value Axis tab. In the Series tab, I chose "By Category" for the Bar Color option, assigning different colors to represent the severity of coral bleaching: light blue for No Alert, light yellow for Watch, peach for Warning, light brown for Level 1, and dark brown for Level 2. These labels were updated on the axis in the previous step. To ensure the actions worked, the elements had to share a data source or be mapped to the data source. I filtered the Target Field to "Alert Level" in the Actions tab, so clicking on the bar graph for an alert level would show the corresponding points on the map.

Finally, I added an indicator element to the top left corner of the map to display dynamic summary statistics based on attribute fields in the dashboard data. This indicator reported the number of virtual stations indicating that the coral reef was at risk of bleaching. Again, I selected the Coral Reef Bleaching web map from the Virtual Stations layer of NOAA Coral Reef Watch (CRW). In the Data Options pane, I built an expression filter stating _Alert Level Greater Than Or Equal 3_ to show the number of stations with a Level 1 or 2 alert. To provide context, I included the total count of virtual stations. In the Reference section, I chose "Statistic" for the Reference type. In the Indicator Options pane, I typed "Coral reefs at risk of bleaching" out of the total number of stations. Lastly, I configured the actions to ensure the different elements of the dashboard could interact with each other.

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

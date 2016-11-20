

MAP TOPIC
---------
 - *What are you mapping?*  **I’m mapping the 3 programs areas of the Louisville Visual Art (LVA)** -- http://www.louisvillevisualart.org/
 - *Briefly describe the topic and the geography the map intends to represent.* **The map will show the education, outreach, and support programs of LVA across the city of Louisville**
 - *Tentative title.* **Mapping the Mission: Past & Present Projects of of the Louisville Visual Art**

Map objectives and user needs
---------
•	*"Why are you making this map?"* **I'm making this map as a community resource, to demonstrate the work of LVA across Louisville.**

•	*Consider your own positionality with respect to the map and tell us why you are making it and what you want to get out of it*. **I'd like to help LVA demonstrate the reach and impact of the work they do with communities**

•	*Create a brief user persona and tell us what this persona(s) will get out of the map. Why are they using it? How would you characterize this user in terms of their expertise and motivation (i.e., novice/public, average, expert/domain-specific)* **One user persona would be someone hoping to connect with LVA, to find ways to bring artists to a particular population or project. The user level of knowledge would be novice/public to average.**

•	*Imagine a scenario about how the user may use the map. It need not cover all potential use case scenarios, but it should describe some potential action the user will engage in to meet their objective (i.e., filtering the data, searching for an address, changing the attribute through a dropdown menu)*  **A user may learn about the work of LVA, and specifally what types of activities are occuring in their neighborhood. When the map first loads, and see there are 3 major program areas the user will select, perhaps from a drop down. They will be able to click on points and see more information (including organizer info) about each project. There will also be a slider for year, so the user can see past and current projects, and possibly projects slated for the near future.**

Data source
---------
1. *your anticipated data source* **The data is provided by LVA. They still may have some additions and improvement, but I've worked with them to get enough data in which I can achieve the functionality described above. It definitely will need some restructuring.**
2. a small sample of the data (e.g., CSV, GeoJSON, Shapefile, or within a database)
https://docs.google.com/spreadsheets/d/1LAmRyfVI55_VTuNE17l7TlFXfiL1qXZiFoez-WMOWNo/edit?usp=sharing

Anticipating your technology stack
----------------------------------
*•	data and information processing tools, web-based or desktop (i.e., QGIS, MapShaper)* **I plan to use Excel mainly for reorganing the data. Currently I believe I'll only be generating points on top of a basemap, perhaps with some D3 proportional symbols for number of program participants. I will probably use QGIS to geocode the locations.**

*•	the format you'll use to store your data (i.e., flat files such as CSV or GeoJSON, database technology such as CartoDB)* **I will probably use CSV, but I'd love to find a way to employ GeoJSON for practice, assuming it make sense for the project.**

*•	the JS libraries you anticipate using or need (include any relevant plugins)* **Leaflet of course. I will probably need simple statistics for the proportional symbols.**

*•	the hosting platform you intend to use to host your map (i.e., GitHub pages, your own web server)* **For now I think it will live on Github pages... but eventually, it may live on the LVA website**


Note: This is a draft of the information we'll want to include in your final map writeup. While informative to curious users of your map, it also looks good to employers and clients in terms of demonstrating your expertise in the world of open source web mapping!



> Written with [StackEdit](https://stackedit.io/).

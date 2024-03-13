# Deployment Order Tool (DOT)
This is a web mapping application used to find the nearest Urban Search and Rescue Team to an incident point of arrival. 

This application is currently used by FEMA US&R Branch staff to determine the closest Task Force based on trucking distance and/or travel time. It can be adapted for other purposes but the intended audience for the core application is the FEMA US&R Branch only. For more information on this project, contact the author. 

Deployment Order Tool 2.0 (requires username and password) https://experience.arcgis.com/experience/9c74a78957d24994af8536ce1015f197

![image](https://github.com/pjdohertygis/DeploymentOrderTool/assets/4256979/b378fa7b-0731-48a6-8c9b-1dd114741778)

# How Does It Work? 
To provide a simplified end user process with rapid results, we pre-calculated the truck-driving distance between 28 FEMA US&R Task Force Points of Departure (POD, static) and USNG 5km Grid Centroids. Then the end user simply uses a web mapping application (WebAppBuilder) to click on a Point of Arrival (POA) location. This selects a 5km Grid and looks up the distance for each Task Force POD from that 5km Grid centroid. The results are returned instantly.

![image](https://github.com/pjdohertygis/DeploymentOrderTool/assets/4256979/391c00da-f0ff-4b58-b391-1cf29b1843f6)



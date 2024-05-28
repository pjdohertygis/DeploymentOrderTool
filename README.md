# Deployment Order Tool (DOT)
This is a web mapping application used to find the nearest Urban Search and Rescue Team to an incident point of arrival. 

This application is currently used by FEMA US&R Branch staff to determine the closest Task Force based on trucking distance and/or travel time. It can be adapted for other purposes but the intended audience for the core application is the FEMA US&R Branch only. For more information on this project, contact the author. 

Deployment Order Tool 2.0 (requires username and password) https://experience.arcgis.com/experience/9c74a78957d24994af8536ce1015f197

![image](https://github.com/pjdohertygis/DeploymentOrderTool/assets/4256979/b378fa7b-0731-48a6-8c9b-1dd114741778)

# Backend - How Does It Work? 
To provide a simplified end user process with rapid results, we pre-calculated the truck-driving distance between 28 FEMA US&R Task Force Points of Departure (POD, static) and USNG 5km Grid Centroids. Then the end user simply uses a web mapping application (WebAppBuilder) to click on a Point of Arrival (POA) location. This selects a 5km Grid and looks up the distance for each Task Force POD from that 5km Grid centroid. The results are returned instantly.

![image](https://github.com/pjdohertygis/DeploymentOrderTool/assets/4256979/05f83501-90c7-41b4-849e-a4af7a510ee1)

See ArcGIS Pro Project with scripts, data, and documentation here: (COMING SOON)

These are powered by ArcGIS Pro Tasks and python scripts. 
![image](https://github.com/pjdohertygis/DeploymentOrderTool/assets/4256979/3512df6b-f809-4619-9db9-2fe66d4f6432)

![image](https://github.com/pjdohertygis/DeploymentOrderTool/assets/4256979/6ccddac6-f56d-4f1e-8ecf-82562aa2f375)


# Frontend - How Does It Work? 
Web Map https://www.arcgis.com/home/item.html?id=3f0ef15c7ca647c1a43ec47927c6684b

Web Mapping Application (Builder) [https://experience.arcgis.com/experience/9c74a78957d24994af8536ce1015f197
](https://experience.arcgis.com/builder/?id=9c74a78957d24994af8536ce1015f197)https://experience.arcgis.com/builder/?id=9c74a78957d24994af8536ce1015f197

See GitHub Wiki for documentation on how the layers, web maps, and apps are configured. https://github.com/pjdohertygis/DeploymentOrderTool/wiki


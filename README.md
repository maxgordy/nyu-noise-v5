# QGIS Instructions

1.    	Created new project.
2.    	Added Positron base layer via web -> QuickMapServices -> CartoDB -> Positron
3.    	Added 311 “calls” shapefile and NYU “residence_halls” shape file from GitHub to map.
4.    	Selected and removed attributes from “residence_halls” which were appearing as duplicates and / or were in Brooklyn.
5.    	Reprojected 311 “calls” shapefile into CRS 2263:
- Selected the Processing tab in the top menu bar -> toolbox 
- Selected Reproject Layer and new CRS 2263. Saved new reprojected layer as geojson then re-added to the map.
6.    	Created 250 ft. buffer around each NYU building and dissolved buffer.
7.    	Created intersection of 311 calls and NYU buildings. Saved as new layer.
8.    	Four layers were now:  Positron Base layer followed by 250 foot buffer, calls within buffer, and NYU residences.
9.    	Created heat map of new layer that showed intersecting calls.  
10.  Created new project layout. Added labels with addresses of each residence. Added inset map that showed broader Manhattan and Brooklyn with map area highlighted. Added key for residence halls and buffers. Added title and subtitle. Saved as PDF.
 

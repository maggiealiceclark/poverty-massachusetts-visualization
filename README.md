# poverty-massachusetts-visualization
Using ACS and Census data to explore poverty in Massachusetts in the style of Steven Chao, Michael Mann, Jordan Graesser, Nina Feldman's work from Python Open Source Spatial Programming & Remote Sensing.

Loaded from the U.S. Cenus Bureau API and accessed map shapefile from GeoPandas, performed data pre-processing to produce a cohesive dataset joined on the created GEOID column. Filtered to retrieve poverty rate data, calculated percentage poverty for each census tract, and plotted. Pulled table statistics: highest, lowest, and average. Regrouped census tracts by counties, aggregating tract values. 

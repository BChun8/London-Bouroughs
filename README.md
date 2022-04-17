# London-Bouroughs
In this dashboard, I worked with spatial data that pertained to London Boroughs. Spatial files helps us outline detailed outlines, marks, so that we can describe geographical features such as points, lines or polygons. Furthermore, I was aggregating the measures of the geometry measure and then I added Name column and SUM of Hectres to classify these different bouroughs.

DATA GATERING:
I pulled the spatial dataset from Tableau public site called CO2 Emissions by London Borough (2005-2014). Then, I joined the carbon-emissions-bourgh exel file by GSS code, through INNER JOIN. 

DATA VISUALIZATION:
I aggregate the measures of the geometry measure and then I added Name column and SUM of Hectres to classify these different bouroughs. Furthermore, I added the SUM of Hectres to further increase the color granualarity of the visualization. By doing the join, I was also able to illustrate the SUM of CO2 Emissions per capita. Then, I filtered the visualization by YEAR and then created an animation by shifting the YEAR Field by pages. This creates an animation for the relationship of CO2 emissions over a period of time by year. I also wanted to create increased granualarity by adding the Name onto Filters so that I can choose the exact borough to show the relationships of CO2 Emissions. 

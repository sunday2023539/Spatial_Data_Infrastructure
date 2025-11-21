**Trends in Employment Shifts over the years in Austria (TESST)**

This project, titled "Trends in Employment Shifts over the years in Austria" (TESST), analyzes Austrian employment shifts from 2019 to 2023. It leverages Spatial Data Infrastructure (SDI) principles to enhance data accessibility, interoperability, and visualization.

**Aim and Objectives**

The core aim is to analyze employment shifts using SDI to improve data accessibility, interoperability, and visualization.

**Key objectives include:**

Examining employment changes across different sectors, age groups, and genders.

Storing employment and geospatial data in a PostGIS geodatabase.

Processing the data using ArcGIS Pro and defining metadata.

Publishing the employment datasets as web services on the ArcGIS Enterprise Portal.

Developing an interactive dashboard to provide employment insights via maps, charts, and statistical summaries.

**Methodology and Architecture**

The study is conducted within an SDI framework, which ensures efficient management and interoperability of spatial data.

**Data Sources:** Employment data was acquired from AMS Statistics Austria, and state boundaries were downloaded from Data.gv.at.

**Data Storage:** Employment data was structured and stored in a PostGIS geodatabase.

**Processing and Analysis:** Data underwent cleaning, preprocessing, and transformation using SQL queries. Spatial joins were performed in ArcGIS Pro, linking employment statistics with regional boundaries.

**Data Publishing:** The processed dataset was published on the ArcGIS Enterprise Portal as interactive web services, including WMS, WFS, Feature Layers, and Image Layers.

**Key Findings (2019–2023)**

The analysis highlighted significant shifts in the Austrian labor market:

**Sectoral Shifts:** The job market shows a strong trend toward service-based jobs.

**Tertiary Sector (Services):** Saw the highest growth, adding 84.24%.

**Secondary Sector (Industry):** Experienced moderate growth at 7.98%.

**Primary Sector (Agriculture):** Saw minimal change at 7.78%.

**Gender:** There was a significant rise in female workforce participation.

**Female:** Accounted for 68.56% of new jobs.

**Male:** Accounted for 31.44% of new jobs.

**Age Group:** The 50-54 years category experienced the highest increase in jobs.

**Regional Trends:** Employment growth varied across states.

**Highest Growth:** Oberösterreich, Wien, and Steiermark.

**Lowest Growth:** Kärnten and Burgenland.

**Visualization:** An interactive dashboard was developed using ArcGIS Dashboard to visualize employment trends and workforce distribution.

**Conclusion**

This study successfully integrated employment and geospatial data within an SDI framework to provide a comprehensive understanding of labor market dynamics in Austria. The interactive dashboard is a valuable tool for policymakers and businesses, supporting data-driven decision-making for targeted employment policies and workforce development programs.



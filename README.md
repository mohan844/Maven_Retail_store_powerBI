# Maven_Retail_store_powerBI
Created a dynamic interactive dashboard involves multiple steps, from ETL (Extract, Transform, Load) to designing the dashboard itself using DAX functions. Here's a step-by-step guide on how to achieve this and then expand it into a GitHub repository:

Step 1: ETL Process
Extract Data: Obtain your data from various sources. In your case, you have 5 lookup tables and 2 data tables.

Transform Data: Clean, transform, and preprocess your data. Ensure that data types are consistent, and handle missing or duplicate values.

Load Data: Load the transformed data into your data model. You can use tools like Power BI or Excel Power Query to do this.

Step 2: Creating the Data Model
Create Relationships: Define relationships between the tables using proper keys. Make sure to create one-to-many or many-to-one relationships as needed.

Calculated Columns: Create calculated columns to enrich your data model. Use DAX functions like IF, SWITCH, etc., to create dynamic columns based on your requirements.

Step 3: Implementing DAX Functions
Aggregations: Utilize basic aggregation functions like SUM, AVERAGE, COUNT, MIN, MAX to summarize your data.

Filtering: Use DAX FILTER function to apply specific filters to your data, either in calculations or for display.

Time Intelligence: Utilize DAX functions like DATESYTD, DATESINPERIOD, DATESADD to perform time-based calculations. These are useful for creating dynamic date-based visuals.

Step 4: Creating the Interactive Dashboard
Slider and Bookmarks: Design a single-page dashboard that includes a slider. The slider can represent a date range or any other dynamic parameter. Use Power BI's bookmark feature to capture different states of your dashboard based on the slider's value.

Visualizations: Create various visualizations using the data model you've built. This can include charts, tables, maps, etc.

Utilize DAX Functions in Visuals: Apply DAX calculations to your visualizations. Use functions like CALCULATE, ALL, etc., to create interactive and context-aware visuals.

Dynamic Interaction: As users interact with the slider, the visuals should dynamically change based on the selected value.

# Published Link: https://app.powerbi.com/view?r=eyJrIjoiZDY3YjQ5OWItMGNiMC00NDVkLWJiNWUtMDNhZGUxZTUwOTNlIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9





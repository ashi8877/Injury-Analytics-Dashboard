# Injury-Analytics-Dashboard
This dashboard is created to analyse and visualize road accident data across different factors such as accident severity, vehicle type, road type, lighting condition, and area type (urban/rural). It helps in identifying patterns and supporting data-driven decision-making for road safety initiatives.

Road Accident Analysis Dashboard :-
Step-by-Step Structure to Build the Dashboard
________________________________________
PART 1: Primary KPIs Section
What we are making:
Visual blocks with key performance indicators (KPIs) to give a quick summary.
🔧 KPIs to Create:
1.	Total Casualties
2.	Fatal Casualties (Severe Deaths)
3.	Serious Casualties (Critical Injuries)
4.	Slight Casualties (Minor Injuries)
5.	Casualties by Cars

Visualizations:
•	Use number cards (big bold values)
•	Add donut charts (Data Labels ON, No Legends, % formatting)
•	Insert icons or shapes to visually represent each KPI
________________________________________
PART 2: Secondary KPIs – Casualties by Vehicle Type
What we are making: A summary of casualties grouped by type of vehicle.
🔧 Vehicle Groups:
•	Cars
•	Motorcycles
•	Buses
•	Trucks
•	Tractors
•	Others

Visualizations:
•	Use icon + label combinations (SmartArt or manual shapes)
•	Add small number cards below or beside each icon
•	Use shapes or images of vehicle types from Excel Icons or Insert → Pictures
PART 3: CY vs PY Casualty Trend (Monthly)
What we are making:
A line chart comparing current year (CY) vs previous year (PY) month-wise data.
Visualizations:
•	Use Line Chart
•	X-axis: Month names (Jan to Dec)
•	Y-axis: Casualty numbers
•	Use three series: one for 2020, one for 2021 & one for 2022
•	Add Data Labels and Legend
________________________________________
PART 4: Casualties by Road Type
What we are making: Compare accident counts across different road types.
Visualizations:
•	Use Horizontal Bar Chart
•	Categories: Single carriageway, Dual carriageway, Roundabout, One-way, Slip Road, etc.
•	Sort by descending order
________________________________________
PART 5: Casualties by Road Surface Condition
What we are making:
Show how many casualties occurred on dry, wet, or snow-covered roads.
Visualizations:
•	Use Tree Map or 100% Stacked Bar
•	Categories: Dry, Wet, Snow/Ice
________________________________________
PART 6: Urban vs Rural Casualties
What we are making:
Compare how many accidents happened in Urban vs Rural areas.
Visualizations:
•	Use Donut Chart
•	Two categories: Urban, Rural
•	Highlight with contrasting colors (e.g., brown vs light beige)

PART 7: Light Condition Analysis (Day vs Night)
What we are making:
Determine when most accidents happen — during daylight or darkness.
Visualizations:
•	Use Donut Chart
•	Categories: Daylight, Darkness
•	Show both count and percentage
________________________________________
PART 8: Filter Panel
What we are making:
Interactive panel to filter data based on:
1.	Urban or Rural
2.	Years (2020, 2021, 2022)
3.	Weather Conditions
Visualizations:
•	Use Slicers (Insert > Slicer from Pivot Table)
•	Style them with custom colors matching your theme
________________________________________
PART 9: Linked Image Navigation
What we are making:
Clickable icons that navigate to the dataset or pivot pages.
How to do it:
1.	Insert image or icon (Insert > Icons or Pictures)
2.	Right-click > Link > Place in this Document > Select Sheet (e.g., Dataset)
3.	Add a small hover effect using formatting
________________________________________
Data Setup Recommendation
•	Use Pivot Tables behind all visuals
•	Store raw data in one clean sheet (Road Accident Dataset)
•	Name your ranges or use Excel Tables
•	Use helper columns (e.g., Year, Month, Light, Road Type Group) for better analysis
________________________________________

Tools & Features Used:

Feature	Use Case
Pivot Tables	Aggregating accident data
Pivot Charts	Creating dynamic visuals
Donut Charts	For % comparison
Line Charts	Time-series (month) analysis
Bar Charts	Category-wise comparisons
Slicers	Interactive filtering
Shapes/Icons	Visual storytelling & linking
Conditional Formatting	For color indicators

 


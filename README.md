# Flight-Dashboard
Short Description
An interactive Power BI dashboard that visualizes flight booking trends, ticket pricing, and passenger behavior across airlines, cities, and travel classes. It exists to help stakeholders quickly identify revenue patterns, popular routes, and payment preferences to support data-driven decisions in the travel domain.

**Tool / Technology**                 **Purpose**
Power BI Desktop                  Dashboard design & interactive visualizations
Microsoft Excel/CSV               Raw data storage and preprocessing
Power Query(M Language)           Data cleaning, transformation & shaping
DAX(Data Analysis Expressions)    Custom KPI measures and calculated columns.

🗄️ **Data Source**
Source: Simulated/sample flight booking dataset (CSV / Excel flat file)
Origin: Kaggle-style structured dataset representing real-world airline booking transactions
Size: 250 booking records across 9 key fields
Format: Single flat table — no relational joins required.

⚙️ **How the Data Was Processed**

Imported raw file into Power BI via **Power Query Editor**
Checked and corrected **data types for** each column
Removed **nulls and duplicate records** to ensure data integrity
Created **DAX measures** for KPIs — SUM, AVERAGE, COUNT
Applied **age binning** on Passenger_Age for generational analysis
Added **Airline slicer** for dynamic, cross-visual filtering

✨ **Features & Highlights**
🔢 KPI Summary Cards (Top Row)
Six at-a-glance metrics give an instant health check of the dataset:

**250** total bookings tracked
**$644.6K** total ticket revenue generated
**45.60**average passenger age
**1.89M km** total distance covered across all flights
**11.04** hrs average flight duration
**$2.58K** average ticket price per booking

🎫 **Bookings by Travel Class (100% Stacked Bar)**
Shows distribution of 250 bookings across 4 cabin classes.

•Premium Economy is the most booked class with 69 bookings (81.2% share shown)
•First (63), Business (62), and Economy (56) follow closely
•Indicates passengers prefer comfort over budget in this dataset

# Lego-Sets-Categorization

<img width="2755" height="1470" alt="image" src="https://github.com/user-attachments/assets/9bb7dd47-4b9e-47a2-b77c-980a4a8c59cf" />
### 🧱 LEGO Sets Categorization and Analysis Dashboard
#### Project Overview
This repository documents and supports an interactive Power BI dashboard designed to categorize, analyze, and explore the vast world of LEGO sets. The primary goal of this project is to provide a comprehensive view of the LEGO catalog, allowing users to understand how sets are distributed across different themes, price points, piece counts, and years.
The dashboard functions as a dynamic catalog, enabling quick insights into product strategy, pricing trends, and product development over time.

Key Objective: To categorize and visualize the key attributes of LEGO sets to reveal product patterns and trends.

#### 📊 Dashboard 
The dashboard is designed for ease of use, featuring filter panes and clear key performance indicators (KPIs) to facilitate deep dives into specific product lines.

#### Key Features and Interaction
The dashboard highlights several key aspects of the LEGO set data:

##### 1. High-Level Metrics (KPI Cards)
1. Total Sets: The overall number of unique LEGO sets in the dataset.
2. Avg Pieces: The average number of pieces across all or filtered sets.
3. Avg Price: The average retail price (US_retailPrice) across all or filtered sets.

#### 2. Interactive Filtering and Slicers
1. Select Theme Group: Allows filtering by high-level grouping (e.g., Creator, Licensed, etc.).
2. Select Theme: Specific filtering for detailed themes (e.g., Star Wars, City, Batman).
3. Select Age Range: Filters sets by the recommended minimum age (agerange_min).
4. Max Price: A slider filter to dynamically adjust the maximum price point shown.

#### 3. Detailed Set List (Matrix/Table Visual) 
A drill-down table that lists individual sets and their key metrics (Name, Set ID, Theme, Age Range, Avg Price, Avg Pieces) based on the applied filters.

#### 4. Set Detail Card
A dedicated card that updates to show a detailed image and metrics (Year, Pieces, Age) for a single, selected set, giving an immediate, contextual view of the product.

#### 🛠️ Tools and Technologies
1. Primary Tool: Microsoft Power BI Desktop
2. Data Cleaning and Transformation : Power Query Editor
3. Analysis: Data Analysis Expressions (DAX) for calculating aggregates like Avg Pieces and handling currency formatting.

#### 🚀 How to Use
To explore the interactive dashboard:

1. Clone the Repository:
git clone [Your Repository URL]

2. Install Power BI Desktop: Ensure you have Power BI Desktop installed on your machine.

3. Open the File: Navigate to the cloned folder and open the Lego_Sets_Categorization.pbix

4. Interact: Use the slicers on the left (Theme Group, Theme, Age Range, Max Price) to filter the data and observe how the KPIs and the Set List change in real-time. Click on a row in the detailed Set List to update the specific information in the Set Detail Card on the right.

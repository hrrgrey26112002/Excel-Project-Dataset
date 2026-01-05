## Excel-Project-Dataset
This project focuses on analyzing bicycle buyer data to gain insights into the demographic factors influencing purchasing decisions. The dataset includes information such as ID, marital status, gender, income, number of children, education level, occupation, commute distance, region, age, and whether or not they purchased a bike.
## Workflow
The project is divided into three main phases to demonstrate a comprehensive data processing workflow:

# Phase 1: Data Cleaning & Preparation
- Deduplication: Removed duplicate records to ensure the integrity and accuracy of subsequent analyses.

- Data Standardization: Utilized the Find and Replace function to convert abbreviations (M, S, F) into full descriptive terms (Married, Single, Female, Male), making the data more intuitive for end-users.

- Feature Engineering: Created an "Age Brackets" column using Nested IF functions to categorize customers into groups: Adolescent, Middle-aged, and Senior. This transformation enhances visualization and makes trend tracking more effective than analyzing individual ages.

# Phase 2: Data Analysis with Pivot Tables
- Constructed Pivot Tables to extract key business insights:

Income: Compared the average income of males vs. females between buyers and non-buyers.
<img width="674" height="221" alt="{B1832F14-C8E0-4BA6-BA2F-46E0DD407D2F}" src="https://github.com/user-attachments/assets/794610ed-ec03-480d-b04e-dd0bbf7eb6c8" />

Commute Distance: Analyzed the impact of commuting distance on the decision to purchase a bike.
<img width="681" height="217" alt="{AEC0A921-AB24-4167-B0C6-58B78FF00621}" src="https://github.com/user-attachments/assets/d7168d2e-6fbb-4755-a37c-917c9eb94183" />

Age Groups: Identified the primary target customer segments based on age.
<img width="691" height="220" alt="{3BFDA509-E7F7-4671-BC0D-C8894C6C235A}" src="https://github.com/user-attachments/assets/2198d825-73e2-4c1a-bcf3-37632dfe31a3" />

# Phase 3: Interactive Dashboard Construction
- Visual Design: Cleaned the interface by removing gridlines, applying a consistent color palette, and aligning charts to create a professional look and feel.

- Interactivity: Integrated Slicers (Region, Education, Marital Status) and linked them across all visualizations via Report Connections, allowing users to filter and customize their view of the data dynamically.
<img width="403" height="274" alt="{A7994266-8A5C-43A8-83EC-4AD0E559D2FF}" src="https://github.com/user-attachments/assets/07e45a89-8655-4fa7-883f-33913fc2d6d9" />

## Results & Key Insights
- Identified the Middle-aged group (31-54 years old) as the segment with the highest bike purchase rate.

- Discovered a strong correlation between higher income levels and the likelihood of purchasing a bicycle.- 

- Developed a flexible reporting tool that enables rapid data filtering to support data-driven business decisions.

## Tools & Skills
- Tool: Microsoft Excel.

- Skills: Raw Data Processing, Logical Functions (Nested IF), Pivot Tables, Data Visualization (Bar Charts, Line Charts), Dashboard Design, Interactive Slicers.

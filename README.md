# Beauty Supply Chain Dynamics



## Problem Statement

Effective supply chain management is crucial for optimizing operations, reducing costs, and enhancing customer satisfaction. This project aims to analyze supply chain data to identify bottlenecks, streamline processes, and improve overall efficiency. By leveraging Power BI, the goal is to create a comprehensive dashboard that provides actionable insights to drive strategic decision-making in supply chain management.

### Steps followed 

- Step 1 : Import the supply chain dataset into Power BI Desktop from a CSV file.
- Step 2 : Data Cleaning and Transformation. Transformed product category names to ensure consistency (e.g., capitalizing the first letter).

- Step 3 : Created new measures to calculate average defect rates, average lead time and procurement cost.
           
           avg_defect_rates = AVERAGE(supply_chain_data[Defect rates])
           avg lead time = ROUND(AVERAGE(supply_chain_data[Lead time]),0)& " days"
           Procurement cost = SUM(supply_chain_data[Manufacturing costs]) + SUM(supply_chain_data[Shipping costs])
- Step 4 : Developed visualizations and organized them into three sections: Revenue, Production and Supply, and Shipping. 
- Step 5 : Combined visualizations into a cohesive and interactive dashboard.

 
 

# Snapshot of Dashboard 

![2024-07-21_21h30_08](https://github.com/user-attachments/assets/30c47eca-61a3-4b75-8fd4-58d5ea4e8248)

![2024-07-21_21h30_52](https://github.com/user-attachments/assets/f01d67d8-0781-4fca-ae23-1696b70c600f)

![2024-07-21_21h31_19](https://github.com/user-attachments/assets/10213d82-d4b7-48c3-a8a6-80b0acd76b9e)

![2024-07-21_21h31_42](https://github.com/user-attachments/assets/68141741-4816-4028-99cb-fe3e7dc226f6)

# Insights

Following inferences can be drawn from the dashboard;

### [1] Total Revenue and Sales

   Total revenue generated: 577.60k

   Total products sold: 46k
           
### [2] Lead Time and Defect Rates

Average lead time: 17 days

Average defect rate: 2.28%
  
 

 ### [3] Revenue Breakdown
 
Highest revenue generated in Mumbai.

Supplier 1 contributes the most to revenue.

Rail is the most profitable transportation mode.
 
 ### [4] Production and Supply Analysis
 
 Bangalore incurs the highest manufacturing costs, while Mumbai has the lowest.

 Supplier 1 also has the highest order quantities.

 Supplier 5 has the highest defect rates and manufacturing lead time.
### [5] Shipping Analysis

Kolkata is the costliest location for shipping.

Route B handles the highest order quantities.

Carrier A has the highest defect rates.

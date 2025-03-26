# *TOPIC:Pizza Hut Sales vs Waste*

This analysis for a job interview as Data Analyst Role in FSC Group. 
---

### **Data Understanding Questions**
1. **What is the main objective of this analysis?**  
2. **What type of data am I working with?** 
3. **Are there any missing values or data inconsistencies that need cleaning?**  
4. **What is the overall distribution of my data?**  
5. **Are there any potential outliers that could distort my analysis?**  
6. **What key metrics should I focus on?** 
7. **Are there any seasonal trends or cyclical patterns?**  
8. **Which data segments are important to highlight?**  
9. **What relationships between variables should I explore?**  
10. **Which visualization type best represents this data?**  
11. **What key insights should the audience take away from this visual?**  

### Download Excel (Dataset) Here
- <a href="https://github.com/Harizaqil1/PizzaHutSalesvsWaste/blob/main/Pizza_Hut_Dataset.xlsx">Dataset</a>


- Dashboard Interaction - <a href="https://github.com/Harizaqil1/PizzaHutSalesvsWaste/blob/main/image013.png">View Dashboard</a>


---

## **Methodology**
1. **Reading & Understanding the Dataset**  
   ➔ Identifying dataset, tables (row & column) and sheets.
![2](https://github.com/user-attachments/assets/6f985a22-b915-4b40-bdf6-ab4844eac9bb)

From here we can identify key variables, and clean the dataset.

2. **Cleaning the Dataset**
   ➔ Ensure every column in their correct data type (example: Cost is numerical and Location is Text or String).
   ➔ Using **=Countblank()** to identify is there any NA or missing values.
   ➔ Some values often duplicate or wrong format such as Date.
   ➔ Then, we identify is there any outliers or dominant data, depends on each dataset, we must make sure if we            remove outliers "it is will affect the overall analysis such as biased data ?"
   
4. **Visualization**
   ➔ In this analysis I used Power Pivot & Data Model, Slicer and Timeline.
   ➔ I plotted into several chart and connecting slicers & timeline to every chart.
   ➔ From here, I can compare between each category versus cost or waste or sales.


---


## Dashboard

![image013](https://github.com/user-attachments/assets/ea79a498-6dc9-492e-8f84-6ce418bceac6)

### Analysis
1. Trend Analysis

   1. **Sales Trends by Date**
   ![image009](https://github.com/user-attachments/assets/36483d2d-970a-4eea-8418-edcd1e846738)
   The date filter indicates Q2 2024 data is selected.
   There’s flexibility to explore data from 2023 to 2025, suggesting trend analysis across multiple periods is          possible.
   To understand seasonality or major sales peaks, exploring quarterly trends could reveal valuable insights.
   
   2. **Sales vs Cost**
   ![image007](https://github.com/user-attachments/assets/7f8046b4-342e-4eb6-8e31-436241afba2b)
   The scatter plot shows a positive correlation between sales and cost.
   The red dotted line indicates a possible non-linear relationship, where higher costs may yield diminishing           returns.
   Outliers on the upper end of costs may suggest potential inefficiencies or overspending.

   3. **Sales by Food Category vs Age Group**
   ![image006](https://github.com/user-attachments/assets/809a02d1-8109-4237-bebf-11229718a4d7)
   Adults (20-59) are the biggest contributors across multiple food categories.
   Desserts and Main Course are strong performers.
   Sales for Snacks are lower across all age groups.
   
   4. **Geographic Sales Distribution**
   ![image010](https://github.com/user-attachments/assets/c25ce7be-de7b-48b6-b496-3c27e8bd4efc)
   The heatmap shows that West Malaysia regions are driving the majority of sales, particularly in Johor, Kuala         Lumpur, and Selangor.
   East Malaysia appears to have minimal or no data, indicating low presence or weak sales in that region.
   
   5. **Sales Breakdown by State**
   ![image011](https://github.com/user-attachments/assets/7b629808-aa97-45b8-bc25-7662cddb151b)
   Perak stands out with the highest sales, followed closely by Kuala Lumpur and Johor.
   All states show consistent levels of sales, with no extreme outliers.
   
   6. **Sales vs Waste Analysis**
   ![image008](https://github.com/user-attachments/assets/03a5b221-10cb-4caf-a317-0f02e4d1494c)
   Beverages and Desserts generate the highest sales but also show higher waste levels.
   The correlation between sales and waste appears consistent across most categories, except for Main Course, which     shows a dip in waste despite good sales performance.
   

3. Challenges
   ➔ Data Cleaning:
         Often missing values & outliers
         Either to subtitute the data or remove.
         Biased
         Numerical value instead of Categorical (Location)

   ➔ Visualisation:
         New tools (Data Type)
         Unaffective chart such as pie chart
         Too much data to show.
         New chart (map chart)


   ➔ Pre & Post Analysis:
         Not understanding the data, tables and sheets.
         Biased analysis due to personal preferences.


---

## Conclusion
The Pizza Hut performance dashboard reveals key insights into sales trends, customer demographics, and regional performance. The data indicates that:
✅ Desserts and Main Course are top-performing food categories, primarily driven by the Adult (20-59) age group.
✅ Snacks are underperforming, suggesting potential growth opportunities through targeted marketing or product bundling.
✅ Geographically, Perak, Kuala Lumpur, and Johor lead in sales, while Kedah and Malacca show room for improvement.
✅ Sales correlate positively with costs, but certain high-cost instances may signal inefficiencies requiring further investigation.
✅ Waste levels are concerning in Desserts and Beverages, warranting improved inventory control or production planning.

### Final Recommendation
   ➔ To enhance Pizza Hut's performance, strategies should focus on:
   ➔ Expanding marketing efforts for Snacks.
   ➔ Strengthening sales in regions like Kedah and Malacca.
   ➔ Implementing better waste control strategies in high-waste categories.
   ➔ Optimizing cost management to ensure improved profitability.


   

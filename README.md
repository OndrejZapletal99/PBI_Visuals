# PBI_Visuals
PBI Visuals

- ## Content
    - [1. Pareto - Visual Calculations](#1-pareto---visual-calculations)
    - [2. Column Diff](#2-column-diff)
    - [3. Scatter Plot Quadrant Analysis](#3-scatter-plot-quadrant-analysis)

## 1. Pareto - Visual Calculations

[**PBIX File Download**](https://github.com/OndrejZapletal99/PBI_Visuals/blob/main/Pareto/Pareto.pbix)

![Pareto final](https://github.com/OndrejZapletal99/PBI_Visuals/blob/main/Pareto/Pareto_finished.png)

1. **Create** a Line and Stacked Column Chart.  
2. **Add** your preferred KPI (**COGS**) to the **Y-axis**.  
3. **Add** your preferred dimension to the **X-axis**.  
4. **Sort** the chart in **descending order** based on the KPI.  
5. **Click** on **"New Visual Calculation"** and select **Custom**.  
   ![New Visual Calculation](https://github.com/OndrejZapletal99/PBI_Visuals/blob/main/Pareto/Pareto_select_vis_cal.png)  
6. **Create** a new visual calculation called **"Share of Total"** and **hide it**.
   ![Share of total](https://github.com/OndrejZapletal99/PBI_Visuals/blob/main/Pareto/Pareto_share_of_total_vis_cal.png)   
7. **Create** a new visual calculation called **"Pareto"**.  
   ![Pareto](https://github.com/OndrejZapletal99/PBI_Visuals/blob/main/Pareto/Pareto_pareto_vis_cal.png)  
8. **Create** a new visual calculation called **"Pareto Shade Area"** and **hide it**.  
   ![Pareto Shade Area](https://github.com/OndrejZapletal99/PBI_Visuals/blob/main/Pareto/Pareto_shade_vis_cal.png)  
9.  **Go to** the **Format settings**, locate **"Shade Area"**, and **turn it off for Pareto**.  
   ![Pareto Shade Area Format](https://github.com/OndrejZapletal99/PBI_Visuals/blob/main/Pareto/Pareto_shade_area_color.png)  
10. **Apply** your preferred formatting.  
11. *(Optional)* **Enhance** the visualization by adding **Dynamic Dimensions** or a **Dynamic Pareto Parameter**.  

## 2. Column Diff

[**PBIX File Download**](https://github.com/OndrejZapletal99/PBI_Visuals/blob/main/Column%20Diff/Column%20Diff.pbix)

![Column Diff Example](https://github.com/OndrejZapletal99/PBI_Visuals/blob/main/Column%20Diff/Column_diff.png)

The **Column Diff** visual is designed to help you easily compare values between two columns or categories. This is useful for highlighting differences, changes, or trends between two data points in your dataset.

**How to use Column Diff:**
1. **Open** the provided PBIX file or add the visual to your report.
2. **Assign** the columns or measures you want to compare to the appropriate fields in the visual.
3. **Customize** the formatting and colors to match your report style.
4. **Interpret** the visual to quickly spot increases, decreases, or unchanged values between the compared columns.

This visual is ideal for before/after analyses, year-over-year comparisons, or any scenario where you need to highlight the difference between two values in a clear and visual way.

## 3. Scatter Plot Quadrant Analysis

This section describes how to create a scatter plot in Power BI that segments your data into quadrants based on customizable margin and sales parameters. This approach allows you to easily identify products or product categories with high sales and high margins, as well as other combinations (e.g., high sales/low margin, low sales/high margin, low sales/low margin).

### Steps to Create a Scatter Plot with Quadrants in Power BI

1. **Prepare your data**  
   Ensure your dataset contains at least the following fields:  
   - Product or Product Category  
   - Sales  
   - Margin (as a percentage or value)

2. **Add a Scatter Plot Visual**  
   - Insert a scatter plot visual into your Power BI report.
   - Assign the appropriate fields to the X-axis (Sales), Y-axis (Margin), and Details (Product/Product Category).

3. **Create Margin and Sales Parameters**  
   - Use Power BI's "What-if Parameter" feature to create dynamic parameters for Margin and Sales thresholds.
   - These parameters will be used to define the quadrant boundaries.

4. **Add Quadrant Calculation**  
   - Create a calculated column in visual calculations to assign each data point to a quadrant based on the selected parameter values:
     - High Margin & High Sales
     - High Margin & Low Sales
     - Low Margin & High Sales
     - Low Margin & Low Sales

5. **Format the Scatter Plot**  
   - Use reference lines and shade areas.

6. **Interpret the Results**  
   - Use the scatter plot to quickly identify which products or categories fall into each quadrant.
   - Focus on the "High Margin & High Sales" quadrant for top performers, and analyze other quadrants for improvement opportunities.

### Example

*Add your scatter plot screenshot here:*

![Scatter Plot Quadrant Example](https://github.com/OndrejZapletal99/PBI_Visuals/blob/main/Scatter%20Quadrant/Scatter_Quadrant.png)

---

This visual approach is ideal for portfolio analysis, product performance reviews, and strategic decision-making, enabling you to focus on the most valuable segments of your business.
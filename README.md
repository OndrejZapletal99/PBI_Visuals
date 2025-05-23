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

Want to quickly see which products or categories are your best?  
Use a scatter plot with quadrants in Power BI! Just set your own margin and sales limits (parameters) and see everything at a glance.

### How to do it

1. **Get your data ready**  
   You need:  
   - Product or Product Category  
   - Sales  
   - Margin (% or value)

2. **Add a scatter plot**  
   - Put Sales on X-axis  
   - Margin on Y-axis  
   - Product or Category as Details

3. **Create parameters**  
   - Use "What-if Parameter" in Power BI for Margin and Sales  
   - These set your quadrant lines

4. **Add quadrant logic**  
   - Make a calculated column or measure to say if each point is:  
     - High Margin & High Sales  
     - High Margin & Low Sales  
     - Low Margin & High Sales  
     - Low Margin & Low Sales

5. **Format your plot**  
   - Add reference lines for your parameters  
   - Color by quadrant

6. **Read your results**  
   - Top right = best (high margin, high sales)  
   - Bottom left = needs work  
   - Super easy to spot trends!

### Example

*Add your scatter plot screenshot here:*

![Scatter Plot Quadrant Example](https://github.com/OndrejZapletal99/PBI_Visuals/blob/main/Scatter%20Quadrant/Scatter_Quadrant.png)

---

You can use this for products, customers, projects—anything!  
Just change the fields and parameters.  
Easy, visual, and fast.
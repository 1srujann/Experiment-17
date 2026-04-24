# Experiment 17: Statistical and Specialized Data Visualization Techniques

---

## Title

Exploration of Statistical and Advanced Data Visualization Techniques using Matplotlib and Seaborn

---

## Aim

To study and implement statistical and specialized data visualization techniques for better data analysis and interpretation.

---

## Objectives

- To understand advanced visualization techniques  
- To create area and pie charts for representation  
- To visualize data distribution using boxplots and histograms  
- To analyze relationships using correlation heatmaps  
- To represent multi-variable data using bubble plots  
- To utilize Seaborn for enhanced statistical visualization  

---

## Theory

Data visualization helps in understanding patterns, trends, and relationships within data.

Advanced visualization techniques provide deeper insights compared to basic charts.

Python libraries used:

- **Matplotlib:** Used for creating basic and customizable plots  
- **Seaborn:** Built on Matplotlib, provides better statistical graphics  

Common plots used in this experiment:

- **Area Plot:** Represents quantitative data over categories  
- **Pie/Donut Chart:** Shows proportional distribution  
- **Box Plot:** Identifies spread and outliers  
- **Histogram:** Displays frequency distribution  
- **Heatmap:** Shows correlation between variables  
- **Bubble Plot:** Represents 3 variables (x, y, size/color)  

---

## Datasets Used

### 1. Category Dataset
- Columns: Category, Values, Sales, Profit  
- Used for area plot, pie chart, donut chart, boxplot, heatmap, and bubble plot  

### 2. Customer Dataset
- Columns: Customer_ID, Age, Income, Loan_Amount, Credit_Score, Loan_Status  
- Used for histogram, boxplot, bubble plot, and correlation heatmap  

---

## Problem Statements

### 1. Area Plot

Plot values across categories using an area chart.

**Concepts Used:** plt.fill_between()

---

### 2. Pie Chart

Display percentage contribution of each category.

**Concepts Used:** plt.pie()

---

### 3. Donut Chart

Create a pie chart with a hollow center.

**Concepts Used:** plt.pie(), plt.Circle()

---

### 4. Box Plot (Outlier Detection)

Analyze distribution and detect outliers in values.

**Concepts Used:** sns.boxplot()

---

### 5. Correlation Heatmap

Show relationship between numerical variables.

**Concepts Used:** DataFrame.corr(), sns.heatmap()

---

### 6. Bubble Plot

Visualize Sales vs Profit with bubble size representing Values.

**Concepts Used:** plt.scatter(), sns.scatterplot()

---

### 7. Box Plot (Loan Dataset)

Analyze loan amount distribution.

**Concepts Used:** plt.boxplot()

---

### 8. Histogram

Display distribution of credit scores.

**Concepts Used:** plt.hist()

---

### 9. Advanced Bubble Plot

Visualize Income vs Loan Amount with Credit Score as size and color.

**Concepts Used:** plt.scatter(), color mapping (cmap), alpha

---

### 10. Correlation Heatmap (Customer Dataset)

Analyze relationships between Age, Income, Loan Amount, and Credit Score.

**Concepts Used:** sns.heatmap()

---

## Error Observed

While creating heatmaps or scatter plots, possible issues:

```python
ValueError: could not interpret value
```

**Reason:**
- Incorrect column name or missing data

**Solution:**
- Ensure correct column names
- Verify dataset before plotting

---

## Result

Successfully implemented various statistical and advanced visualization techniques using Matplotlib and Seaborn.

---

## Conclusion

This experiment helped in understanding how advanced visualizations like heatmaps, boxplots, and bubble plots provide deeper insights into data. Choosing the right visualization technique improves data interpretation and analysis.

---

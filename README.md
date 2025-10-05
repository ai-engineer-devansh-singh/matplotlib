# Matplotlib Data Visualization Tutorial

A comprehensive guide to data visualization using matplotlib, covering everything from basic plots to advanced multivariate analysis.

## 📊 Overview

This notebook demonstrates various data visualization techniques using matplotlib and pandas, progressing from simple univariate analysis to complex multivariate visualizations. The tutorial includes practical examples using simulated employee data and business metrics.

## 🎯 Learning Objectives

- Master matplotlib's pyplot API for quick data exploration
- Understand when to use different types of visualizations
- Learn to analyze univariate, bivariate, and multivariate data
- Compare matplotlib's object-oriented vs. pyplot interfaces
- Create publication-ready plots with proper styling

## 📋 Table of Contents

### 1. **Data Setup & Basic Plotting**
- Essential library imports (matplotlib, numpy, pandas)
- Basic line plots for showing relationships
- Grid usage for better readability

### 2. **Univariate Numerical Analysis**
- **Histograms**: Frequency distribution visualization
- **Box Plots**: Quartiles, median, and outlier detection
- Understanding data spread and central tendency

### 3. **Univariate Categorical Analysis**
- **Pie Charts**: Proportional data representation
- **Bar Charts**: Categorical frequency comparison
- When to use each visualization type

### 4. **Bivariate Analysis**

#### Numerical vs Numerical
- **Scatter Plots**: Correlation and pattern identification
- **Line Plots**: Trend analysis (importance of data sorting)
- **Bar Charts**: Individual value comparison

#### Numerical vs Categorical
- **Side-by-side Box Plots**: Distribution comparison across groups
- **Grouped Bar Charts**: Average value comparison
- **Pie Charts**: Aggregated data visualization

### 5. **Multivariate Analysis**
- **Bubble Plots**: 3+ variable visualization using size encoding
- **Color-coded Scatter Plots**: 4+ variable analysis
- **3D Plotting**: Spatial relationship visualization

### 6. **Advanced Techniques**
- **Object-Oriented API**: Better control for complex plots
- **Subplots**: Multiple visualizations in one figure
- **Interactive Plots**: Using Plotly for enhanced exploration

## 🔧 Technologies Used

- **matplotlib**: Primary plotting library
- **pandas**: Data manipulation and analysis
- **numpy**: Numerical computing support
- **plotly**: Interactive 3D visualizations

## 📊 Dataset Description

The tutorial uses two main datasets:

### Employee Dataset
- **Salary**: Employee compensation (1000-15000)
- **Years of Experience**: Work experience (1-20 years, includes outlier)
- **Age**: Employee age (22-40 years)
- **Department**: HR or IT classification

### Business Metrics Dataset
- **Years**: Time series data (2010-2020)
- **Sales**: Revenue figures over time
- **Profit**: Profit margins over time
- **Expenses**: Cost analysis over time

## 🎨 Visualization Types Covered

| Plot Type | Use Case | Variables |
|-----------|----------|-----------|
| Line Plot | Trends over time/continuous data | 2 numerical |
| Histogram | Distribution analysis | 1 numerical |
| Box Plot | Quartiles and outliers | 1 numerical |
| Pie Chart | Proportional data | 1 categorical |
| Bar Chart | Category comparison | 1 categorical + counts |
| Scatter Plot | Correlation analysis | 2 numerical |
| Bubble Plot | Multi-dimensional data | 3+ numerical |
| 3D Plot | Spatial relationships | 3 numerical |

## 🚀 Key Features

### Comprehensive Comments
- Every code cell includes detailed explanations
- Purpose and use case for each visualization
- Parameter explanations for better understanding

### Progressive Complexity
- Starts with basic concepts
- Gradually introduces advanced techniques
- Builds upon previous examples

### Practical Examples
- Real-world data scenarios
- Business-relevant use cases
- Best practices demonstrated

### Multiple Approaches
- pyplot API for quick exploration
- Object-oriented API for production code
- Interactive alternatives with Plotly

## 📈 Best Practices Demonstrated

1. **Choose the Right Plot Type**
   - Histograms for distributions
   - Scatter plots for correlations
   - Box plots for group comparisons

2. **Enhance Readability**
   - Clear titles and axis labels
   - Appropriate color schemes
   - Grid lines for value estimation

3. **Handle Multiple Variables**
   - Size encoding for additional dimensions
   - Color coding for categorical separation
   - Subplots for comprehensive analysis

4. **Professional Styling**
   - Consistent color palettes
   - Proper legends and annotations
   - Export-ready formatting

## 🔍 Code Structure

```python
# Standard imports
import matplotlib.pyplot as plt
import pandas as pd
import numpy as np

# Data preparation
data = {...}
df = pd.DataFrame(data)

# Visualization with explanatory comments
plt.plot(x, y, ...)  # Purpose and parameters explained
plt.title('...')     # Clear, descriptive titles
plt.show()          # Display the plot
```

## 📁 Files Included

- `matplotlib.ipynb`: Main tutorial notebook with comprehensive examples
- `matplotlib_summary.png`: Generated subplot summary image
- `README.md`: This documentation file

## 🎓 Learning Path

1. **Beginners**: Start with univariate analysis (sections 1-3)
2. **Intermediate**: Focus on bivariate analysis (section 4)
3. **Advanced**: Explore multivariate techniques (sections 5-6)

## 💡 Tips for Success

- Run cells sequentially to maintain data consistency
- Experiment with different parameters to see their effects
- Try applying techniques to your own datasets
- Pay attention to when each visualization type is most appropriate

## 🔧 Setup Requirements

```python
pip install matplotlib pandas numpy plotly
```

## 📝 Usage Notes

- The notebook includes intentional outliers for demonstration
- Comments explain both the 'what' and 'why' of each visualization
- Interactive plots (Plotly) work best in Jupyter environments
- Object-oriented examples show production-ready coding practices

## 🎯 Next Steps

After completing this tutorial, consider exploring:
- Seaborn for statistical visualizations
- Plotly Dash for interactive web applications
- Advanced matplotlib customization
- Publication-quality figure formatting

---

*This tutorial provides a solid foundation for data visualization in Python, preparing you for real-world data analysis and presentation tasks.*
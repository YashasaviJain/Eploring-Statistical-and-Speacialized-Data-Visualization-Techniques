# 📊 Experiment 18 – Statistical and Specialized Data Visualization

## 🧪 Aim
The aim of this experiment is to explore and understand various **statistical and specialized data visualization techniques** using Python libraries. The objective is to represent data in different graphical formats to analyze patterns, relationships, distributions, and correlations effectively.

---

## 📘 Theory

Data visualization is a key component of data analysis that allows users to interpret complex datasets visually. This experiment uses libraries like **Matplotlib**, **Seaborn**, **Pandas**, and **NumPy** to generate different types of plots.

### Key Visualization Techniques Used:

1. **Area Plot**
   - Represents quantitative data over categories.
   - Helps visualize trends and magnitude.

2. **Pie Chart**
   - Displays proportions of categories.
   - Useful for percentage-based representation.

3. **Donut Chart**
   - A variation of the pie chart with a hollow center.
   - Improves readability and aesthetics.

4. **Box Plot**
   - Shows distribution of data.
   - Highlights median, quartiles, and outliers.

5. **Heatmap**
   - Represents correlation between variables.
   - Uses color intensity to indicate relationship strength.

6. **Bubble Plot**
   - A scatter plot with an additional variable represented by bubble size.
   - Useful for multi-dimensional analysis.

7. **Correlation Analysis**
   - Helps identify relationships between numerical variables.
   - Important for predictive modeling.

---

## ⚙️ Algorithm

1. Import required libraries: Matplotlib, Seaborn, Pandas, NumPy.
2. Set random seed for reproducibility.
3. Create a dataset using Pandas DataFrame.
4. Display dataset for verification.
5. Generate Area Plot using fill_between().
6. Apply Seaborn styling and plot overlapping area charts.
7. Create Pie Chart to show category proportions.
8. Convert Pie Chart into Donut Chart using a central circle.
9. Generate Box Plot to detect outliers in data.
10. Compute correlation matrix using `.corr()` method.
11. Visualize correlation using Heatmap.
12. Create Bubble Plot using scatter plot with size parameter.
13. Generate enhanced Bubble Plot using Seaborn.
14. Create a second dataset with customer-related features.
15. Add a new column using conditional logic (Loan Status).
16. Display sample data for analysis.

---

## 🛠️ Commands Used and Their Features

### 📦 Libraries
- `matplotlib.pyplot`
  - Used for basic plotting and visualization.
  - Provides functions like `figure()`, `plot()`, `show()`.

- `seaborn`
  - Built on Matplotlib.
  - Provides advanced and aesthetically pleasing plots.
  - Includes built-in themes and color palettes.

- `pandas`
  - Used for data manipulation and analysis.
  - Provides DataFrame structure for tabular data.

- `numpy`
  - Used for numerical operations and random data generation.

---

### 🔧 Functions and Methods

- `np.random.seed()`
  - Ensures reproducibility of random data.

- `pd.DataFrame()`
  - Creates structured datasets in tabular form.

- `plt.figure()`
  - Initializes a new plotting figure.

- `plt.fill_between()`
  - Creates area plots between x and y values.

- `sns.set_style()`
  - Applies visual themes like grids and backgrounds.

- `plt.pie()`
  - Generates pie charts with percentage labels.

- `plt.Circle()`
  - Draws a circle (used to create donut charts).

- `sns.boxplot()`
  - Displays distribution and identifies outliers.

- `DataFrame.corr()`
  - Computes correlation between numerical columns.

- `sns.heatmap()`
  - Visualizes correlation matrix using colors.

- `plt.scatter()`
  - Creates scatter plots (used for bubble plots).

- `sns.scatterplot()`
  - Advanced scatter plot with size and color encoding.

- `np.random.randint()`
  - Generates random integer values within a range.

- `np.where()`
  - Applies conditional logic to create new columns.

---

## ✅ Conclusion

This experiment successfully demonstrates the use of various **data visualization techniques** to analyze datasets effectively. By using multiple types of plots, we can:

- Identify trends and patterns in data.
- Detect outliers and anomalies.
- Understand relationships between variables.
- Represent multi-dimensional data visually.

The use of libraries like Matplotlib and Seaborn enhances the clarity and presentation of data. Overall, visualization plays a crucial role in transforming raw data into meaningful insights, making it easier for decision-making and analysis.

---

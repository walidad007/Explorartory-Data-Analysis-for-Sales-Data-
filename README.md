
# Sales Data Analysis

This project involves a comprehensive Exploratory Data Analysis (EDA) on a sales dataset. The objective is to uncover insights and patterns in the data that can inform business decisions. The dataset contains information about orders, products, sales, and other relevant details.


### Dataset

The dataset used in this analysis contains the following columns:

* Order ID
* Product Category
* Product
* Quantity Ordered
* Price Each
* Order Date
* Purchase Address
* Month
* Sales
* City
* Hour
* Time of Day


### Data Cleaning

**Steps Taken:**

1. Loading Data: The dataset is loaded using pandas.

2. Initial Inspection: Viewing the first few rows, shape, and data types to understand the structure of the dataset.

3. Handling Missing Values: Visualized missing values using a heatmap and identified the number of missing values per column.

4. Removing Duplicates: Identified and handled duplicate entries by grouping them and aggregating relevant columns.

5. Data Type Conversion: Converted Order Date to datetime format.

## Exploratory Data Analysis (EDA)

### Univariate Analysis

* **Descriptive Statistics:** Summary statistics for numerical columns.

* **Distribution Plots:** Histograms for numerical columns to understand their distribution.

* **Count Plots:** For categorical columns to see the frequency distribution of each category.

### Bivariate Analysis

* **Correlation Matrix:** Heatmap to visualize the correlation between numerical features.

* **Scatter Plots:** To examine relationships between pairs of numerical columns.

* **Box Plots:** To visualize the distribution of numerical columns across different categories.

### Multivariate Analysis

* **Pair Plot:** Colored by a categorical column to observe interactions between numerical features.

* **FacetGrid:** To visualize conditional distributions across multiple categories.

* **Heatmap:** Showing the interaction between multiple features such as sales distribution across products and cities.


### Key Insights

* **Sales Distribution:** Identified how sales are distributed across different products and cities.

* **High and Low Performing Segments:** Determined which products perform well in which cities.

* **Comparative Analysis:** Enabled comparisons between products within cities and across different cities.

* **Patterns and Trends:** Uncovered regional preferences and trends over time.


## Visualizations

The following visualizations were created to support the analysis:

1. **Heatmap for Missing Values:** To identify and visualize missing data.

2. **Distribution Plots:** For numerical features like 'Quantity Ordered', 'Price Each', 'Sales', 'Month', and 'Hour'.

3. **Count Plots:** For categorical features like 'Product Category', 'Product', 'City', and 'Time of Day'.

4. **Correlation Heatmap:** To show correlations between numerical features.

5. **Pair Plot:** To visualize relationships between pairs of numerical features with a categorical hue.

6. **FacetGrid:** To show conditional distributions of 'Sales' across 'Product Category' and 'Time of Day'.

7. **Heatmap of Sales by Product and City:** To visualize the interaction between sales, products, and cities.

### Conclusion

This EDA provides valuable insights into the sales data, helping to understand the distribution and relationships between various features. These insights can be used to make data-driven decisions and strategies.



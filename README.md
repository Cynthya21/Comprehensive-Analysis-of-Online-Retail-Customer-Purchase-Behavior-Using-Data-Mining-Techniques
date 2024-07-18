# Comprehensive-Analysis-of-Online-Retail-Customer-Purchase-Behavior-Using-Data-Mining-Techniques
# Comprehensive Analysis of Online Retail Customer Purchase Behavior Using Data Mining Techniques

## What is it?

This project focuses on analyzing online retail customer purchase behavior using data mining techniques. The process involves leveraging Association Rule Mining (ARM) and Clustering within the R Studio environment to uncover patterns in customer purchases. The goal is to identify products that are frequently bought together and segment customers based on their buying habits, enabling personalized shopping experiences and optimized inventory management.

## Files

- **Comprehensive Analysis of Online Retail Customer Purchase Behavior Using Data Mining Techniques.docx**: The report detailing the analysis and findings.
- **Online Retail.xlsx**: The dataset used for the analysis.

## Key Features

### Data Exploration

- **Summary Statistics**: Detailed examination of the dataset to uncover patterns and insights.
- **Visualization**: Graphical representation of data to highlight important trends and relationships.

### Data Mining Techniques

- **Association Rule Mining (ARM)**: Using the Apriori algorithm to identify patterns of items frequently purchased together, which informs cross-selling strategies and inventory management.
- **Clustering**: Segmenting customers into groups based on their purchasing behavior to guide targeted marketing initiatives.

## Dataset Details

The dataset, 'Online Retail', contains transactional data from an e-commerce platform, including nominal, numeric, and temporal data points. Key variables include:

- **InvoiceNo**: Invoice number
- **StockCode**: Product (item) code
- **Description**: Product (item) name
- **Quantity**: The quantities of each product (item) per transaction
- **InvoiceDate**: Invoice date and time
- **UnitPrice**: Unit price
- **CustomerID**: Customer number
- **Country**: Country name

## Visualization Insights

- **Purchase Patterns**: Identification of frequently co-purchased items.
- **Customer Segmentation**: Clustering customers based on purchase volume and frequency.

## Data Mining Techniques Details

- **Association Rule Mining (ARM)**: Utilized the 'arules' package in R Studio for ARM, identifying significant associations between products.
- **Clustering**: Applied the 'cluster' package in R Studio to segment customers into distinct groups.

### ARM Visualization

- **Support**: Proportion of transactions that include the item set.
- **Confidence**: Frequency of item Y being bought with item X.
- **Lift**: Strength of a rule, indicating positive or negative associations.

### Clustering Visualization

- **Elbow Method**: Used to determine the optimal number of clusters.
- **Scatter Plot**: Analysis of customer segments based on total spending and total quantity of purchases.

## Applications and Insights

- **Retail Strategy**: Enhanced customer experiences through personalized recommendations and promotions.
- **Inventory Management**: Improved product placement and cross-selling strategies.
- **Marketing Initiatives**: Tailored campaigns based on customer segmentation.


# Customer Segmentation using K-Means Clustering

## Project Overview

This project focuses on **customer segmentation**, which involves grouping customers into distinct clusters based on similarities in their annual income and spending score. By identifying these customer groups, businesses can tailor marketing strategies and improve customer satisfaction. In this case, we use the **K-Means Clustering** algorithm, a popular unsupervised learning technique, to classify customers into different clusters based on their purchasing behavior.

## Dataset

The dataset used in this project is the **Mall_Customers.csv** file, which contains the following features:

- **CustomerID**: Unique customer identification number
- **Gender**: Gender of the customer
- **Age**: Age of the customer
- **Annual Income (k$)**: Annual income of the customer in thousands of dollars
- **Spending Score (1-100)**: Customer's spending score, where a score closer to 100 indicates more spending

### Sample Data

| CustomerID | Gender | Age | Annual Income (k$) | Spending Score (1-100) |
|------------|--------|-----|--------------------|------------------------|
| 1          | Male   | 19  | 15                 | 39                     |
| 2          | Female | 21  | 15                 | 81                     |
| 3          | Female | 20  | 16                 | 6                      |
| 4          | Male   | 23  | 16                 | 77                     |
| ...        | ...    | ... | ...                | ...                    |

## Project Workflow

1. **Data Preprocessing**: 
    - The data is loaded and cleaned for missing values.
    - The dataset is then analyzed to extract useful insights.
   
2. **Feature Selection**:
    - We select the **Annual Income** and **Spending Score** columns for clustering.
   
3. **K-Means Clustering**:
    - The optimum number of clusters is determined using the **Elbow Method**.
    - A K-Means model is trained on the data, and customers are grouped into five distinct clusters.
   
4. **Visualization**:
    - The clusters are visualized using a 2D scatter plot, showing the distinct customer groups and their centroids.

## Key Libraries

- **NumPy**: For numerical computations
- **Pandas**: For data manipulation and analysis
- **Matplotlib**: For data visualization
- **Seaborn**: For statistical data visualization
- **Scikit-learn**: For implementing K-Means clustering

## Results

- Five distinct customer clusters were identified based on annual income and spending scores.
- This segmentation can be used to better understand customer behavior and design personalized marketing strategies.

### Elbow Method for Optimal Clusters

![Elbow Method Graph](C:\ML Projects\Customer-Segmentation-using-K-Means-Clustering\Elbow Graph.jpg)

### Customer Clusters

![Customer Segmentation Plot](C:\ML Projects\Customer-Segmentation-using-K-Means-Clustering\customer_groups.png)




## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/FaheemKhan0817/Customer-Segmentation-using-K-Means-Clustering.git

2. pip install -r requirements.txt

3. jupyter notebook customer_segmentation.ipynb

## Conclusion
This project demonstrates how to use K-Means clustering for customer segmentation. By grouping customers based on their annual income and spending score, businesses can enhance their customer retention strategies and target specific customer groups more effectively.



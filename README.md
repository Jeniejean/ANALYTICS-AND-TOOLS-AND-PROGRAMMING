Plotly

Link Code: https://github.com/Jeniejean/ANALYTICS-AND-TOOLS-AND-PROGRAMMING/blob/main/Amazon_Best_Seller_Analyst_6610422019.ipynb

3.1 Post the image of your chart newplot
![newplot](https://github.com/Jeniejean/ANALYTICS-AND-TOOLS-AND-PROGRAMMING/assets/157271789/c434d61a-3cbe-4de1-9182-9d3e7cd80ad5)


3.2 Explain your data sources
The dataset used for analysis is a collection of best-selling products with their respective categories. It provides information on the products that have been top sellers along with user-specific data. Here's an overview of the data sources:
Title: Name of the product.
Author: Name of the author or creator of the product.
User Rating: User-rated ranking of the product (ranging from 1 to 5).
Reviews: Number of reviews received from users.
Price: Price of the product.
Year: Year in which the product was a bestseller.
Genre: Category or genre of the product.
This dataset is in CSV format and contains information about top-selling products and user-specific data from 2009 to 2019. It is suitable for analyzing trends in bestselling products and the popularity of products over the specified time period. The data is valuable for behavioral analysis of consumers and top-selling products in the online retail market, impacting marketing strategies for businesses interested in selling popular products in related industries both currently and in the future. Users can download additional data from the provided link for further analysis and study according to their specific interests or business needs.
Link data sources: https://www.kaggle.com/datasets/sootersaalu/amazon-top-50-bestselling-books-2009-2019

3.3 Explain why choose the chart with your data
The chosen chart, a stacked bar chart, was selected due to its effectiveness in presenting complex data in a visually accessible format. Here's a more detailed explanation:
Clarity and Simplicity: Stacked bar charts are intuitive and easy to understand. By representing data with vertical bars, they allow for straightforward comparisons between different categories or groups. In this case, the chart displays the total reviews of best-selling products grouped by user rating bins across various years. The stacked nature of the bars enables viewers to see both the total reviews for each year and how those reviews are distributed among different user rating categories.
Temporal Analysis: The chart facilitates the analysis of trends over time. Each bar represents a year, and the stacked segments within each bar show how the total reviews are partitioned into different user rating bins for that particular year. By examining changes in the height and composition of the bars across multiple years, viewers can gain insights into shifts in user preferences and product popularity over time.
Insight into User Behavior: By categorizing reviews into user rating bins, the chart provides insights into user behavior and preferences. It allows viewers to see how the distribution of reviews varies across different levels of user satisfaction, ranging from low to high ratings. This information can be valuable for understanding which types of products tend to receive more positive or negative feedback and how these patterns evolve over time.
Interactivity: The chart benefits from Plotly's interactive features, which enhance the user experience. Viewers can hover over the bars to see specific data points, such as the total number of reviews for each user rating bin in a particular year. This interactivity enables deeper exploration of the dataset and encourages engagement with the visualizations.
In summary, the stacked bar chart was chosen for its ability to effectively communicate trends in user reviews of best-selling products over time while remaining simple and accessible to a wide audience. Its clarity, temporal analysis capabilities, insight into user behavior, and interactive features make it a powerful tool for exploring and understanding the dataset.

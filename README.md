# Retail-Sales-Data-set
This dataset invites you to unravel intricate patterns, draw insights,  and gain a deeper understanding of customer behavior.


<h1>INTRODUCTION</h1>
	Welcome to the Retail Sales and Customer Demographics Dataset! This synthetic dataset has been meticulously crafted to simulate a dynamic retail environment, providing an ideal playground for those eager to sharpen their data analysis skills through EXPLORATORY DATA ANALYSIS (EDA), with a focus on retail sales and customer characteristics, this dataset invites you to unravel intricate patterns, draw insights, and gain a deeper understanding of customer behavior. 

<h2>Dataset Overview</h2>
     This dataset is a snapshot of a fictional retail landscape, capturing essential attributes that drive retail operations and customer interactions. It includes key details such as Transaction ID, Date, Customer ID, Gender, Age, Product Category, Quantity, Price per Unit, and Revenue. These attributes enable a multifaceted exploration of sales trends, demographic influences, and purchasing behaviors.
 



Why Explore This Dataset?
 Realistic Representation: Though synthetic, the dataset mirrors real-world retail scenarios, allowing you to practice analysis within a familiar context. 
Diverse Insights: From demographic insights to product preferences, the dataset offers a broad spectrum of factors to investigate. 
Hypothesis Generation: As you perform EDA, you'll have the chance to formulate hypotheses that can guide further analysis and experimentation.
Questions to Explore 
1. Find the Total Quantity of Product sold 
2. How many are the Product Category? 
3. How does customer age and gender influence their purchasing behavior? 
4. Are there discernible patterns in sales across different time periods? 
5. Which product categories hold the highest appeal among customers? 
6. What are the relationships between age, spending, and product preferences? 
7. How do customers adapt their shopping habits during seasonal trends, having the season: Spring (March, April, and May), Summer (June, July, and August) Autumn (September, October, and November), Winter (December, January, and February) 
8. Are there distinct purchasing behaviors based on the number of items bought per transaction? 
                     Note: The above insights are to be visualized using Power BI Desktop

To analyze this dataset based on the outlined questions, we can design a hypothetical retail dataset that captures customer purchases & behaviors, insights, recommendations, and conclusions. Here’s a structured outline of what the dataset could include: Data preparation, Data modeling and Data visualization.
Data Preparation:
•	Data Collection: I imported this dataset from Excel file to my power BI through the data               import method. The data structure include: Transaction ID, Date, Customer ID, Gender, Age, Product Category, Quantity, Price per Unit and Revenue, Imported into power query.
•	Data Transformation: I ensure date formats are consistent and I created calculated columns & measures (Season based on month, Distinct categories, Item bins, Total number of transactions, Total number of customers, Total quantity, Total Revenue, Total Unit prize, Age range & Age band) to summarize the data.
•	Data Cleaning: Check for missing values, duplicates, and inconsistent formats in my POWER QUERY. Clean the data to ensure accuracy for my analysis.

Data Modeling:
I created a relationship with my tables (Date, Gender, Product Category, Retail Sales Fact) by merging all together with a unique identifier.

 



Data Visualization: 

I use the 'Visualizations' pane to create the recommended charts and graphs, added slicers & filters and page navigator, to allow for interactive exploration of the data. List of charts & graphs I used in achieving these goals are (Clustered column chart, Line chart, Pie chart, Cards, Clustered bar chart, Stacked bar chart).

 
 



Analytical Insights and Visualization

1.	Find the Total Quantity of Product sold? 
  Insight: The total quantity provides insight into overall sales volume, which is critical for inventory management and to ensure inventory levels match high-demand products to avoid stockouts. I created a card visual to display the total quantity sold.
 
2.	How many are the Product Category?
  Insight: The number of product categories helps understand the product diversity offered and consider focusing on high-performing categories based on sales data. I use a card visual to show the count distinct product categories.
 


3.	How does customer age and gender influence their purchasing behavior?
Insight: Analyze which age groups purchase the most and what types of products they prefer. Compare purchasing behavior between genders within each age group. Identify which products are popular among different demographics. I use a clustered bar chart.
Recommendation: Tailor marketing campaigns to target age and gender groups that show higher purchasing tendencies. Understanding age and gender influence helps in developing targeted marketing strategies.
•	Age range 51-60 show higher purchases in electronics, while 21-30 shows high purchase in beauty and 41-50 shows high purchase in clothing.
•	Male customers might dominate clothing purchases across all age groups.
•	Consider seasonality or promotional periods in your analysis.
•	Clothing took the lead in the product category which means the genders purchase more on clothing than electronics and beauty.
  

4.	Are there discernible patterns in sales across different time periods?
Insight: Identify trends and patterns in sales over different time periods (monthly and years). I use a Line graph to show monthly or yearly sales.
Recommendation: Adjust marketing efforts and inventory levels based on peak sales periods. Identifying time-based sales patterns allows for better strategic planning and resource allocation.
•	Identify peak sales months, or dips in sales. From the graph you discover that the month of May 2023 has the highest sales but had a lot of loss in January 2024. 
•	Compare sales performance month-over-month or year-over-year. The sales performance was good in 2023 from January to December but had a downtrend in January 2024
•	 Analyze the impact of promotions or events on sales trends. The sales trend shows a downtrend
  

5.	Which product categories hold the highest appeal among customers?
Insight: Determine which categories are most appealing and popular among customers. I use a pie chart to analysis the dataset.
Recommendation: Invest in clothing for top-performing categories. Focus promotional efforts on top-performing categories to maximize sales. Recognizing popular product categories aids in optimizing inventory and marketing strategies.
•	Identify the top 1 product categories by quantity sold. Clothing has the highest because there was high purchase for it
 

6.	What are the relationships between age, spending, and product preferences?
Insight: Analyze how shopping behavior changes with seasons. Examine how age influences spending habits. I use a stacked bar chart to analysis the dataset.
Recommendation: Create personalized marketing and pricing strategies based on age-related spending habits. Analyzing these relationships helps in understanding customer preferences and spending behavior. Implement seasonal marketing campaigns and Seasonal trends can guide promotions and inventory decisions. 

•	Identify which age group spends the most and their preferred product categories. from the table you will see that age range from 11-20 spends more
•	Analyze if there’s a correlation between higher spending and specific product categories across age groups. Yes, there is a correlation between the age range and product categories

  

7.	How do customers adapt their shopping habits during seasonal trends, having the season: Spring (March, April, and May), Summer (June, July, and August) Autumn (September, October, and November), Winter (December, January, and February)?
Insight: Analyze changes in shopping behavior with seasons. I use a clustered column chart to analysis the data.
Recommendation: Implement seasonal marketing campaigns. Seasonal trends can guide promotions, inventory decisions and stock management. Seasonal insights are crucial for aligning marketing efforts with customer shopping behavior throughout the year.

•	Identify which season has the highest overall sales and which product types dominate in each season. From the table Spring has the highest sales.
•	Analyze any notable trends, such as seasonal spikes in specific categories.
•	Discuss potential inventory strategies based on seasonal sales patterns.

 

8.	Are there distinct purchasing behaviors based on the number of items bought per transaction?
Insight: Examine purchasing behaviors based on the number of items bought. Differentiate customer behavior by transaction size.
Recommendation: Encourage larger transactions through bundling offers. Distinct behaviors based on transaction size can inform pricing strategies. Offer discounts or promotions for larger transaction sizes to encourage bulk purchases. Understanding transaction sizes can help in structuring promotions and pricing strategies.

•	Identify which item bin has the highest total spending and which product categories dominate in each bin.
•	Analyze trends or patterns, such as whether customers buying more items tend to spend more or prefer certain categories.
•	Discuss marketing strategies based on the preferences of customers in different item bins.
 


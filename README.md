# Data Visualization Using Looker Studio
 
![looker studio](https://github.com/zilllaa/Data-Visualization-Using-Looker-Studio/assets/139882527/3f4dac45-337f-4927-be0a-f9ca2abaf9e6) 

Looker Studio is an online tool for converting data into customizable informative reports and dashboards introduced by Google on March 15, 2016 as part of the enterprise Google Analytics 360 suite. It is a data visualization platform that makes reports easier to create and understand. It is a free tool that turns data into informative, easy-to-read, easy-to-share, and fully customizable dashboards and reports. Looker Studio's built-in and partner connectors make it possible to connect to virtually any kind of data. Looker Studio unlocks the power of data by making it easy to create interactive dashboards and compelling reports from a wide variety of sources, driving business insights and enabling smarter decision-making.

# The Advantages of Looker Studio

•	**Free tool**: Looker Studio is a free tool that turns data into informative, easy-to-read, easy-to-share, and fully customizable dashboards and reports. 

•	**Real-time collaboration**: When sharing Looker Studio files with other editors, you can work together in real-time as a team.

•	**Easy to use**: Looker Studio's drag and drop report editor allows users to create fully customizable dashboards and reports easily.

•	**Connectors**: Looker Studio's built-in and partner connectors make it possible to connect to virtually any kind of data.

•	**Customizable visualizations**: Looker Studio offers pre-made templates and a visualization library to help users create reports quickly.

•	**Community component library**: Looker Studio's community component library provides an interface between users and Looker Studio. It handles events and provides convenience methods to simplify the development of visualizations.

•	**Enterprise features**: Looker Studio's enterprise features allow administrators to manage users and control access to Looker Studio assets.

# Data Understanding
## Source Data
![analitik](https://github.com/zilllaa/Data-Visualization-Using-Looker-Studio/assets/139882527/ef5f6fea-bb9a-40d9-905e-b73a6554804c) 

•	[Customer Spending](https://www.kaggle.com/datasets/goyaladi/customer-spending-dataset/data)

•	8 columns

•	1000 rows

## Data Dictionary
Customer spending dataset provides valuable insights into customer demographics, income, spending habits, and purchase behavior. 

•	Name: The name of the customer.

•	Age: The age of the customer.

•	Gender: The gender of the customer.

•	Education: The highest level of education attained by the customer.

•	Income: The annual income of the customer.

•	Country: The country of origin of the customer.

•	Purchase frequency: The frequency of customer purchases, ranging from 0.1 to 1.0.

•	Spending: The annual spending of the customer, calculated based on various factors.
 
# Data Cleansing
 
![data cleansing](https://github.com/zilllaa/Data-Visualization-Using-Looker-Studio/assets/139882527/5e8b849a-763a-4ea6-a5e1-6eef8bc358e3) 

The data is clean, with correct data types, and free from missing values and duplicates. so that, the data can be directly visualized in looker studio.
 
# Data Visualization and Story Telling
## Dashboard Customer Behavior
 
![data dashboard](https://github.com/zilllaa/Data-Visualization-Using-Looker-Studio/assets/139882527/347feeea-e79b-4dc0-a86c-49202c6de458) 

The picture above is a visualization of the customer spending dataset using Looker Studio. At the top there is a highligth of the dataset. And the left is a dataset sorter where the dataset can be sorted by age, gender, and education.

## Distribution of Spending by Nation
 
![distribution of spending](https://github.com/zilllaa/Data-Visualization-Using-Looker-Studio/assets/139882527/bb272701-4b76-43af-a199-409e270a7175) 

In the top 10 map chart, Palau takes the lead in customer spending with 1.32%, indicating a strong consumer market. Ukraine, on the other hand, ranks the lowest with spending at 0.92%, highlighting its potential for business expansion and growth.

## Corelation Between Spending and Purchase Frequency
 
![corelation](https://github.com/zilllaa/Data-Visualization-Using-Looker-Studio/assets/139882527/2f0b842d-6093-4c88-96f7-15bd37577411) 

Based on the data above, it is found that customer behavior between purchase frequency and spending has a strong positive correlation, suggesting that the more frequently customers make purchases, the higher their spending tends to be. This insight underscores the significance of understanding and leveraging purchase frequency as a key driver of customer spending, offering valuable implications for businesses looking to optimize their sales and marketing strategies.

## Distribution of Gender by Spending
 
![distribution gender](https://github.com/zilllaa/Data-Visualization-Using-Looker-Studio/assets/139882527/e5f4bb33-6970-4fb1-bacc-b9bd239e5d8c)

Examining the spending data categorized by gender, it becomes apparent that females take the lead with 52.9%, while males represent 47.1% of the overall spending. This indicates that female customers tend to demonstrate a greater inclination towards spending than their male counterparts.

## Comparison of Spending and Income
 
![comparison spending n purchase](https://github.com/zilllaa/Data-Visualization-Using-Looker-Studio/assets/139882527/5e03ae47-1b27-4444-974d-b93269a501ba)

In the data comparison of the average income and spending of customers based on age (18-65), it can be seen that the older the age of the customer, the higher the spending compared to the income earned by the customer, but the income trend fluctuates along with customer expenses.

This is quite evident in the graph of spending that have an increasing frequency, especially at the age of 65 years, which recorded the highest spending of 3,46% but only had an income of 2,65%. This is inversely proportional to the young age of 34 years where income leads 3,28% compared to spending of 2,27%. 

Starting at the age of 45, the trend shows a continuous decline in income compared to young people who are still actively working. This change in income and spending trends may reflect changes in the economic situation or spending priorities of customers as they age.


## Analyzing Food and Grocery Delivery Throughout the Year
<img src="images/order-food-on-your-hand-1_orig.png?raw=true"/>

As part of my first step towards a career in data analysis, I joined a data analytics accelerator boot camp. The first project introduced in this course was on a data set for a company similar to DoorDash that was modified for this program. This project made me wonder questions, like "What products bring in the most profit?", "Who are their main consumers?", and "Are there any noticeable trends from their campaigns?".Utilizing Excel and the data set given in the course, I was able to answer these questions and learn how the company sales and demographics work. From my analysis, I was able to find:
- 76% of consumers are aged 36-65
- Over $150000 was spent on wine by consumers
- Over 90% of the company's consumers have a college degree
- $1.13 million was spent by consumers


### The Data
This data set was originally a data analyst use case for an interview process.
Here is the data set:
(/files/DoorDash_Case_Study.xlsx)
Some important columns to look at are:
- Income: Customer's Yearly Income
- MntTotal: Total Amount Spent at Store by Customer
- MntWines: Amount Spent on Purchasing Wine
- MntFruits: Amount Spent on Purchasing Fruit
- MntMeatProducts: Amount Spent on Purchasing Meat
- MntFishProducts: Amount Spent on Purchasing Fish
- MntSweetProducts: Amount Spent on Purchasing Sweet
- MntGoldProds: Amount Spent on Purchasing Gold
- AcceptedCmp1: Did The Customer Accept Offer in 1st Campaign
- AccaptedCmp2: Did The Customer Accept Offer in 2nd Campaign
- AcceptedCmp3: Did The Customer Accept Offer in 3rd Campaign
- AcceptedCmp4: Did The Customer Accept Offer in 4th Campaign
- AcceptedCmp5: Did The Customer Accept Offer in 5th Campaign
- AcceptedCmp6: Did The Customer Accept Offer in 6th Campaign
- Age Group
- education_Graduation: Is the customer's highest education level undergraduate?
- education_Master: Is the customer's highest education level Master's?
- education_PHD: Is the customer's highest education level a PhD?
- education_2n Cycle: Is the customer’s highest education high school?
- Each row represents a customer.

### The Analysis
<img src="images/Money Spent by Product.png?raw=true"/>
Using the sum function in Excel, the total money spent through "DoorDash" was $1,139,418. We produced the chart above to further break down the money spent by product. Consumers spent the most money on wine products, coming to a total of $150,068. Consumers also spent $90,571 on meat products. One possible way to use this finding is by trying to gain new consumers and having campaigns or special deals for meat or wine products. Another option is to have special deals for the products consumers spend less on to entice them to buy more fruit, sweet, fish, or gold products.

<img src="images/Age Demographic.png?raw=true"/>
Comparing the ages of the consumers, the bar chart above shows most of the customers are between the ages of 36 to 65. Comparing the ages of the consumers, the bar chart above shows most of the customers are between the ages of 36 to 65.

<img src="images/Education Demographic.png?raw=true"/>
About 51% of the consumers have a bachelor's degree and another 25% have a PhD or Masters for their highest education. ​Focusing on the average income by age group, the following bar chart is generated:

<img src="images/Average income by age group.png?raw=true"/>
At first glance, there isn't much difference between age groups. The bar chart shows the older the consumer, the more money they earn. Utilizing the data shown in the scatter plot below, it is shown that there is a direct correlation between money earned and the amount spent on products. Looking at the amount spent based on the highest education level, the following chart is shown:
<img src="images/amnt spent by education.png?raw=true"/>
The chart shows that there is on average about a $100 difference of money spent between a consumer's education level. Wondering why this is happening, the following bar chart was generated:
<img src="images/Average income by efducation.png?raw=true"/>
From this bar chart, a consumer with a Ph.D. level education earns about $54,000, while a person with a high school diploma earns about $48,000. From this difference in income, it can be seen there is a correlation between income and money spent. The following scatter plot confirms this thought, by showing a direct correlation between income and money spent.

<img src="images/Income vs Total Spent Scatter Plot.png?raw=true"/>

### Main Takeaways
From this analysis, the following conclusions were made:
- Consumers spend the most money on wine and meat products
- Most of the company's consumers are between the ages of 36-65
- Most of the company's consumer's highest level of education is a bachelor's degree
- There is a direct correlation between the income of the consumer and the money spent by the consumer

One way the company can use this analysis is by creating a campaign or sale for less popular products like fruit, sweets, and fish to encourage consumers to spend more money on other products. Another way would be to create a campaign aimed at consumers who earn a higher income.

# Luxury-Brand-Analysis-Project

### Business Understanding:

Al Dubai Fragrances is a privately held luxury goods retailer and distributor, headquartered in Dubai, UAE. Al Dubai Group is the largest retail operator in the Middle East. It played a crucial role in developing the luxury sector in the region. The company has more than 12,000 employees, in 14 countries.

Al Dubai operates in two major modes, one is through its mobile application and the second is through its various offline stores that they have across Dubai and the middle east. Under the brand name Al Dubai Fragrances, they have a wide variety of products for both Males and Females but their major distribution is across fashion products and accessories among female customers. 

### Problem Statement:

In recent years, Al Dubai Fragrances has faced a certain dip in their revenue and they are now looking to go through a major transformation in the following two sectors.
1.	They are looking to revamp their marketing strategy by targeting the right set of customers.
2.	They are looking to promote their application among customers so that they may enter into the “E-Commerce” sector.

You are working as an Associate Data Analyst with Al Dubai Fragrances and you are now required to help the marketing team to identify the various segments of customers that can be found in the data so that the marketing team can accordingly roll out offers to enhance customer engagement and experience with their products.

### RFM Scoring Technique:

RFM Stands for recency, frequency, and monetary value. It’s a very popular scoring technique to identify the best-performing and least-performing customer groups. 
In the above table, we have taken the average of R-Score, F-Score and M-Score to generate RFM Score. Now, the higher the score, the better the customer, the lower the score, the worst the customer.

### Tasks-Excel:
You are given the excel file with the data consisting of the details of various customers. Perform the following tasks using excel/google sheets to answer the questions.
1.	Use the RFM technique defined above to find the top-performing customers and the bottom-performing customers. 
a.	Filter the data and create two sheets, one with those customers having an RFM score greater than 4.5. Name this sheet as Top Performing Group
b.	Create another sheet with those customers having RFM Score less than 2. Name this sheet as Worst Performing Group.
c.	Using both sheets and answer the following questions.(Using Pivot Table)
i.	What is the proportion of males and females?
ii.	Find the average sales
iii.	Find the number of app and non-app users.
2.	Create a new column(sales level) using the following conditions(Use if-else).
a.	Total sales<1000: ‘L5’
b.	Total sales>=1000 and total sales<10000: ‘L4’
c.	Total sales>=10000 and total sales<20000: ‘L3’
d.	Total sales>=20000 and total sales<50000: ‘L2’
e.	Total sales>50000: ‘L1’
3.	Find the number of customers and the average number of transactions under each sales level.
4.	Use V-Lookup to achieve the following result.
a.	You are given the category and the number of transactions ranges in the below table. 
b.	
A	1-10
B	10-50
C	50-100
D	>100
c.	Using v-lookup append the category column to the data
d.	Find the category-wise count of orders placed.
5.	Find the top 5 customers according to the percentage of total sales. (Use pivot table)

### Tasks-SQL:

Al Dubai Fragrances wants to expand its business to the online web market and for that expansion, they are looking to improve its team. The company has the data of its various employees. You are required to answer the following questions to help the Al Dubai Fragrances HR team better understand its employees.

Tasks:

1.	Load the tables in the database and name them as hr.
2.	Find the number of employees working in the ‘Sales’ department. (Use sub-query).
3.	Join the 3 tables and find the country-id wise count of employees and the avg salary. Which country has the maximum number of employees and which country has the maximum average salary?
4.	Find the top 5 managers according to their salary.
5.	Find the department name-wise percentage of employees working under each department. Which department is having the maximum percentage of employees?

### Results:

Present your result in a business presentation and submit three files.
a.	Excel file with all the results(each in a separate sheet)
b.	SQL file with all the queries.
c.	Presentation explanation with the insights derived from the analysis.

### Important Notes:

1.	Please note that since this is an EDA Case Study, your analysis should not be just limited to the questions asked above. You are required to take extra steps in order to find out more interesting insights from the data.
2.	If you are generating plots, please make sure that you have also added the inference that you may derive from the plot. Any plot generated without your observation/inference will not be considered for evaluation.
3.	Add details regarding any assumptions that you make while working on the case study. You are free to make assumptions or add more insights to the analysis by adding data from various sources but any such steps taken by you need to be mentioned in your solution file.



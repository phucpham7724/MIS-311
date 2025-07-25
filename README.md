# MIS-311
1. Data Overview

The table have 201 rows (not include labers) and 5 columns 
Nam of the columns 
+ Country
+ Year 
+ Average_Monthly_Income
+ Cost_of_Living
+ Region
The context or background of the data:


The data shows average incomes and living costs by country, during different years, with the goal of perhaps comparing living standards across regions or countries. The data also includes geographic (continental) information, allowing for regional groupings.
<img width="624" height="158" alt="image" src="https://github.com/user-attachments/assets/ee898608-dda8-4400-90ff-080ba069acfd" />
<img width="573" height="150" alt="image" src="https://github.com/user-attachments/assets/af39d76f-c4a4-4287-8a7c-3bfa2d7a5c67" />

2. Data Cleaning

There are 4 missing data in the data, including 2 missing data in the Average_Monthly_Income column, I use median function to fill in these 2 cells. 2 are missing in Region, here I know that the region of Mexico is in the same area (North America) so I just need to fill in the 2 missing places which are North America.

<img width="545" height="246" alt="image" src="https://github.com/user-attachments/assets/6b78cd47-766b-4daf-8488-63d6f4be6bd1" />
<img width="546" height="326" alt="image" src="https://github.com/user-attachments/assets/c7f4ef93-4d4b-46f5-9fad-6811d1eb62b2" />

I checked and found 2 duplicates and decided to delete them.

<img width="410" height="110" alt="image" src="https://github.com/user-attachments/assets/6e1407ab-a29d-4f72-b4f6-80d189b4b6ce" />

3. Descriptive Statistics

<img width="569" height="308" alt="image" src="https://github.com/user-attachments/assets/5a7a707d-01ce-41a9-b778-58df4accbacb" />

The minimum monthly income is 534.74, while the minimum cost of living is 464.49. This narrow margin (only about 70.25 difference) suggests that individuals at the bottom end of the income distribution are living very close to the survival threshold. Any unexpected expenses or price increases could push these individuals into financial hardship.

The average monthly income ( 4244.19) is higher than the average cost of living ( 3705.13), suggesting that, on average, individuals may have a financial buffer. However, the high standard deviations (2116.64 for income and 1982.22 for costs) and wide ranges indicate everyone significant variation, implying that not may actually experience this surplus.

Below are some data and charts to easily compare data with each other in each region.

<img width="520" height="466" alt="image" src="https://github.com/user-attachments/assets/047baa6d-d7e9-493d-804f-81e27b44d40b" />

The bar chart compares total living costs and average monthly incomes across six global regions. In all regions, incomes are higher than living costs, with Asia and Europe having the highest total incomes. Africa and South America have the lowest figures, reflecting more modest economic conditions.

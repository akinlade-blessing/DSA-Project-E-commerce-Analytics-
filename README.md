## Project Topic: Amazon Product and Customer's Review
### Project Overview
The primary goal of this project is to analyze the e-commerce data which includes product analysis, customer's review, and marketing effectiveness—to generate actionable insights that drive improved decision-making, customer engagement, and revenue growth.

### Background:
As the e-commerce industry continues to grow, businesses require more sophisticated analytics to remain competitive. By leveraging data from platforms like Amazon,businesses can better understand market trends, optimize pricing and inventory, and personalize customer experiences.

### Data Sources
The primary source of data used here is Amazon Case Study and this is an open source data that can be downloaded from an open source. this particular data source used was gotten from DSA tutors.

### Tools Used
- Microsoft Excel 
  - For data collection
  - For data cleaning
- SQL Server
  - (For querying and analysis)
- Power Bi (To create a report)

### Data Cleaning and Preparation
To achieve the final results, these steps were performed on the data.
  - Data Cleaning
  - Creation of pivot tables
  - Visualization

### Exploratory Data Analysis(EDA)
Exploratory Data Analysis (EDA) is the process of examining and summarizing a dataset to understand its main characteristics, patterns, and relationships before applying any formal modeling or statistical techniques.
Computers and accesories had the highest average discount percentage by product category
Electronics is the most available product
Amazon Basics High-Speed has the highest number of reviews
Amazon Basics Wireless has the highest average ratingsThe five top product in terms of rating is 
 - Amazon Basics Wireless M
 - Campfire Spring Chef Pro
 - FIGMENT Handheld Milk Fr
 - Instant Pot Air Fryer, V
 - Multifunctional 2 in 1 E
 - Oratech Coffee Frother 

The top five products in terms of number of reviews include 
Amazon Basics High-Speed
AmazonBasics Flexible Pr
boAt Bassheads 100 in Ea
Redmi 9A Sport (Coral Gr
JBL C100SI Wired In Ear 

AVERAGE DISCOUNT PERCENTGE BY PRODUCT CATEGORY				PRODUCT COUNT BY PRODUCT CATEGORY 				TOTAL RATING COUNT BY PRODUCT CATEGORY				ACTUAL PRICE AGAINST DISCOUNTED PRICE BY PRODUCT CATEGORY					TOTAL POTENTIAL REVENUE BY PRODUCT CATEGORY				TOTAL RATING COUNT BY PRODUCT CATEGORY	
Row Labels	Average of discount_percentage			Product Category	Count of product_name.1			Product Category	Sum of rating_count			Product Category	Average of actual_price	Average of discounted_price			Product Category	Sum of Potential Revenue			Product Category	Sum of rating
Car & Motorbike	42%			Car & Motorbike	1			Car & Motorbike	1118			Car & Motorbike	 $4,000.00 	 $2,339.00 			Car & Motorbike	 $4,472,000.00 			0%-10%	353.4
Computers & Accessories	54%			Computers & Accessories	453			Computers & Accessories	7728689			Computers & Accessories	 $1,683.62 	 $842.65 			Computers & Accessories	 $12,614,808,461.00 			11%-20%	393.5
Electronics	51%			Electronics	526			Electronics	15778848			Electronics	 $10,127.31 	 $5,965.89 			Electronics	 $98,020,806,794.00 			21%-30%	681.2
Health & PersonalCare	53%			Health & PersonalCare	1			Health & PersonalCare	3663			Health & PersonalCare	 $1,900.00 	 $899.00 			Health & PersonalCare	 $6,959,700.00 			31%-40%	713.5
Home & Kitchen	40%			Home & Kitchen	448			Home & Kitchen	2991069			Home & Kitchen	 $4,162.07 	 $2,330.62 			Home & Kitchen	 $10,459,722,337.00 			41%-50%	1032.1
Home Improvement	58%			Home Improvement	2			Home Improvement	8566			Home Improvement	 $799.00 	 $337.00 			Home Improvement	 $6,163,434.00 			51%-60%	1040.2
Musical Instruments	46%			Musical Instruments	2			Musical Instruments	88882			Musical Instruments	 $1,347.00 	 $638.00 			Musical Instruments	 $151,117,062.00 			61%-70%	904.2
Office Products	12%			Office Products	31			Office Products	149675			Office Products	 $397.19 	 $301.58 			Office Products	 $60,778,817.00 			71%-80%	644.7
Toys & Games	0%			Toys & Games	1			Toys & Games	15867			Toys & Games	 $150.00 	 $150.00 			Toys & Games	 $2,380,050.00 			80%-90%	209.3
Grand Total	48%			Grand Total	1465			Grand Total	26766377			Grand Total	 $5,444.99 	 $3,125.31 			Grand Total	 $121,327,208,655.00 			91%-100%	25.3
																					Grand Total	5997.4
																						
																						
TOTAL RATING COUNT BY PRODUCT CATEGORY				PRODUCT CATEGORY WITH MOST REVIEW				PRODUCTS WITH 50% OR MORE				UNIQUE PRODUCTS PER PRICE RANGE BUCKET					CATEGORIES WITH HIGHEST DISCOUNT				TOP 5 PRODUCTS BY COMBINED SCORE	
Product Category	Average of rating			Product Category	Sum of rating_count			Product Category	NUMBER OF PRODUCTS			Product Category	Count of product_name.1				Product Category	Average of discount_percentage			Product Category	Sum of Combined Score
Amazon Basics Wireless M	5			Amazon Basics High-Speed	 853,946 			No	 714 			<200	 199 				Car & Motorbike	42%			Amazon Basics High-Speed	3757362.4
Campfire Spring Chef Pro	4.7			AmazonBasics Flexible Pr	 853,945 			Yes	 751 			>500	 889 				Computers & Accessories	54%			AmazonBasics Flexible Pr	3757358
FIGMENT Handheld Milk Fr	4.7			boAt Bassheads 100 in Ea	 727,426 			Grand Total	 1,465 			200-500	 377 				Electronics	51%			boAt Bassheads 100 in Ea	2982446.6
Instant Pot Air Fryer, V	4.8			Redmi 9A Sport (Coral Gr	 627,668 							Grand Total	 1,465 				Health & PersonalCare	53%			Redmi 9A Sport (Coral Gr	2573438.8
Multifunctional 2 in 1 E	4.7			JBL C100SI Wired In Ear 	 577,766 												Home & Kitchen	40%			JBL C100SI Wired In Ear 	2368840.6
Oratech Coffee Frother e	4.8			boAt Deuce USB 300 2 in 	 377,454 			PRODISTRIBUTION OF PRODUCT RATING									Home Improvement	58%			Grand Total	15439446.4
REDTECH USB-C to Lightni	5			boAt BassHeads 100 in-Ea	 363,711 			Product Category	Count of product_name.1								Musical Instruments	46%				
Sony Bravia 164 cm (65 i	4.7			boAt Bassheads 242 in Ea	 323,356 			(blank)	 1 								Office Products	12%				
Swiffer Instant Electric	4.8			Redmi 9 Activ (Carbon Bl	 313,836 			5	 3 								Toys & Games	0%				
Syncwire LTG to USB Cabl	5			Redmi 9A Sport (Carbon B	 313,832 			4.8	 3 								Grand Total	48%				
Zuvexa USB Rechargeable 	4.7			Grand Total	 5,332,940 			4.7	 6 													
Grand Total	4.8							4.6	 17 													
								4.5	 75 													
								4.4	 123 													
								4.3	 230 													
								4.2	 228 													
								4.1	 244 													
								4	 181 													
								3.9	 123 													
								3.8	 86 													
				PRODUCT CATEGORY WITH MOST REVIEW				3.7	 42 													
				Product Category	Sum of rating_count			3.6	 35 													
				Amazon Basics High-Speed	 853,946 			3.5	 26 													
				AmazonBasics Flexible Pr	 853,945 			3.4	 10 													
				boAt Bassheads 100 in Ea	 727,426 			3.3	 16 													
![image](https://github.com/user-attachments/assets/24458e0d-928b-471f-b2e2-4e1686223f67)






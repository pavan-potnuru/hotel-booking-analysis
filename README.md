# Hotel-Booking-Analysis
EDA Capstone project- Hotel Booking Analysis

## 1.Problem Statement

We are here to explore a hotel booking dataset to discover important factors that govern the bookings, which contain booking information for a city hotel and a resort hotel. We will analyze some important aspects of hotel bookings which will helps us identify major loopholes and give us insights which will be helpful to run profitable hotel business are as follows:
•	The time of year to book a hotel room?
•	Optimal length of stay to get the best daily rate?
•	To predict whether or not a hotel was likely to receive a disproportionately high number of special requests?

## Introduction
In Hotel industry, Cancellation and Average Daily Rate are two important factors that help run the business effectively.
By understanding the factors that are determining the cancellation of a certain booking, the hotels can take necessary precautions to reduce Cancellation rate.
By understanding the patterns in ADR against different variables, the hotels can be prepared in advance to generate more revenue and help make a profitable business.
Our goal here is to understand such factors in the given data set by performing Exploratory Data Analysis.

## Exploratory Data Analysis:

Exploratory Data Analysis refers to the critical process of performing initial investigations on data so as to discover patterns, to spot anomalies, to test hypothesis and to check assumptions with the help of summary statistics and graphical representations.

The following are the various steps performed as a part of Exploratory Data Analysis:
•	Data Preparation
•	Data Cleaning
•	Univariate Analysis
•	Bivariate Analysis
•	Multivariate Analysis

## Data Preparation
Firstly, we imported libraries and dataset, some of the libraries used are NumPy, pandas, matplotlib, seaborn, warnings. Once the data is collected, process of analysis begins. But data has to be translated in an appropriate form. This process is known as Data Preparation

## Data Cleaning
The raw data received in the data set might not be directly suitable for analysis due to presence of unwanted data like, duplicate values, null values, outliers etc. We need to handle them first before we proceed with further analysis.

Removing Duplicates: The dataset provided for this analysis consists of almost 32000 duplicate records. We have removed these duplicate values so that we get accurate patterns and numbers regarding the hotel booking.

Handling null/missing values: It is also possible that the given data set can contain missing information for some or all features in some records, we need to either remove them or find alternatives to fill up the null values. We have added ‘0’ in place of null values for company feature assuming the booking is done directly by the customer. Also, for country column we filled them with ‘Others’. In the Children column we replaced it with ‘0’ as there is a majority chance that the customer has come without children to the hotel.

## Univariate Analysis:
In Univariate Analysis, we choose a single feature from the data and try to determine what the output or the target value is, i.e., one feature/variable at a time. 
• Understand the trends and patterns of data • Analyze the frequency and other such characteristics of data
• Know the distribution of the variables in the data. 
• Visualize the relationship that may exist between different variables.

## Bivariate Analysis: 
In a Bivariate Analysis, we try to analyze two features instead of one, and finally determine the classification of output we are looking for. It is a methodical statistical technique applied to a pair of variables (features/ attributes) of data to determine the empirical relationship between them. In order words, it is meant to determine any concurrent relations. We have performed the following analysis as a part of Bivariate analysis:

## Hotel-wise analysis: 
In this step we have compared hotel type with various relevant features to understand the variation in the two hotel types across different features like total_nights_stayed, cancellation, etc.

## ADR analysis: 
ADR (Average Daily Rate) is one of the most important features that determines the revenue in the hotel industry. So, we have performed ADR analysis against different parameters to understand how ADR is related and varying with different 

## Cancellation Analysis:
Cancellation is also one of the key factors that drive the revenue and subsequently the overall profits of the hotels in hotel industry. If the cancellations are less, the hotels can get high occupancy thus generating more revenue. So, we have performed bivariate analysis to understand the patterns in cancellations across different parameters like hotel type, market segment, deposit types, etc.

## Multivariate Analysis: 
In Multivariate analysis we analyze three or more different features at a time, to understand the relationship between all the features involved.

## Conclusion
●	Around 61% of bookings are for the City Hotel and 39% bookings are for Resort hotel, therefore City hotel is busier than Resort Hotel.
●	Most of the bookings are from European countries, so we need to focus more on Domestic market.
●	60% of the bookings are from Online TA and also 1/3rd of the total cancellations is from online TA. Some strict rule should be levied in terms of cancelations for online bookings.
●	Highest number of bookings are in the month of August and we can also see the increase in bookings in the month range from May to Oct. Hostel need to prepared for this peak time so they provide smooth experience for guests.
●	Guest tends to stay longer when they are allotted the same room type as they preferred while booking.
●	Avg. waiting time for City hotel is 1 day and for Resort hotel is 0.3 days. Resort hotel has 60% more customer return rate than City hotel, so city hotel should try to reduce the avg. waiting time.
●	Highest number of bookings are from people count of 2. Hotels need to provide good facilities and offers for couples to drive more traffic
●	Booking with people count as (4 – 5) has highest avg ADR. Focus more on families to increase revenue.
●	Lead time and cancelations are positively corelated.
●	Cancelations are more in non-refundable deposit type; hotel should check reasons for cancelations and take precautions.
●	Cancelation for previously canceled bookings is very high, so hotels can have strict policies for customers who had cancelled in the past.

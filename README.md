# Kira Plastinina-Company
Kira Plastinina is a Russian brand that is sold through a defunct chain of retail stores in Russia, Ukraine, Kazakhstan, Belarus, China, Philippines, and Armenia. The brand’s Sales and Marketing team would like to understand their customer’s behavior from data that they have collected over the past year. More specifically, they would like to learn the characteristics of customer groups.

# Defining the Metric of Success
The metrics of success for this project are:

  - Performing clustering stating insights drawn from my analysis and visualizations.

  - Upon implementation, provide comparisons between the K-Means clustering vs Hierarchical clustering approaches, highlighting the strengths and limitations of each approach in the context of my analysis.
  
# Understanding the Context
The project is centered around the Sales and Marketing industry. Customer segmentation is vital because it helps the business to get insights of the different customer segments, hence tailor their marketing accordingly.

# Recording the Experimental Design
For this analysis, I will perform the following actions:

Loading the Data.

Reading the Data.

Cleaning the Dataset.

Performing EDA:

Univariate Analysis.

Bivariate Analysis.

Multivariate Analysis.

Implement the Solution.

Challenging the Solution.

Follow-up Questions.

# Data Understanding
- The dataset consists of 10 numerical and 8 categorical attributes. The 'Revenue' attribute can be used as the class label.

- "Administrative", "Administrative Duration", "Informational", "Informational Duration", "Product Related" and "Product Related Duration" represents the number of different types of pages visited by the visitor in that session and total time spent in each of these page categories. The values of these features are derived from the URL information of the pages visited by the user and updated in real-time when a user takes an action, e.g. moving from one page to another. 

- The "Bounce Rate", "Exit Rate" and "Page Value" features represent the metrics measured by "Google Analytics" for each page in the e-commerce site. 
The value of the "Bounce Rate" feature for a web page refers to the percentage of visitors who enter the site from that page and then leave ("bounce") without triggering any other requests to the analytics server during that session.

- The value of the "Exit Rate" feature for a specific web page is calculated as for all pageviews to the page, the percentage that was the last in the session.
The "Page Value" feature represents the average value for a web page that a user visited before completing an e-commerce transaction. 

- The "Special Day" feature indicates the closeness of the site visiting time to a specific special day (e.g. Mother’s Day, Valentine's Day) in which the sessions are more likely to be finalized with the transaction. The value of this attribute is determined by considering the dynamics of e-commerce such as the duration between the order date and delivery date. For example, for Valentina’s day, this value takes a nonzero value between February 2 and February 12, zero before and after this date unless it is close to another special day, and its maximum value of 1 on February 8. 

- The dataset also includes the operating system, browser, region, traffic type, visitor type as returning or new visitor, a Boolean value indicating whether the date of the visit is weekend, and month of the year.

# Exploratory Data Analysis

## Univariate

The image below shows the univariate analysis of various variables:

![sqft_living Vs Price](condition_uni.png)

## Bivariate

The images below show how various sqft_living, bedrooms, and condition:

![sqft_living Vs Price](sqft_living_price.png)

![bedrooms Vs Price](bedrooms_price_bi.png)

![condition Vs Price](condition_price_bi.png)

![price change over time](house_price_change.png)

Heatmap showing the correlation of all the variables:

![heatmap](heatmap.png)

## Multivariate

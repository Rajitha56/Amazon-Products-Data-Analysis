# Amazon Product Data Analysis
## Project Overview
This project analyzes Amazon product data to uncover insights related to pricing, discounts, ratings, and customer reviews. The dataset contains details about various products, including their prices, discounts, ratings, reviews, and categories. The analysis aims to identify trends in pricing, product popularity, and customer feedback.

## Objective
--Clean and preprocess the dataset for accurate analysis.
--Perform Exploratory Data Analysis (EDA) to identify key trends.
--Visualize important aspects of the data.
--Extract meaningful insights regarding product pricing, discounts, and customer preferences.

## Dataset Information
--**product_id** : Unique identifier for the product.
--**product_name** : Name of the product.
--**category** : Product category.
--**discounted_price**  : Price after applying discounts.
--**actual_price** : Original price of the product.
--**discount_percentage** : Percentage of discount applied.
--**rating** : Customer rating of the product.
--**rating_count** : Number of ratings received.
--**about_product** : Product description.
--**user_id** : Unique identifier for the user.
--**user_name** : Name of the user who reviewed the product.
--**review_id** : Unique identifier for the review.
-- **review_title** : Title of the review.
--**review_content** : Full text of the review.
--**img_link** : Link to the product image.
--**product_link** : Link to the product on Amazon.

## Data Cleaning Steps
--Convert discounted_price and actual_price to numeric by removing currency symbols.
--Convert discount_percentage to numeric after removing the % sign.
--Convert rating and rating_count to proper numeric types.
--Handle missing values in rating_count by filling with the median.
-- Drop unnecessary columns like img_link, product_link, user_id, and user_name if not needed for analysis.
## Exploratory Data Analysis (EDA)
--**Basic Statistics** : Summary of pricing, discounts, and ratings.
--**Category Analysis** : Identify the most common product categories.
--**Price vs Discount Analysis** : Examine the relationship between discount percentages and actual prices.
--**Ratings Distribution** : Analyze the spread of product ratings.
--**Review Analysis** : Extract frequently used words in customer reviews.

## Visualizations
--**Category Distribution** : Bar chart of the most common product categories.
![image](https://github.com/user-attachments/assets/a1542987-0e08-4085-ae25-abca2a025ade)

--**Price vs Discount** : Scatter plot to show discount trends.
![image](https://github.com/user-attachments/assets/9f733c7e-d9a8-406f-aa33-38a64029e28d)

--**Rating Distribution** : Histogram of product ratings.
![image](https://github.com/user-attachments/assets/eac9f901-bd97-4f7e-9786-9172aef62257)

--**Top-rated Products** : Bar chart of the highest-rated products.
![image](https://github.com/user-attachments/assets/dda75dff-77a4-4b9a-86b6-51c087190a87)

--**Review Word Cloud**: Visual representation of frequently used words in reviews
![image](https://github.com/user-attachments/assets/fce44c4b-dbd6-4194-89b3-6463843fa78b)

## Insights

--**High Discounts on Expensive Products** : Products with higher actual prices tend to have larger discounts to attract buyers.
--**Most Common Rating is 4.0-4.5** : Majority of products have ratings within this range, indicating good customer satisfaction.
--**Category Popularity** : Some categories like electronics and fashion have a higher number of products listed.
--**Higher Ratings Correlate with More Reviews** : Products with higher ratings tend to have more customer reviews, indicating a strong customer engagement.
--**Common Review Words Indicate Quality and Service** : Word cloud analysis shows frequent terms related to product quality, delivery speed, and packaging.

## Technologies Used

--Python for data analysis and visualization.
--Pandas for data manipulation.
--Matplotlib & Seaborn for visualizations.
--WordCloud for text analysis.


## How to Use

--Ensure you have Python installed along with the required libraries (pandas, matplotlib, seaborn, wordcloud).
--Load the dataset and execute the cleaning and analysis steps.
--Generate visualizations to interpret the insights.
--Modify and extend the analysis based on specific business questions.
--This project provides a comprehensive analysis of Amazon products, helping businesses and consumers make informed decisions based on product pricing, discounts, and customer feedback.



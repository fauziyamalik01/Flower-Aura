FlowerAura (Customer Sentiment Analysis):-

End-to-end sentiment analysis project on FlowerAura product reviews. Scraped 400+ reviews, performed NLP preprocessing, and generated customer insights using Python.

Project Overview:-

This project is about understanding customer sentiment from products review. The goal was to understand how customers feel about a product, whether they are happy or unhappy, by processing their review data and classifying it as positive or negative.

About the data:-

1. I scrapped almost 500 reviews from the FolwerAura website
2. Each review conatined customer's name, city, occasion, rating and review text

Tool Used:-

The tool used here was Python and its Libraries like-
1. Selenium & BeautifulSoup for Scrapping the data
2. Pandas perform data manipulation like cleaning and preprocessing
3. TextBlob for sentiment analysis
4. Seaborn & Matplotlip for Data Visualization 

Data Cleaning & Preprocessing:-

1. Removed duplicate reviews
2. Handled missing values
3. Converted ratings to numeric format
4. Converted text to lowercase & more

Key Insights:-

1. 99% of reviews were positive with an average rating of 4.91 out of 5
2. Birthday & Anniversary were the top selling occasions together accounting for 50% of the reviews 
3. Banglore, Delhi and Hyderabad were the cities with most acyive customers.
4. Positive reviews frequently mention words like “fresh”, “delivery”, and “quality”.
5. Negative reviews highlight delivery delays or packaging issues.

Business Recommendations:-

1. FlowerAura should focus more on delivery reliability since that is where most negative reviews were concentrated
2. They should run targeted markeing campaingns around birthdays and anniversaries since they are the strongest segment
3. They should leverage 91% of five-star rating as social proof in ads and on product pages to drive conversions.

Challenges Faced:-

The biggest challenge here was that Flipkart's system blocked my selenium scrapper, so i had to pivot to FlowerAura and i also had to deal with missing values, duplicates, data inconsistencies again.


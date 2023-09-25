
![YelpExplorer](https://github.com/DATA-606-2023-FALL-MONDAY/Kandlagunta_Dheeraj/blob/dev/pictures/YelpExplorer.png)

## 1. Title and Author

- Project Title: Yelp Explorer: A Chatbot Assistant for Finding and Learning About Local Businesses
- Prepared for UMBC Data Science Master Degree Capstone by Dr Chaojie (Jay) Wang
- Author Name: Dheeraj Kandlagunta 
- [GitHub](https://github.com/DATA-606-2023-FALL-MONDAY/Kandlagunta_Dheeraj/tree/dev)
- [LinkedIn](https://www.linkedin.com/in/dheeraj-kandlagunta/)

## 2. Background

For my capstone project, I'm creating a chatbot assistant called Yelp Explorer that will assist customers in finding and learning about local businesses using natural language interactions. This chatbot attempts to be a helpful navigator through the vast quantity of data on Yelp as more people depend on online reviews and recommendations when choosing where to eat, buy, and spend their free time. The chatbot may offer users personalized suggestions and information by using machine learning to analyze customer reviews, ratings, and qualities of businesses. 

The Sentiment Analysis tools, such as Textblob and LSTM-based models, will be employed to evaluate user reviews and derive quantitative sentiment metrics. By combining sentiment scores with review ratings, a super score will be developed, representing users' comprehensive experiences and feelings towards businesses. This score will be utilized in the Collaborative Filtering Recommendation System.

Topic Modeling (LDA) will also be integrated to classify reviews into various dominant themes. By pinpointing recurring keywords in these themes, these keywords will be applied to the Content-Based Recommendation System.

The longitude and latitude coordinates of businesses will be used to build a Location-Based Recommendation System, with businesses being grouped using the K-Means Clustering Algorithm.

The main research questions are at how AI assistants can efficiently search and summarize huge Yelp datasets to satisfy users' requests through dialog.

## 3. Data 

Data Source: [Yelp Open Dataset](https://www.yelp.com/dataset)

Data Size: 
- Original: 8.82GB
- Filtered: 692.2MB  


Records:
Total -
- Reviews: 6,990,280
- Businesses: 150,346
- Users: 1,987,897

Additional Data:
- Over 1.2 million business attributes (hours, parking, availability, ambience etc.)
- Aggregated check-ins over time for each of the 131,930 businesses

Data Shape: 
- business.json: approximately 161,000 rows and 11 columns
- review.json: over 5.5 million rows and 7 columns  
- user.json: over 1 million rows and 20 columns

Time Period: Data spans from 2004 to 2022.

What does each row represent?
- business.json: Each row represents a unique business listed on Yelp.
- review.json: Each row represents a specific review written by a user.
- user.json: Each row represents a Yelp user profile.

In-depth description: https://www.yelp.com/dataset/documentation/main
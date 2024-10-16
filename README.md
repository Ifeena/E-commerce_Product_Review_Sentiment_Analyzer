# E-commerce_Product_Review_Sentiment_Analyzer
# Project Overview
This project develops a sentiment analysis model specifically for e-commerce product reviews in the Electronics category from AliExpress. The objective was to automate the classification of reviews into positive and negative sentiment, providing clear insights for product improvement and marketing strategies.
# Problem Statement
E-commerce platforms like AliExpress face the challenge of processing large volumes of customer feedback to determine product sentiment. Manual analysis is time-consuming, necessitating an automated solution for effective insights.
Objectives
- Create an accurate sentiment analysis model.
- Extract specific insights from customer reviews for actionable product and marketing improvements.
- Improve customer satisfaction through better understanding of feedback trends.
# Methodology
1. Data Acquisition: Collected over 2,000 reviews and corresponding star ratings from AliExpress's database.
2. Data Preprocessing: Cleaned and tokenized text data, handling missing values and removing special characters.
3. Feature Engineering: Applied Bag of Words (BoW) and TF-IDF for feature extraction.
4. Model Training: Collaboratively trained various models, including Vader (Pre trained model), Logistic Regression, XGBoost, and Naive Bayes, evaluating performance using metrics such as accuracy, precision, and F1 score.
5. Model Evaluation: Analyzed models to identify the most effective option based on performance metrics.
6. Model Deployment: Deployed the best-performing model using Flask for local and Streamlit for web-based access.
# Contributors
1. Ifechukwu Akaeze
2. Daniel Edet Onofiok
3. Okediran Tope Emmanuel
4. Dr. Ezeuchu Emmanuel Uzondu
5. Modinat Gbemisola Adesope
6. Adebayo Olalekan
7. Khadijat Oludolapo Adebiyi
8. Chinua Mbajekwe
9. Dr. Chinwe Njoku
10. Vincent C. Ajaegbu
11. Ayodele Kehinde Richard
12. Precious Odinakachi Loveday
13. Ifeoluwa Adeniyi
# Tech Stack
- Development: Jupyter Lab, VSCode
- Deployment: Flask, Streamlit
# Conclusion/Insights
The sentiment analysis provided actionable patterns in customer feedback, enabling businesses to target product improvements and refine marketing strategies. The team identified Logistic Regression with BoW as the most effective model, achieving 93.39% accuracy.

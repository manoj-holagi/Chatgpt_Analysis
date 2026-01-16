# ChatGPT Reviews Data Analysis

## Project Overview
This project performs an end-to-end analysis of a large dataset of ChatGPT user reviews. The goal is to understand user satisfaction, sentiment distribution, and engagement trends over time. The analysis is conducted using Python in Google Colab.

## Business Problem
ChatGPT receives a high volume of user feedback. Analyzing this feedback is essential to improve product quality and user experience. This project answers:
- What is the overall level of user satisfaction?
- How are positive, neutral, and negative reviews distributed?
- How do reviews change over time?
- What issues are most common in negative feedback?

## Dataset Information
File Name: `chatgpt_reviews.csv`

### Columns
- Review Id – Unique identifier for each review
- Review – User-provided text feedback
- Ratings – User rating (1–5)
- Review Date – Date and time of review

## Objectives
- Perform exploratory data analysis (EDA)
- Analyze rating distribution
- Identify review trends over time
- Perform sentiment analysis
- Analyze review text behavior
- Visualize insights

## Tools and Technologies
- Google Colab
- Python
- Pandas
- Matplotlib

## Data Cleaning and Preparation
- Handled missing values in review text
- Converted review date to datetime format
- Created derived features such as review length and sentiment labels
- Validated rating and date fields

## Exploratory Data Analysis
- Rating distribution analysis
- Monthly review trends
- Review length vs rating analysis
- Sentiment-wise review distribution
- Identification of long negative reviews

## Sentiment Analysis
Sentiment was derived using a rule-based approach:
- Ratings 4–5 → Positive
- Rating 3 → Neutral
- Ratings 1–2 → Negative

## Sentiment Distribution
- Positive ≈ 88%
- Negative ≈ 8%
- Neutral ≈ 4%

## Visualizations
- Rating distribution bar chart
- Monthly review trend line chart
- Sentiment distribution pie chart

## Key Insights
- Most users are highly satisfied
- Review volume is increasing over time
- Negative reviews are fewer but more detailed
- Performance issues dominate negative feedback

## Results and Findings
- Strong overall user satisfaction
- Actionable insights from negative reviews
- Increasing engagement trend identified

## Author
Manoj M Holagi  
Data Analyst | Data Collection and Analytics  
LinkedIn: https://www.linkedin.com/in/manoj-holagi/

## Note
This project is created for learning and portfolio purposes.

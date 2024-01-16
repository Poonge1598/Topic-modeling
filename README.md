# Airline Reviews Sentiment and Topic Analysis

## Introduction
This project analyzes airline reviews to extract insights through topic modeling and sentiment analysis, identifying the public perception of various airline services.

## Data Sources and Lexicons
The analysis used the `NRC-Emotion-Lexicon-Wordlevel-v0.92.txt` file to score reviews based on a range of emotions and sentiments.

## Sentiment Analysis
- Sentiments and emotions in the reviews were quantified, focusing on both positive (joy, anticipation, surprise, trust) and negative (anger, disgust, fear, sadness) aspects.
- Mean sentiment scores for these emotions were computed for each airline.
- The results were visualized, showcasing the distribution of sentiments across airlines.

## Topic Modeling
- Topic modeling was performed using Latent Dirichlet Allocation (LDA) to identify prevalent topics in negative and positive reviews.
- A network graph was created to illustrate the connections between airlines and specific topics such as seating, reservations, customer support, and flight delays.
- The thickness of the edges in the graph represents the strength of the connection, indicating the prevalence of certain topics in relation to specific airlines.

## Visualization
The provided network graph demonstrates the analysis of topics associated with each airline, highlighting customer service and flight experience-related issues.

## Discussion
- The analysis sheds light on customer sentiment and common themes in reviews, providing valuable insights for business strategy and operational improvements.
- It also points out the areas where an airline is performing well and where improvements are needed to enhance the customer experience.

## Conclusion
- The project demonstrates the effectiveness of sentiment analysis and topic modeling in extracting actionable insights from customer reviews.
- The findings can be instrumental for airlines to improve their service quality and customer experience.


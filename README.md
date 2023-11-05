# MarkyChallenge - Tamu Datathon Project

## Introduction
Welcome to MarkyChallenge, our Tamu Datathon project! We embarked on this journey to predict user approval of AI-generated content, delving into the fascinating interplay between AI and human sentiment.

## Project Overview
MarkyChallenge aims to predict whether users will approve or disapprove of AI-generated posts by analyzing both textual and visual content. Leveraging data science and machine learning techniques, we offer valuable insights into user preferences, contributing to the enhancement of content creation and recommendation processes.

## Model Performance

Here's a summary of the performance of different models we experimented with:

| Model               | Training Loss | Training Accuracy | Testing Accuracy |
|---------------------|---------------|-------------------|-------------------|
| Single LSTM 8 Units | 0.5273        | 75.23             | 73.22             |
| Single LSTM 32 Units | 0.5134        | 76.34             | 71.06             |
| BERT 7 epochs       | 0.36          | 90.24             | 71.8              |
| BERT 5 epochs       | 0.42          | 84.38             | 73.83             |
| BERT 3 epochs       | 0.47          | 79.12             | 75.25             |

We see that different models offer varying levels of performance in terms of training loss and accuracy.

## Challenges and Learning
Throughout the project, we encountered challenges related to computational resources, model interpretability, and dataset handling. Overcoming these obstacles taught us the importance of balancing model interpretability with predictive power, the influence of content factors on user approval, and the need for responsible content creation.

## Next Steps
In the future, we plan to continue exploring the interplay between visual and textual content, enhancing model interpretability, expanding our dataset for better accuracy, and incorporating real-time sentiment analysis. We're also working on personalized content recommendations to enhance user experiences in the age of AI-generated content.

Thank you for exploring MarkyChallenge with us! We look forward to further developments in this exciting journey.


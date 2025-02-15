# Emotion-Map-of-Toronto
An emotion map of Toronto City using NLP Techniques and plotting using Folium. 

# Overview

This project performs sentiment and emotion analysis on tweets collected from Toronto. By leveraging Natural Language Processing (NLP) techniques, the project aims to create an emotion heatmap of the city, providing insights into public sentiment across different locations and events.

# Dataset

The dataset consists of tweets collected from a 50km radius around Toronto over a period of January 2024 to January 2025. The dataset includes:

Tweet text
Location data (latitude, longitude) (Which was added using Geopandas (Nominatim)
Timestamps
Hashtags and mentions

# Methodology

## Data Preprocessing

1. Cleaning tweets (removing URLs, mentions, hashtags, stopwords, and special characters)
2. Tokenization and lemmatization
3. Handling missing values and location-based filtering

## Sentiment & Emotion Analysis

1. Utilizing pre-trained models (e.g., VADER, TextBlob, or RoBERTa) for sentiment analysis
2. Classifying emotions using models like BERT-based fine-tuning
3. Generating an emotion score for each tweet

# Visualization & Insights

1. Creating an Emotion Heatmap of Toronto using geo-tagged tweets
2. Analyzing sentiment trends over time (daily, weekly, monthly trends)
3. Correlating emotions with events, weather, or major social occurrences

# Technologies Used

### Python (pandas, NumPy, scikit-learn, NLTK, transformers, seaborn, matplotlib, folium, geopandas)

### NLP Models (BERT, RoBERTa, TextBlob, VADER)

### Data Visualization (Plotly, Folium for maps, Matplotlib, Seaborn)

# Results & Key Findings

Generated a dynamic heatmap showing happiest and saddest locations in Toronto.
Discovered trending topics contributing to positive and negative emotions.

# How to Run

Clone the repository:

git clone https://github.com/yourusername/Toronto-Twitter-Emotion-Analysis.git

Install dependencies:

pip install -r requirements.txt

Run the analysis:

python analyze_tweets.py

View the visualization results in results/

Future Enhancements

Real-time sentiment tracking using live Twitter API.

Multi-city comparison to see how Toronto compares with other cities.

Integration with weather & event data for deeper correlation insights.

### Contact

For any questions, feel free to reach out via GitHub issues or email me at sakethsavanth@gmail.com.


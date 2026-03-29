# Flipkart Reviews Sentiment Analysis Project

## Overview
This project aims to analyze sentiment from Flipkart customer reviews using various machine learning techniques in Python. The primary goal is to predict whether a given review is positive, negative, or neutral based on the text content.

## Features
- **Sentiment Analysis**: Classifies reviews as positive, negative, or neutral.
- **Data Visualization**: Visual representation of sentiment distribution.
- **Customizable**: Easy to adapt to other datasets with minimal modifications.

## Requirements
- Python 3.6 or higher
- libraries used: 
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn
  - nltk
  - tensorflow (if using deep learning)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/abinaya-345/Flipkart_reviews_sentiment_analysis_using_python.git
   cd Flipkart_reviews_sentiment_analysis_using_python
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Import the necessary modules:
   ```python
   import pandas as pd
   import numpy as np
   from sklearn.model_selection import train_test_split
   from sklearn.feature_extraction.text import TfidfVectorizer
   from sklearn.linear_model import LogisticRegression
   ```
2. Load your dataset:
   ```python
   df = pd.read_csv('reviews.csv')
   ```
3. Preprocess the data and create a model as explained in the scripts provided.

## Project Structure
```
Flipkart_reviews_sentiment_analysis_using_python/
│
├── data/                  # Contains raw and processed data
├── notebooks/              # Jupyter notebooks for exploration and analysis
├── src/                   # Source code for sentiment analysis
├── requirements.txt       # Required libraries for the project
├── README.md              # Project documentation
└── results/               # Stores results and visualizations
```

## Results
After running the analysis, results will show the accuracy of the model along with visualizations of sentiment distribution.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
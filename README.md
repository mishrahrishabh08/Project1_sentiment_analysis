# Amazon Review Sentiment Analysis

## Project Overview
This project performs sentiment analysis on Amazon product reviews by analyzing the text and categorizing the sentiment into positive, negative, or neutral. The goal is to understand the overall sentiment of customer reviews.

## Technologies Used
- **Programming Language:** Python
- **Libraries:**
  - `NumPy`: For numerical operations.
  - `Pandas`: For data manipulation and analysis.
  - `Matplotlib` and `Seaborn`: For data visualization.
  - `NLTK`: Natural Language Toolkit for sentiment analysis.
  - `tqdm`: To display progress bars during data processing.
- **Environment:** Virtual environment (`venv`)

## Project Setup
### 1. Clone the Repository
```
git clone https://github.com/mishrahrishabh08/Project1_sentiment_analysis.git
cd Project1_sentiment_analysis
```

### 2. Create and Activate Virtual Environment
```
# Create virtual environment
python3 -m venv venv

# Activate the environment (Linux/Mac)
source venv/bin/activate

# Activate the environment (Windows)
venv\Scripts\activate
```

## Dataset
The project uses Amazon product reviews from `https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews/Reviews.csv`. The dataset contains customer reviews with scores and text descriptions.
As the dataset was very big, only the top `15000` rows are included

## Steps Followed
### 1. **Data Loading and Exploration**
- Loaded the dataset using `Pandas`.
- Displayed the shape and previewed the data.
- Visualized the distribution of review scores using bar plots.

### 2. **Sentiment Analysis**
- Used `NLTK`'s `SentimentIntensityAnalyzer` to compute sentiment scores.
- Applied the analyzer to each review.
- Categorized the reviews into positive, negative, and neutral based on the sentiment scores.

### 3. **Data Visualization**
- Visualized the distribution of sentiment categories.
- Created bar plots and pie charts for easy interpretation of sentiment distribution.

## How to Run
1. Ensure the virtual environment is activated.
2. Execute the Jupyter notebook or run the Python script.
3. Review the visualizations and sentiment analysis results.

## Visuals
1. Our initial dataset

   ![Screenshot From 2025-03-30 15-49-15](https://github.com/user-attachments/assets/f9ea56f9-e9c0-4818-a9dc-f927b6eae6fc)
   
3. Count of Reviews by Stars

    ![Screenshot From 2025-03-30 15-49-25](https://github.com/user-attachments/assets/a9c2859f-8f20-4381-b05d-e186941fbbbd)
   
6. Our Dataset after including the result columns

   ![Screenshot From 2025-03-30 15-49-41](https://github.com/user-attachments/assets/bbf99a9f-8c84-4003-8eaa-4cf2e1d7679d)
   
8. Compound Score by Amazon Star Review

   ![Screenshot From 2025-03-30 15-50-57](https://github.com/user-attachments/assets/5cf6aec2-8d6c-43d4-9f25-3ca2b5de3f62)
   
9. Positive , negetive and neutral Scores by Amazon Star Review

  ![Screenshot From 2025-03-30 15-51-08](https://github.com/user-attachments/assets/f8da3478-b06e-45a6-8eea-6d31dc184f18)

## Results
- The project successfully provides insights into the overall sentiment of Amazon reviews.

- Sentiment distribution is visualized using plots for better understanding.

- Key Insight:

   1- With the increase in positive sentiment scores, the overall rating score also rises.

   2- This indicates that users giving positive feedback tend to leave higher ratings, demonstrating a clear correlation between sentiment and ratings.

- The project effectively utilizes NLTK for sentiment analysis, successfully identifying and visualizing the sentiments of the reviews.

## Future Enhancements
- Use more advanced NLP models (e.g., `Transformers`, `BERT`) for improved accuracy.
- Perform topic modeling to group similar reviews.
- Create a web dashboard to display real-time review analysis.

## Author
Hrishabh Mishra


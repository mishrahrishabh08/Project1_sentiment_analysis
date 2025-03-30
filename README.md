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
git clone <repository_url>
cd <project_directory>
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
The project uses Amazon product reviews from `dataset/Reviews.csv`. The dataset contains customer reviews with scores and text descriptions.

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

## Results
- The project provides insights into the overall sentiment of Amazon reviews.
- Sentiment distribution is visualized using plots for better understanding.

## Future Enhancements
- Use more advanced NLP models (e.g., `Transformers`, `BERT`) for improved accuracy.
- Perform topic modeling to group similar reviews.
- Create a web dashboard to display real-time review analysis.

## Author
[Your Name]


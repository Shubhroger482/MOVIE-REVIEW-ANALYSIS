# MOVIE-REVIEW-ANALYSIS
# Movie Review Sentiment Analysis

This project analyzes movie reviews and predicts whether a review is **positive** or **negative** using Machine Learning models. It was created as a Project Based Learning (PBL) activity.

## Project Structure

- Perform complete **Exploratory Data Analysis (EDA)**
- Handle missing values and remove duplicate entries
- Display data distribution and detect outliers
- Encode categorical features
- Normalize feature data
- Train and evaluate two models:
  - Logistic Regression
  - Random Forest Classifier
- Compare model performances
- Allow users to input custom reviews for real-time sentiment prediction

## Dataset

The dataset used is the **IMDB Movie Reviews** dataset containing 50,000 entries. Each entry includes:

- `review`: The text of the movie review
- `sentiment`: The sentiment label ("positive" or "negative")

## Requirements

- Python 3.7+
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

Install requirements using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/Shubhroger482/MOVIE-REVIEW-ANALYSIS.git
cd MOVIE-REVIEW-ANALYSIS
```

2. Ensure the `IMDB Dataset.csv` file is present.

3. Run the main Python script:

```bash
python MOVIE-REVIEW-ANALYSIS.py
```

4. After training, you can enter custom reviews to predict their sentiment. Type `exit` to stop the prediction loop.

Example input:

```text
This movie was absolutely fantastic! Loved the acting and storyline.
```

Example output:

```text
Logistic Regression Model Prediction: POSITIVE -> ✅ Good Review!
Random Forest Model Prediction: POSITIVE -> ✅ Good Review!
```

## Features

- Full EDA process with visualization
- Cleaning of input text for better model accuracy
- Friendly output with emojis ✅ / ❌
- Model comparison using bar graphs
- Continuous prediction loop for user reviews

## Future Improvements

- Hyperparameter tuning for better accuracy
- Deploy as a web app using Flask/Streamlit
- Use deep learning models like LSTM for better text understanding

Made with ❤️ for Machine Learning PBL.


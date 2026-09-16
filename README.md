# Movie Review Sentiment Analysis

## About the Project

This project analyzes movie reviews and predicts whether a review is positive or negative.

The project started with exploring and cleaning the review dataset, followed by text preprocessing to prepare the reviews for machine learning. The cleaned text can then be converted into numerical features using TF-IDF and used to train sentiment classification models.

The main goal of the project is to understand the review data, identify useful text patterns, and build a model that can classify the sentiment of a new movie review.

---

## Dataset

The dataset contains movie reviews along with their sentiment labels.

- Total reviews: 50,000
- Columns: `review`, `sentiment`
- Positive reviews: 25,000
- Negative reviews: 25,000
- Duplicate reviews: 418

After removing duplicate reviews, the dataset contains 49,582 unique reviews.

### Columns

| Column | Description |
|--------|-------------|
| `review` | Text of the movie review |
| `sentiment` | Sentiment of the review (positive/negative) |

---

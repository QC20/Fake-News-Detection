# Fake News Detection on Twitter
Automatic Fake News Spreader Profiling Detecting


This repository contains code and resources for a machine learning framework developed for the detection of fake news posts on the online social media platform Twitter. We have conducted classification experiments on both an English and a Spanish dataset to achieve reliable results.

## Methodology
Our approach involved testing various methods and combinations to identify the best performing model for detecting fake news tweets. After careful evaluation, we found that the Gradient Boosting & Random Forest model, combined with features extracted from a TF-IDF approach, yielded the most accurate results.

## Results
For the English dataset, our model achieved an accuracy score of 75.33% mean accuracy in detecting fake news tweets. Similarly, for the Spanish dataset, we achieved a mean accuracy of 77.66%.

## Repository Structure
- `data/`: This directory contains the English and Spanish datasets used for training and testing.
- `code/`: This directory contains the Python scripts used to preprocess the data, train the models, and evaluate the performance.
- `models/`: This directory contains the trained models saved in the pickle format.
- `results/`: This directory contains the evaluation results and performance metrics of the models.

## Getting Started
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/fake-news-detection.git

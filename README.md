# udemy--course-recommendation

## Overview
This repository contains code for building a recommendation system for Udemy courses. The recommendation system utilizes cosine similarity based on TF-IDF vectors of course titles to suggest similar courses to users.

## Dataset
The dataset used in this project is a CSV file containing information about Udemy courses, including course titles, prices, number of subscribers, number of reviews, and other relevant attributes.

## Requirements
- Python 3.x
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

4. Follow the instructions provided by the script to generate recommendations based on different criteria.

## Files
- `main.py`: Main script to run the recommendation system.
- `utils.py`: Utility functions for data preprocessing and feature engineering.
- `evaluation.py`: Functions to evaluate the performance of the recommendation system.
- `udemy_courses.csv`: Dataset containing information about Udemy courses.

## Functionality
- The `main.py` script provides an interface to interact with the recommendation system.
- Users can specify different criteria for generating recommendations, such as number of reviews, number of subscribers, etc.
- The recommendation system uses TF-IDF vectors of course titles and cosine similarity to suggest similar courses.

## Results
- Evaluation metrics such as precision, recall, and F1-score are computed to assess the performance of the recommendation system.
- The results of the recommendation system are presented to the user through the command line interface.

## Future Improvements
- Incorporate collaborative filtering techniques for more personalized recommendations.
- Experiment with different feature engineering methods to improve recommendation quality.
- Deploy the recommendation system as a web application for broader accessibility.






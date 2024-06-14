# NAAC Survey Analysis and NPS Calculation

## Project Overview
This project aims to analyze the National Assessment and Accreditation Council (NAAC) survey data, which is crucial for understanding student feedback on various aspects of college facilities and teacher-student relations. By using machine learning models and neural networks for natural language processing (NLP), the project classifies student suggestions into positive, negative, and neutral categories, calculates department-wise Net Promoter Scores (NPS), and identifies key areas for improvement.

## Project Features
1. **Department-wise NPS Calculation**: Computes the Net Promoter Score (NPS) for each department based on survey responses.
2. **Sentiment Analysis**: Classifies student suggestions into three categories: positive, neutral, and negative, providing a detailed sentiment report.
3. **Frequent Suggestions Report**: Generates and downloads the top 10 most frequent positive and negative suggestions department-wise in CSV format.
4. **CSV Files**: Outputs seven CSV files:
    - 6 CSV files with the top 10 positive and negative suggestions for each department.
    - 1 CSV file containing the aggregated results.

## Project Abstract
NAAC surveys conducted in colleges provide essential insights into how students perceive the facilities and teacher-student relationships. Analyzing these surveys can significantly improve student life at the college by addressing concerns promptly. This project utilizes machine learning and NLP techniques to classify suggestions from the survey data into positive, negative, and neutral categories. The suggestions are further analyzed to extract the most common suggestions, which are then compiled into the top 10 lists for each department. The result is a comprehensive and actionable feedback report that can guide the improvement process for each department.

## Installation
To set up and run the project locally, follow these steps:

### Prerequisites
- Python 3.6+
- `pip` (Python package installer)

### Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/AbhishekyPhalak/NPS-Analyser.git
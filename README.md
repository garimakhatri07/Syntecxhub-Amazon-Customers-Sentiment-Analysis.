# Amazon Customers Sentiment Analysis

## About the Project

This project focuses on understanding customer feedback from Amazon product reviews. The aim was to analyze customer ratings and review text, classify reviews into positive, neutral, and negative sentiment categories, and identify patterns that can help improve customer satisfaction.

I completed this project as part of my Data Analysis Internship at Syntecxhub. It gave me practical experience working with review data, preparing datasets, analyzing customer feedback, and presenting findings through visualizations.

## Project Objectives

- Clean and prepare Amazon customer review data.
- Classify reviews as positive, neutral, or negative.
- Analyze customer ratings and sentiment distribution.
- Explore sentiment patterns across verified and non-verified purchases.
- Study review trends over time and review-length patterns.
- Identify useful insights and recommendations from customer feedback.

## Dataset

The dataset contains **30,846 customer reviews** and includes information such as review headlines, review text, star ratings, product category, purchase verification, and review dates.

## Work Performed

### 1. Data Cleaning and Preparation
- Checked the dataset's dimensions, missing values, and duplicate records.
- Filled missing review headlines and review bodies with empty strings.
- Converted review text to lowercase and removed surrounding whitespace.
- Prepared review dates for time-based analysis.

### 2. Sentiment Classification
Reviews were categorized using star ratings:
- **Positive:** 4–5 stars
- **Neutral:** 3 stars
- **Negative:** 1–2 stars

This is a rating-based classification approach rather than a trained machine learning model.

### 3. Exploratory Data Analysis
- Analyzed the distribution of customer sentiments and star ratings.
- Compared sentiment across verified and non-verified purchases.
- Examined sentiment patterns over time.
- Explored review length and frequently used words.
- Used charts to present the results in an understandable way.

## Key Findings

- Total reviews analyzed: **30,846**
- Positive reviews: **25,767**
- Neutral reviews: **2,216**
- Negative reviews: **2,863**
- Average star rating for the PC product category: approximately **4.34 out of 5**.

Positive reviews were the most common sentiment category in the dataset. Negative and neutral reviews still provide useful opportunities to understand customer concerns and areas for improvement.

The dataset contains only the PC product category, so comparisons between different product categories were not possible.

## Recommendations

- Review negative feedback to identify recurring product or service issues.
- Use neutral reviews to understand what could improve the customer experience.
- Monitor sentiment trends over time to identify changes in customer feedback.
- Consider verified-purchase feedback when investigating product concerns.
- Use customer suggestions to support product improvements and better customer satisfaction.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization

## Project Files

- `01_Review analysis.ipynb` — notebook containing data preparation, analysis, and visualizations.
- `02_Amazon Product Reviews Dataset.csv` — original dataset.
- `03_Amazon Reviews Sentiment Analysis.csv` — processed dataset containing the analysis columns.
- `README.md` — project overview, methodology, findings, and recommendations.

## Learning Outcome

Working on this project helped me practice data cleaning, sentiment classification using ratings, exploratory data analysis, and visualization. It also helped me understand how customer feedback can be analyzed to identify patterns and support data-informed decisions.

## Acknowledgement

Thank you to **Syntecxhub** for providing this internship project and the opportunity to apply my data analysis skills through practical work.

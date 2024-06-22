Project 1: Melatonin Product Market Analysis: Overview

The market for melatonin products is highly varied, with numerous products available in different doses (e.g., 1mg, 2mg, 10mg, 20mg). This project aims to analyze the distribution of these products and assess customer reviews for each dose.

Steps to Complete:

Data Preparation:

Merge CSV Files: Combine individual files into one DataFrame. Clean Data: Remove unnecessary columns. Extract Dose Information: Add a 'dose' column from the "product_title" column.

Sentiment Analysis:

Analyze "review_rating" by dose.

Text Analysis:

Preprocess Reviews: Remove stop words from "review_text" and "review_header". Extract Keywords: Identify useful phrases (e.g., "good sleep", "tasty").

Analyze Text:

Use tools like TF-IDF or NLTK to evaluate reactions and reviews based on dose.

Tools Required:

NumPy and Pandas for data manipulation. Visualization Tools for data analysis. Text Analysis Tools like TF-IDF or NLTK.

## Google Playstore Dataset: Exploratory Data Analysis (EDA) and Data Cleaning

### Dataset Description

The dataset used in this analysis is the **Google Playstore dataset**. It contains various features of apps available on Google Play, such as `App Name`, `Category`, `Rating`, `Reviews`, `Size`, `Installs`, and more. The dataset provides an opportunity to explore and analyze app characteristics, popularity, and user engagement.

### Steps Followed for EDA and Data Cleaning

1. **Data Loading and Initial Inspection:**
   - Loaded the dataset and inspected its structure, including the number of rows and columns, and the data types of each feature.
   - Checked for missing values and other inconsistencies in the dataset.

2. **Data Cleaning:**
   - Identified and addressed issues with non-numeric values in the `Reviews` column by removing rows with non-numeric data and converting the column to an integer data type.
   - Analyzed and cleaned other features as needed, ensuring that all data was in the correct format for analysis.

3. **Exploratory Data Analysis (EDA):**
   - Conducted an in-depth analysis focusing on key features such as `Category`, `Installs`, `Reviews`, and `Rating`.
   - Generated insights about the most popular app categories based on the number of installs and ratings.
   - Investigated the top apps in the most popular categories and examined which apps received the highest user ratings.

### Key Findings

1. **Category Popularity:**
   - The "GAME" category is the most popular, with nearly 35 billion installations, making it the top category in the Google Playstore.
  
2. **Top Apps in Popular Categories:**
   - The most popular app in the "GAME" category is **Subway Surfers**.
   - The most popular app in the "COMMUNICATION" category is **Hangouts**.
   - The most popular app in the "PRODUCTIVITY" category is **Google Drive**.
   - The most popular app in the "SOCIAL" category is **Instagram**.

3. **Five-Star Apps:**
   - There are a significant number of apps in the Google Playstore that have received a perfect rating of 5 stars.
---
***NOTE :*** I have generated a cleaned dataset that requires further preprocessing. Specifically, some categorical features must be transformed into numerical representations using One-Hot Encoding or a similar technique to enable machine learning training.

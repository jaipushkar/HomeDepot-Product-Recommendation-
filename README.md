# HomeDepot-Product-Recommendation-

**Overview**
This project involves building a recommendation system using data from an Excel file. The system includes both a rating-based and a content-based recommendation approach.

**Requirements**
Python 3.6+
Required packages:
pandas
numpy
matplotlib
seaborn
scikit-learn
spacy
scipy

**Steps**
**1. Load Packages and Libraries**
Import the necessary libraries and packages for data manipulation, visualization, and building the recommendation system.

**2. Data Loading and Preprocessing**
Load the dataset from an Excel file, select relevant columns, and handle missing values.

**3. Exploratory Data Analysis (EDA)**
Perform basic EDA to understand the dataset. This includes checking the number of unique items and ratings.

**4. Data Cleaning and Tag Creation**
Clean the text data and extract tags using spaCy. Create a new column 'Tags' combining relevant text information.

**5. Rating-Based Recommendation System**
Calculate average ratings for items and sort them to get the top-rated items.

**6. Content-Based Recommendation System**
Build a content-based recommendation system using TF-IDF and cosine similarity. Recommend items based on the description and other text features.

**Usage**
**Rating-Based Recommendation**
Top-rated items can be obtained by sorting items based on their average ratings.

**Content-Based Recommendation**
Use the content_based_recommendation function to get recommendations based on a given item description.

**Example**
**To get content-based recommendations for a specific item:**
Specify the item description.
Call the content_based_recommendation function with the item description and desired number of recommendations.

**Notes**
Ensure to load the **en_core_web_sm** model for spaCy.
Handle missing values and data cleaning appropriately.
Adjust parameters like top_n in recommendation functions as needed.

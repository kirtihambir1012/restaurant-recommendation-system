# restaurant-recommendation-system
Hi, this project "Restaurant Recommendation System based on Zomato data" that I made under the guidance of "Astha Sinha" Madam, consists of the recommendation system or model that recommends to user the restaurant based upon the input of the user for a certain restaurant.

This project aims to develop a restaurant recommendation system using a cleaned and analyzed Zomato dataset. 
The system will leverage user preferences and restaurant attributes to provide personalized recommendations.

Dataset:
 1. Source: Zomato dataset
 2. Description: The dataset contains information about restaurants, including location, cuisine, ratings, reviews, and user preferences.
 3. Cleaning: The dataset underwent thorough cleaning, including:
   1. Handling missing values (imputation or removal)
   2. Removing duplicates
   3. Identifying and addressing inconsistencies
   4. Data type conversions
   5. Outlier detection and handling
      
Methodology:
 1. Data Exploration and Analysis:
    Exploratory Data Analysis (EDA) was performed to understand the dataset's characteristics.
    Key insights were extracted, such as popular cuisines, highly-rated restaurants, and user preferences.
 2. Feature Engineering:
   1. Relevant features were extracted or engineered from the cleaned data.
    Examples:
     * User-based features: User's past orders, ratings, preferred cuisines.
     * Restaurant-based features: Cuisine, location, price range, ratings, reviews.
     * Contextual features: Time of day, day of the week, special occasions.
 2. Recommendation Algorithms:
   1. Collaborative Filtering:
     * User-based: Recommends restaurants based on the preferences of similar users.
     * Item-based: Recommends restaurants similar to those the user has liked in the past.
   2. Content-Based Filtering: Recommends restaurants based on user preferences for specific attributes (e.g., cuisine, location, price range).
   3. Hybrid Approaches: Combine collaborative and content-based filtering for improved accuracy.
 3. Model Evaluation:
    The performance of the recommendation models was evaluated using appropriate metrics:
     * Precision, Recall, F1-score
     * Mean Squared Error (MSE)
     * Root Mean Squared Error (RMSE)
     
Implementation:
 * Programming Language: Python
 * Libraries: Pandas, NumPy, seaborn, matplotlib, CountVectorizer, TfidfVectorizer
 * Tools: Jupyter Notebook

Text Preprocessing
  1. Lower casing
  2. Removal of Punctuations
  3. Removal of Stopwords
  4. Removal of URLs
  5. Spelling correction
     
Project Structure:
 * data/: Contains the raw and cleaned Zomato dataset.
 * notebooks/: Contains Jupyter Notebooks for data cleaning, analysis, and model development.
 * src/: Contains Python scripts for data preprocessing, model training, and evaluation.
 * models/: Stores trained recommendation models.
 * README.md: This file.
   
Future Work:
 * Incorporate real-time user feedback to refine recommendations.
 * Develop a user interface for an interactive recommendation system.
 * Explore more advanced recommendation algorithms, such as deep learning models.
 * Integrate location-based services for personalized recommendations.

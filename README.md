# Clash Royale Victor Prediction 

This project explores and analyzes the "Clash Royale S18 Ladder Dataset," which provides detailed match data from the popular mobile game Clash Royale. The dataset contains information such as player stats, card details, elixir usage, and battle outcomes. 

## Dataset Details
- Source: [Clash Royale S18 Dataset on Kaggle](https://www.kaggle.com/datasets/bwandowando/clash-royale-season-18-dec-0320-dataset?resource=download) 

## Objective
To predict the winner of a match based on the player's resource usage and other gameplay metrics.

## Pipeline and Process
### 1. Data Processing
- Tools Used: Google Cloud Platform, Buckets, Dataproc, PySpark 
- Steps:
  - Loaded data onto Google Cloud Platform.
  - Cleaned data by fixing missing values and dropping unnecessary columns.
  - Standardized numerical features to ensure consistency.
  - Assembled features into a single vector for the model.

### 2. Feature Engineering & Modeling
   - Extracted and combined relevant features from the dataset.
   - Applied one hot encoding for categorical variables.
   - Scaled numerical features using MinMaxScaler.
   - Model Used: Logistic Regression for binary classification.
   
### 3. Visualizations
- Bar chart & Scatter plot comparing average elixir consumption of winners and losers.
- Pie chart showing trophy standings between winners and losers.
- Correlation matrix identifying relationships between key features.

### Key Takeaways
- Winning Factors: Higher starting trophies and elixir averages were significant indicators of success.
- Challenges: Moderate accuracy due to variability in gameplay mechanics.
- Opportunities: Improving feature engineering and testing advanced algorithms could enhance predictions.

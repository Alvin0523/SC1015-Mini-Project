# SC1015_MINI-PROJECT_FCS3_GROUP-9
# Taylor Swift Spotify Stream Count

## Introduction
This project focuses on predicting the stream count for Taylor Swift's songs on Spotify. By leveraging machine learning techniques, we aim to develop models that provide accurate forecasts, facilitating strategic decision-making in music marketing.

## Data Sources
The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com), containing detailed features of Taylor Swift's Spotify songs. Additionally, we utilize data from [Kworb.net](https://kworb.net/spotify/artist/06HL4z0CvFAxyc27GXpf02_songs.html) for supplementary information.

## Data Preparation and Features
We begin by importing necessary libraries and merging the datasets to enrich our data. Key features such as acousticness, instrumentalness, and popularity are retained, while others like track number and release date are removed for model simplicity.

## Feature Engineering
To enhance our predictive models, we introduce composite features like mood score and rhythm index, along with date-based features extracted from the release date. These additions aim to capture nuanced aspects of the songs and their release timing.

## Exploratory Analysis and Visualizations
We conduct exploratory data analysis to understand the distribution and relationships between features and stream counts. Visualizations help identify trends and patterns, guiding our feature selection and model development process.

## Machine Learning Models
### 1. Random Forest Regressor
We utilize the Random Forest algorithm due to its robustness and ability to handle non-linear data. After training the model, we evaluate its performance using metrics such as Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE).

### 2. XGBoost Regressor
XGBoost is chosen for its gradient boosting framework, optimizing accuracy and computational efficiency. Similar to Random Forest, we train the XGBoost model and assess its performance against the same metrics.

## Model Comparison and Evaluation
We compare the performance of both models, considering metrics like RMSE, MAE, and error ratios. Visualizations further illustrate the actual vs. predicted stream counts, providing insights into model effectiveness.

## Recommendations and Future Work
To further improve predictive accuracy and uncover insights, we propose several avenues for future exploration, including feature engineering, hyperparameter tuning, ensemble methods, and model interpretability techniques.

## Contributors
- Venkatesh Arun Moorthy
- Wong Wei Ming


## References
- Kaggle: [Taylor Swift Spotify Songs Dataset](https://www.kaggle.com)
- Kworb.net: [Taylor Swift Spotify Song Information](https://kworb.net/spotify/artist/06HL4z0CvFAxyc27GXpf02_songs.html)


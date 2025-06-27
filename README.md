# Climate-Change-Nasa

This data set encompasses over 500 user comments collected from high-performing  posts on NASA's Face book page dedicated to climate change  (https://web.facebook.com/NASAClimateChange/). The comments, gathered from  various posts between 2020 and 2023, offer adiverse range of public opinions and  sentiments about climate change and NASA's related activities.

# Data Science Applications

 Despite not being a large dataset, it offers valuable opportunities for analysis and
 Natural Language Processing (NLP). Potential applications include:
 ● Sentiment Analysis: Gauge public opinion on climate change and NASA's
 communication strategies.
 ● Trend Analysis: Identify shifts in public sentiment over the specified period.
 ● Engagement Analysis: Understand the correlation between the content of a
 post and user engagement.
 ● Topic Modeling: Discover prevalent themes in public discourse about climate
 change.

 # Column Descriptors
 
 1. Date: The date and time when the comment was posted.
 2. LikesCount: The number of likes each comment received.
 3. ProfileName: The anonymized name of the user who posted the comment.
 4. CommentsCount: The number of responses each comment received.
 5. Text: The actual text content of the comment.

 # Ethical Considerations and Data Privacy

 All profile names in this dataset have been hashed using SHA-256 to ensure privacy
 while maintaining data usability. This approach aligns with ethical data mining
 practices, ensuring that individual privacy is respected without compromising the
 dataset's analytical value

 # Climate Change Modeling Machine Learning Project
 
 ## Project Overview
 
 The Climate Change Modeling project aims to develop a machine learning model to
 predict and understand various aspects of climate change. This can include predicting
 temperature changes, sea level rise, extreme weather events, and other related
 phenomena. The project involves analyzing historical climate data, identifying trends,
 and making future projections to help in planning and mitigation efforts.
 
 # Project Steps
 
 1. Understanding the Problem
 The goal is to predict and model various climate change indicators, such as temperature anomalies, precipitation patterns, and sea level changes, using historical climate data and machine learning techniques.
 2. Dataset Preparation
 Data Sources: Collect data from sources like NOAA (National Oceanic and Atmospheric Administration), NASA, IPCC (Intergovernmental Panel on Climate Change), and other climate research organizations.
 Features: Include variables like temperature, precipitation, CO2 levels, solar radiation, sea level, and other relevant environmental factors.
 Labels: Climate change indicators such as temperature anomalies, sea level rise, frequency of extreme weather events.
 3. Data Exploration and Visualization
 Loadand explore the dataset using descriptive statistics and visualization techniques.
 Uselibraries like Pandas for data manipulation and Matplotlib/Seaborn for visualization.
 Identify trends, patterns, and correlations in the data.
 4. Data Preprocessing
 Handle missing values through imputation or removal.
 Standardize or normalize continuous features.
 Encode categorical variables using techniques like one-hot encoding.
 Split the dataset into training, validation, and testing sets.
 5. Feature Engineering
 Create new features that may be useful for prediction, such as rolling averages or lagged variables.
 Perform feature selection to identify the most relevant features for the model.
 6. Model Selection and Training
 Choose appropriate machine learning algorithms based on the problem.
 
 # Common choices include:
 
 ■ Linear Regression
 ■ Decision Trees
 ■ RandomForest
 ■ Gradient Boosting Machines (e.g., XGBoost)
 ■ Neural Networks
 ■ LongShort-Term Memory (LSTM) networks for time series data
 Train multiple models to find the best-performing one.
 7. Model Evaluation
 Evaluate the models using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.
 Usecross-validation to ensure the model generalizes well to unseen data.
 Visualize model performance using plots like residual plots and predicted vs. actual plots.
 8. Future Projections
Usethe trained model to make future projections of climate change indicators.
Validate the projections using available data and compare them with scientific forecasts and models.
 9. Scenario Analysis
 Conduct scenario analysis to understand the impact of different factors (e.g., CO2 emission scenarios) on climate change.
 Usethe model to simulate different scenarios and assess their potential impact.
 10. Deployment (Optional)
 Deploy the model using a web framework like Flask or Django.
 Create a user-friendly interface where users can input data and receive climate change predictions and scenarios.
 11. Documentation and Reporting
 Document the entire process, including data exploration, preprocessing, feature engineering, model training, evaluation, and projections.
 Create a final report or presentation summarizing the project, results, and insights.

## ✅ Conclusion

This project effectively analyzed public perception and engagement with climate change content on NASA’s Facebook page between 2020 and 2023. By
examining over 500 user comments, we gained valuable insights into how people emotionally and socially respond to climate-related posts.

Key outcomes include:

Sentiment Analysis using TextBlob revealed a wide spectrum of opinions. While many comments reflected concern and urgency, there was also skepticism and 
misinformation present, highlighting the complexity of public discourse on climate change.

Engagement Patterns showed a strong correlation between sentiment and user interactions (likes and comments), suggesting emotionally charged content— 
positive or negative—tends to drive more engagement.

Topic Modeling (LDA) uncovered major discussion themes such as global warming denial, renewable energy, extreme weather, and NASA’s climate initiatives.

A Random Forest regression model was trained to predict comment volume based on sentiment and likes, achieving reasonable performance with metrics like 
MSE and R².

A Flask web application was successfully deployed, enabling users to input a comment and receive real-time predictions of sentiment and expected 
engagement.

This project demonstrates how data analytics and natural language processing (NLP) can uncover trends in online public opinion and support science 
communicators like NASA in understanding their audience better.

🔭 Future Work

* Enhance sentiment analysis using deep learning models (e.g., BERT) for better nuance.

* Integrate reaction types (love, angry, sad) to refine emotional impact analysis.

* Scale up analysis with more posts and multilingual content.

* Use time-series modeling to track sentiment evolution over time.

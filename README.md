This project aims to analyze traffic flow data to identify patterns, predict traffic conditions, and provide actionable insights for stakeholders.

The analysis involves exploratory data analysis (EDA) and machine learning models to achieve these objectives.

Preprocessing: The Time and Date columns are converted to appropriate formats, and relevant features like Hour, Month, and Day are extracted.

Label Encoding: Categorical features like Day of the week and Traffic Situation are encoded to numerical values.

Feature Selection: The features (Time, Day of the week, CarCount, etc.) are selected for training.

Model Training: A RandomForestClassifier is used to predict the traffic situation.

Evaluation: The model’s performance is evaluated using confusion matrix, classification report, and accuracy score.

Feature Importance: A plot showing the importance of each feature in predicting the traffic situation is generated.

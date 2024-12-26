Credit Card Delinquency Prediction
This project aims to predict credit card delinquency using machine learning models, specifically Decision Tree and Random Forest classifiers. The dataset includes various features such as card category, annual fees, customer acquisition cost, credit limit, and others. The target variable is whether a customer has a delinquent account or not. 🔍

📊 Exploratory Data Analysis (EDA)
Visualized the distribution of delinquent accounts with a count plot.
Analyzed the distribution of card categories and the most popular card type using a pie chart.
Investigated the relationship between credit limit and card category using a box plot.
Explored the annual fees distribution and interest earned against acquisition costs through scatter and bar plots.
🧹 Data Preprocessing
Dropped irrelevant columns like Client_Num, Activation_30_Days, and others.
Encoded categorical features like Card_Category, Use Chip, and Exp Type using Label Encoding.
Applied Random Oversampling to handle class imbalance.
Scaled the features using MinMaxScaler and StandardScaler for improved model performance.
🧠 Machine Learning Models
Built and trained Decision Tree and Random Forest models.
Evaluated models based on accuracy, confusion matrix, and classification report.
Random Forest Classifier outperformed Decision Tree with an accuracy of 94.1%.
📈 Results
The Decision Tree Classifier achieved an accuracy of 84.6%.
The Random Forest Classifier showed a higher accuracy of 94.1%.
🚀 Future Improvements
Explore additional features or advanced models like XGBoost or Neural Networks.
Implement better handling of imbalanced classes with techniques like SMOTE.

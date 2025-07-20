# Portuguese Bank Marketing Campaign Analysis & Prediction
This project analyzes a Portuguese bank's marketing dataset to identify the key factors influencing customer subscription to term deposits. Using data preprocessing, visualization, and machine learning models, the goal is to gain insights and create accurate predictive models to improve marketing strategies.
# Tech Stack
* Languages & Tools: Python, Jupyter Notebook
# Libraries:
* pandas, numpy – Data manipulation & processing
* matplotlib, seaborn – Data visualization
* scikit-learn – Machine learning models & evaluation
* Project Features
✅ Cleaned and preprocessed real-world banking data
📊 Performed Exploratory Data Analysis (EDA) with impactful visualizations
🤖 Built and evaluated classification models
📈 Compared multiple models using ROC-AUC, Recall, and F1-score
🎯 Identified the best model (Random Forest) based on business needs (minimizing false negatives)

Project Workflow
1.Data Collection: Load the dataset from the CSV file.
2.Data Preprocessing: Handle missing values, encode categorical variables, and scale features.
3.Exploratory Data Analysis (EDA): Generate insights with plots and statistical summaries.
4.Model Training: Use classification models to predict customer subscriptions.
5.Evaluation: Assess model performance using metrics like accuracy, precision, recall, and F1 score.

# After the analysis we see that our interest is over decreasing the False Negative means the client SUBSCRIBED to term deposit, but the model said he dont which indicates RECALL. So, we conclude that the model with high RECALL score 88.77% would be best suited for the problem statement i.e.,(Random Forest Classifier)


# SentimentElectionPrediction_DP

   
1. This project explores sentiment-driven election prediction while ensuring privacy using DP. The goal here is to strike a balance between safeguarding user privacy and offering insightful analysis in predicting elections based on the tone of political dialogue by evaluating the use of DP-ML in comparison with other ML models.

2. **Environment:**
**Platform:** Google Colab
**CPU:** Intel Xeon CPU (2 cores)
**RAM:** 12GB

3. **Datasets**
**Election Tweets Dataset:** Hui, M. (2020). US Election 2020 Tweets. Www.kaggle.com. https://www.kaggle.com/datasets/manchunhui/us-election-2020-tweets
**Polling Dataset:** Wiederkehr, R. B., Aaron Bycoffe, Ritchie King, Dhrumil Mehta and Anna. (2018, June 28). President: general election : 2020 Polls. FiveThirtyEight. https://projects.fivethirtyeight.com/polls/president-general/2020/

4. **Project Structure Overview**
4.1 **Notebooks/Modeling/:** Contains notebooks for various machine learning models, including baseline models (Naive Bayes, Random Forest, Logistic Regression and DP models). 
****Baseline_Naive_Bayes.ipynb:** **Baseline sentiment analysis using Naive Bayes.
**Baseline_Random_Forest.ipynb:** Baseline sentiment analysis using Random Forest.
**Logistic_Regression_Model.ipynb:** Logistic Regression model for sentiment classification.
**LR_dp_sgd_eps_0_1.ipynb, LR_dp_sgd_eps_1.ipynb, LR_dp_sgd_eps_7_.ipynb:** Experiments to integrate DP into Logistic Regression.

4.2 **Notebooks/Data preprocessing/:** This folder includes notebooks for preprocessing the dataset. It handles data cleaning, transformation, and saving the processed datasets to CSV files.
**Polling_data_preprocessing.ipynb:** Preprocessing related to polling data (if applicable).
**Preprocessing_Trump_Biden_df.ipynb:** Preprocessing related to the Trump-Biden dataset.

4.3 **Notebooks/Exploratory Data Analysis/**: Notebooks for exploring and visualizing the dataset to better understand the data's structure and distribution.
**EDA_of_POLLING DATA.ipynb:** Exploratory data analysis of polling data.
**Trump__Biden_Exploratorydata_analysis.ipynb:** EDA specific to Trump-Biden tweets.

5. **Folder and File Descriptions:**
**Notebooks/Modeling/**: Contains notebooks related to sentiment analysis models and their evaluations.
**Notebooks/Data Preprocessing/:** Includes code for preprocessing the dataset and saving it for further analysis.
**Notebooks/Exploratory Data Analysis/:** Contains exploratory data analysis notebooks for understanding the data.

6. **Comparison_of_Models.ipynb:** Comparing the performance of the different models implemented.

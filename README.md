# hate-tweet
<h1>Mitigating Online Harms: Hate Speech Detection in Tweets using Machine Learning and Natural Language Processing</h1>
<h2>Authors’ Name: Shamie Dasgupta, Aishani Dey, Pratyusha Mukhopadhyay, Protim Mandal</h2>
<p>In this study, we have employed two distinct datasets to conduct our analysis. The primary dataset utilized for training purposes comprises 32,000 entries, each possessing three pivotal columns: 'ID', 'Tweet', and 'Label'.</p>
<p>In our study, we diligently pursued feature engineering to enhance our understanding of tweet characteristics and their potential influence on classification. We derived various features from the tweet corpus, encompassing tweet length, hashtag count, exclamation marks, question marks, tags, punctuations, and word count.</p>
<p>One significant challenge we encountered with the dataset was its high imbalance, notably visible in the pie chart, where only 7% of the data was labeled as hate tweets.  To address this issue, we employed a technique known as Synthetic Minority Oversampling Technique (SMOTE). </p>
<p>We undertook an extensive model evaluation phase, fitting four distinct models: Logistic Regression, Naïve Bayes Classifier, Random Forest Classifier, and Gradient Boosting Classifier.
However, upon closer analysis, we observed a concerning phenomenon regarding the F1 scores. The F1 score for the training data with the Random Forest model was unusually high, reaching a perfect 100%. Conversely, the Gradient Boosting model displayed an F1 score around 94% for the training data, indicating potential issues of overfitting and underfitting, respectively.
</p>
<p>Following rigorous experimentation with various combinations of hyperparameters, we successfully addressed the issues of overfitting and underfitting. The final model that emerged as the most effective was the Random Forest Classifier, boasting an impressive validation F1 score of 71%.</p>

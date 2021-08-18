# Amazon-food-reviews

### Problem: 
      
The challenge is to develop a machine learning model that would classify a given food review into 
one of the two categories, positive review or negative review, with high precision and recall. 
A 'rating' attribute was provided for each review with values 1 to 5, which I have used as class label for performing
supervised training and predicting the class labels for test dataset. 
It's is a classic sentiment analysis problem, means that for every food review, the polarity of it has to be predicted.</p>
      
<h3> Data: </h3> 
<p>The Amazon Fine Food Reviews data is distributed across 2 categories with around 0.56 million reviews. 
        Each record in the dataset has information about the user, review text, timestamp of the review etc.</p>
    
      

<h3> Approach: </h3>
<ul>
        <li>Performed Exploratory Data Analysis(EDA) on Amazon Fine Food Reviews Dataset and drew helpful insights by plotting Word Clouds, Distplots, Histograms, etc.</li>
        <li>Performed Data Cleaning & Data Preprocessing by removing unnecessary and duplicates rows and for text reviews removed HTML tags, punctuations, Stopwords and Stemmed the words using Porter Stemmer</li>
        <li>Plotted TSNE plots for Different Featurization of Data viz. BOW(uni-gram), TF-IDF, Avg-Word2Vec and TF-IDF-Word2Vec</li>
        <li>Build machine learning models</li>
      </ul>  

<h3> Models: </h3>
      <p>Applied the following machine learning models on Different Featurization of Data viz. BOW(uni-gram), tfidf, Avg-Word2Vec and tf-idf-Word2Vec</p>
        <ul> 
          <li>K-Nearest Neighbours</li>
          <li>Naive Bayes</li>
          <li>Logistic Regression</li>
          <li>Decision Tree</li>
          <li>Random Forest</li>
          <li>XGBoost and</li>
          <li>Recurrent Neural Networks(LSTM)</li>
        </ul>
      
<b>Technologies Used:</b> Machine Learning, Python
<br> 

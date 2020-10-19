# Sentiment Analysis using Naive Bayes
This sentiment analysis involved the used of naive bayes algorithms of multinomial, bernoulli, gaussian, categorical and complement and the data set used in this analysis is from imdb movie reviews, yelp reviews and amazon_cells revieeq. The main purpose of this exercise is to know which of the Naive Bayes algorithms is more efficient in analysing sentiment analysis or text classification. Mettrics used are F1-score and Accuracy score.

# Setup for Developers 
We used the Pipenv for creating the virtual environment

The Pipfile  is meant to replace requirements.txt and the Pipfile.lock enables deterministic builds.

Instructions for installing this project on your local machine and getting it running in its own virtual environment.
1.  Clone this project into a new directory - click the clone button above on GitHub to get the link and command to use

2.  Ensure you have `pipenv` installed on your machine - installation  
 documentation can be found [here](https://docs.pipenv.org/en/latest/install)

3.  From the project root directory run
    ```bash 
        pipenv install --dev 
    ```
    to create your virtual environment and install all the packages
    
4.  Activate your virtual environment at any time using 
    ```bash 
        pipenv shell 
    ```
    Note only do this from the project directory root 
    
5.  Deactivate your virtual environment at any time using 
    `exit`
...


# Findings:
### Multinomial Naive Bayes (MultinomialNB)
    With Count Vectorizer the metrics that were achieved in this model are as follows:
        -Maximum Accuracy:   82.55%
        -Minimum Accuracy:   76.36%
        -Mean Accuracy:      79.15%
        -Standard Deviation: 0.0230
        
    With TfidfVectorizer the metrics that were achieved in this model are as follows:
        -Maximum Accuracy:   83.27%
        -Minimum Accuracy:   78.18%
        -Mean Accuracy:      80.17%
        -Standard Deviation: 0.0186

Click [Multinomial Naive Bayes](https://github.com/dhrey112/sentimentAnalysis-5_Naive_Bayes_model/blob/master/Sentiment-Analysis-with-multinomialNB.ipynb) to check
      
### Bernoulli Naive Bayes (BernoulliNB)
     With Count Vectorizer the metrics that were achieved in this model are as follows:
        -Maximum Accuracy:   82.18%
        -Minimum Accuracy:   76.00%
        -Mean Accuracy:      78.89%
        -Standard Deviation: 0.0193
        
    With TfidfVectorizer the metrics that were achieved in this model are as follows:
        -Maximum Accuracy:   82.18%
        -Minimum Accuracy:   76.00%
        -Mean Accuracy:      78.89%
        -Standard Deviation: 0.0193     
Click [Bernoulli Naive Bayes](https://github.com/dhrey112/sentimentAnalysis-5_Naive_Bayes_model/blob/master/Sentiment-Analysis-with-BernoulliNB.ipynb) to check
    
### Complement Naive Bayes (ComplementNB)
    With Count Vectorizer the metrics that were achieved in this model are as follows:
        -Maximum Accuracy:   82.91%
        -Minimum Accuracy:   76.00%
        -Mean Accuracy:      79.55%
        -Standard Deviation: 0.0242
      
    With TfidfVectorizer the metrics that were achieved in this model are as follows:
        -Maximum Accuracy:   84.36%
        -Minimum Accuracy:   78.91%
        -Mean Accuracy:      80.68%
        -Standard Deviation: 0.0191       
Click [Complement Naive Bayes](https://github.com/dhrey112/sentimentAnalysis-5_Naive_Bayes_model/blob/master/Sentiment-Analysis-with-ComplementNB.ipynb) to check
  
### Categorical Naive Bayes (CategoricalNB)
    With Count Vectorizer the metrics that were achieved in this model are as follows:
        -Maximum Accuracy:   83.94%
        -Minimum Accuracy:   77.45%
        -Mean Accuracy:      79.88%
        -Standard Deviation: 0.0204
        
Note: It is difficult to carryout TFIDF with Categorical Naive Bayes, any contributor can help on this.     

Click [Categorical Naive Bayes](https://github.com/dhrey112/sentimentAnalysis-5_Naive_Bayes_model/blob/master/Sentiment-Analysis-with-CategoricalNB.ipynb) to check
    
### Gaussian Naive Bayes (GaussianNB)
    With Count Vectorizer the metrics that were achieved in this model are as follows:
        -Maximum Accuracy:   72.63%
        -Minimum Accuracy:   61.82%
        -Mean Accuracy:      66.12%
        -Standard Deviation: 0.0309

    With TfidfVectorizer the metrics that were achieved in this model are as follows:
        -Maximum Accuracy:   71.64%
        -Minimum Accuracy:   64.00%
        -Mean Accuracy:      67.94%
        -Standard Deviation: 0.0184
Click [GaussianNB Naive Bayes](https://github.com/dhrey112/sentimentAnalysis-5_Naive_Bayes_model/blob/master/Sentiment-Analysis-with-GaussianNB.ipynb) to check

## Summary
 With insights derived from the five naive bayes algorithm models, we concluded that the complement naive bayes algorithm with TFIDF and Categorical naives bayes with CountVectorizer are more efficient when analysing sentiment. One can consider starting from there before employing any other algorithm in project related to the subject matter.
 

#### References
 [Data Flair](https://data-flair.training/)
 
 [Towards Data Science](https://towardsdatascience.com)
 
 [Semicolon Machine Learning Community](https://semicolon.africa)
 
 [Google Machine Learning Developer](https://developers.google.com/machine-learning)
 
 [Pipenv Guide](https://realpython.com/pipenv-guide/)
 
## Contributors welcome!!!
[Machine Learning]()

```bash
To Talent and Innovation
```
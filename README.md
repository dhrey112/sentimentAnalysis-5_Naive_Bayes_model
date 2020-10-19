# Sentiment Analysis using Naive Bayes
This sentiment analysis involved the used of naive bayes algorithms of multinomial, bernoulli, gaussian, categorical and complement and the data set used in this analysis is from imdb movie reviews. The main purpose of this exercise is to know which of the Naive Bayes algorithms is more efficient in analysing sentiment analysis or text classification. Mettrics used are F1-score and Accuracy score.

# Setup for Developers 
I used the new Pipenv for creating the virtual environment

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
        -F1-Score:   74.13%
        -Accuracy-Score:   75.17%
    
    With TfidfVectorizer the metrics that were achieved in this model are as follows:
        -F1-Score:   75.64%
        -Accuracy-Score:   74.50% 

Click [Multinomial Naive Bayes](https://github.com/dhrey112/sentimentAnalysis-5_Naive_Bayes_model/blob/master/Sentiment-Analysis-with-MultinomialNB.ipynb) to check
      
### Bernoulli Naive Bayes (BernoulliNB)
    With Count Vectorizer the metrics that were achieved in this model are as follows:
        -F1-Score:   73.56%
        -Accuracy-Score:   68.92%

    With TfidfVectorizer the metrics that were achieved in this model are as follows:
        -F1-Score:   73.56%
        -Accuracy-Score:   68.92%
        
Click [Bernoulli Naive Bayes](https://github.com/dhrey112/sentimentAnalysis-5_Naive_Bayes_model/blob/master/Sentiment-Analysis-with-BernoulliNB.ipynb) to check
    
### Complement Naive Bayes (ComplementNB)
    With Count Vectorizer the metrics that were achieved in this model are as follows:
        -F1-Score:   78.38%
        -Accuracy-Score:   78.38%
      
    With TfidfVectorizer the metrics that were achieved in this model are as follows:
        -F1-Score:   80.52%
        -Accuracy-Score:   79.73%
        
Click [Complement Naive Bayes](https://github.com/dhrey112/sentimentAnalysis-5_Naive_Bayes_model/blob/master/Sentiment-Analysis-with-ComplementNB.ipynb) to check
  
### Categorical Naive Bayes (CategoricalNB)
    With Count Vectorizer the metrics that were achieved in this model are as follows:
        -F1-Score:   80.00%
        -Accuracy-Score:   77.03%

    With TfidfVectorizer the metrics that were achieved in this model are as follows:
        -F1-Score:   80.00%
        -Accuracy-Score:   77.03%

Click [Categorical Naive Bayes](https://github.com/dhrey112/sentimentAnalysis-5_Naive_Bayes_model/blob/master/Sentiment-Analysis-with-CategoricalNB.ipynb) to check
    
### Gaussian Naive Bayes (GaussianNB)
    With Count Vectorizer the metrics that were achieved in this model are as follows:
        -F1-Score:   70.24%
        -Accuracy-Score:   66.44%

    With TfidfVectorizer the metrics that were achieved in this model are as follows:
        -F1-Score:   69.62%
        -Accuracy-Score:   67.79%

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
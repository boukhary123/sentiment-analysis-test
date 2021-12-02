# Sentiment Analysis Test

- [Sentiment Analysis Test](#sentiment-analysis-test)
  - [🎯 Goals](#user-content--goals)
  - [📊 Datasets](#user-content--datasets)
  - [📖 Rules](#user-content--rules)
  - [👩‍💻 What to do](#user-content--what-to-do)

## 🎯 Goals

We want a multilingual text classifier that predicts the sentiment polarity of a given text.
Build two models that satisfy this task and choose the best one.
Please explain in detail each choice you made when building your models and how you choose the best one.

Possible sentiments:
* `positive`
* `negative`
* `neutral`

## 📊 Datasets

* `data/train.csv`: a training dataset containing 25k multilingual texts annotated with their corresponding sentiment
* `data/test.csv`: a test dataset containing 2500 multilingual texts

## 📖 Rules

* Code should be written in Python 3
* Code should be easily runnable, provide a pip requirements.txt file or a conda environment.yml file describing code dependencies
* Code should be documented to explain your methodology, choices, and how to run and get results
* Code should output a file `predictions.csv`, containing the predictions of your best classifier on the test dataset

## 👩‍💻 What to do

1. Fork the project via `github`
2. Clone your forked repository project https://github.com/YOUR_USERNAME/sentiment-analysis-test
3. Commit and push your different modifications
4. Send us a link to your fork once you're done!

# Files
All work is self contained in the jupyter notebook test.ipynb.
First part is installations in the google colab environment. Second part is preparring data and traning, running models on validation data. Third part is loading best saved model and generating predictions.
To generate models it is sufficient to run notebook in the order of their appearance. If using local machine the installation part can be skipped and the paths should be modified accordingly.
The final predictions generated are in the directory ./data/predictions.csv.

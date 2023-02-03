# DeepLearningProject

This project is implemented in a number of notebooks:
## Part 1 - comparison between VADER and pretrained BERT Models:
1- ro-BERT-a Vs VADER.ipynb : This notebook contains the comparison between the performance of VADER and ro-BERT-a pretrained model on the 2 datasets used: 10k dataset (split to train: 9K and test: 1K) and 6K dataset

2- VADER VS. DistilBERT with Logistic Regression.ipynb: This notebook contains the comparison between the performance of VADER and DistilBERT with Logistic Regression model on the 2 datasets used: 10k dataset (split to train: 9K and test: 1K) and 6K dataset

## Part 2- Finetuned Model and comparison between The perfromance of the Finetuned model, LSTM Baseline model, and Bi-LSTM Baseline model:
### a) on the 10K dataset for validating the finetuning efficiency:
1- Covid_19_Vacciene_Sentiment_Analysis_using_BERT_on_10K.ipynb: In this notebook, the data is labeled. We train our finetuned-BERT model and compare it to the baseline LSTM and BILSTM models presented in the baseline paper.

### b) on the baseline/ original dataset used by the baseline paper to find the best combination of models to perform this task:
1 - Covid_19_Vacciene_Sentiment_Analysis_using_BERT_on_labeled_Original_DS.ipynb :  In this notebook we label the data using ro-BERT-a and use the fine-tuned Bert Model to evaluate the sentiment analysis results in compared to the baseline LSTM and BILSTM models presented in the baseline paper.

2- Covid_19_Vacciene_Sentiment_Analysis_using_BERT_on_Original_DS.ipynb:  In this notebook we label the data using VADER and use the fine-tuned Bert Model to evaluate the sentiment analysis results in compared to the baseline LSTM and BILSTM models presented in the baseline paper.


# The Datasets:

There are 3 datasets used in this project:

1- Baseline / Original dataset used by the paper: https://www.kaggle.com/datasets/gpreda/all-covid19-vaccines-tweets

2- 10K manually labelled dataset: https://www.kaggle.com/datasets/trinhngocphap/covid19-vaccine-tweets-sentiment-10k

3- 6k labelled dataset: https://www.kaggle.com/datasets/datasciencetool/covid19-vaccine-tweets-with-sentiment-annotation
 

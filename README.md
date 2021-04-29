# AssessingHeadlinesFunniness

This repo contains notebooks used to analyze the funniness of edited newspaper headlines, it was done as coursework for our Natural Language Processing course along with two coursemates of mine. Many techniques have been used ranging from more classical bag of words approaches to statistical ML models (Random Forests, SVMs, Boosting etc.) and DL models (RNNs, Transformers). For a thourough overview of our methods and results refer to ```report.pdf```.

## notebook instructions

This Google Drive folder contains three Jupyter notebooks:

Run all cells in the notebook data_analysis.ipynb to replicate our data analysis results described in Section 4 of the report.

Run all cells in the notebook main.ipynb to train and test the statistical ML models and the DL models described in Section 5 of the report (both for Approach 1 and Approach 2).

Run all cells in the notebook BoW_models.ipynb to train and test the BoW models described in subsection 5.3 of the report.


## dataset instructions

We used 90% of the train set (train.csv) for training and 10% for validation.

The final tests in the notebooks are performed on the labelled version of the file dev.csv. 

Before running the code, download this labelled version of dev.csv from the subfolder <data/task-1/> within this Google Drive folder. 

Make sure it is located so that it can be retrieved by the following line in the code:
>>> test_df = pd.read_csv('data/task-1/dev.csv')


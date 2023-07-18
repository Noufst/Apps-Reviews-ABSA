
# Aspect-Based Sentiment Analysis of Apps Reviews

This is a replication package of the paper: **An Automated Approach to Aspect-Based Sentiment Analysis (ABSA) of Apps Reviews Using Machine and Deep Learning**
 
 In this paper,  we built ABSA models using supervised Machine Learning (ML) and Deep Learning (DL) approaches.  
Our automated technique is intended to (1) identify the most useful and effective text-representation and task-specific features in both Aspect Category Detection (ACD) and Aspect Category Polarity (ACP), (2)  empirically investigate the performance of conventional ML models when utilized for ABSA task of apps reviews, and (3) empirically compare  the performance of ML models and DL models in the context of ABSA task.

## Prerequisites
-   Python 3.8.16
-   numpy 1.21.2
-   pandas 1.5.3
-   scikit-learn 1.0.1
-   transformers 4.27.4
-   keras-tuner 1.1.3
-  nltk 3.6.1
-   imblearn 0.9.1
 
## Content

The below table describes the functionality of each file. Each file can be run independently based on one's needs. 

| File        | Task           | Model  |
| ------------- |:-------------:| -----:|
| ACD_BERT.ipynb      | Aspect Category Detection (ACD) | BERT |
| ACD_LSTM_CNN.ipynb     | Aspect Category Detection (ACD)      |   LSTM and CNN |
| ACD_ML.ipynb | Aspect Category Detection (ACD)      |    Decision Trees (DT) using CART algorithm, Gaussian Naive Bayes (GNB), K-Nearest Neighbour (KNN), Logistic Regression (LR), Multilayer Perceptron (MLP), and Support Vector Machine (SVM) |
| ACP_BERT.ipynb      | Aspect Category Polarity (ACP) | BERT |
| ACP_LSTM_CNN.ipynb     | Aspect Category Polarity (ACP)      |   LSTM and CNN |
| ACP_ML.ipynb | Aspect Category Polarity (ACP)      |    Decision Trees (DT) using CART algorithm, Gaussian Naive Bayes (GNB), K-Nearest Neighbour (KNN), Logistic Regression (LR), Multilayer Perceptron (MLP), and Support Vector Machine (SVM) |

## Dataset
The dataset used in this work is called **AWARE**: **A**BSA **W**arehouse of **A**pps **RE**views. Direct links to the dataset are included in the code, so it is not necessary to handle the dataset separately. However, the dataset is publicly available at [Zenodo](https://zenodo.org/record/5528481). We kindly ask you to cite the dataset if you wish to use it.

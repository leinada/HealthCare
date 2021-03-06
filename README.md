## Healthcare related projects are  in this directory

### MIMIC EHR data analysis
--------------------------------------------------------------
- Predict which patients are at risk for 30-day unplanned readmission with the help of hospital discharge summaries. 
- Analysis notebook [here](https://nbviewer.jupyter.org/github/leinada/HealthCare/blob/master/readmission/readmission.ipynb)
- Analysis includes
  * Data wrangling
  * Exploratory analysis of the data.
  * Preprocessing of text data (tokenizer, vectorizer, stop word removal, ...)
  * Hyper parameter tuning, feature importance extraction
  * Training and validation of model using different ML algos

### COVID 19 analysis
--------------------------------------------------------------
- Applied time series analysis using fbprophet to predict the death count for the next 30 days 


- Main analysis notebook [here](https://nbviewer.jupyter.org/github/leinada/HealthCare/blob/master/covid19/covid_eda_predictions_g.ipynb)
- Notebook with some EDA [here](https://nbviewer.jupyter.org/github/leinada/HealthCare/blob/master/covid19/covid_plotly_g.ipynb)

- Analysis includes

  * Data wrangling
  * Exploratory analysis of the data.
  * Time series analysis using fbprophet

#### Cancer classification basd on micro array Gene Expression
----------------------------------------------------------------
- Apply deep learning techniques to perform cancer Classification ased on Microarray Gene Expression Data. Notebook [here](https://github.com/leinada/HealthCare/blob/master/cancerClassification_geneMicroArray/cancerClassification_microArrayGeneExpressionData_KERAS.ipynb)
- This project requires Python 3.x, NumPy,Pandas, matplotlib,sklearn, KERAS libraries
- Analysis includes
  * preprocessing of the data,  scaling of features and encoding, training and validation of model training using KERAS
#### Breast Cancer Prediction
---------------------------------------------------------------
- Prediction of benign and malignant breast cancer using data mining techniques. This analysis aims to observe which features are most helpful in predicting malignant or benign breast cancer (data from UCI machine learning repository)
- Analysis includes (notebook [here](https://github.com/leinada/HealthCare/blob/master/breastCancer/BCD_differentAlgos.ipynb))
  * preprocessing of the data,  training and validation of model using different ML algos such as KNN, Random Forest, SVC, Decision tree, ...
#### Diabetes Prediction
----------------------------------------------------------------
- Goal is to predict the onset of diabetes in Pima Indians within five years using different ML techniques.
- Analysis include. Note book [here](https://github.com/leinada/HealthCare/blob/master/diabetes_prediction/diabetes.ipynb) 
   * preprocessing, classification report, ROC curve
   * Logistic regression, XGBoost
   * Keras (Grid search on batch size, number of epochs, learning rate, dropout rate , diferent kernels, activation functions, number of neurons in each hidden layer)
#### DNA classification
----------------------------------------------------------------
- Analysis of DNA gene sequence. E. coli promoter gene sequences (DNA) with associated imperfect domain theory. Data from UCI repositary
-  Analysis include (note book [here](https://github.com/leinada/HealthCare/blob/master/DNAclassification/dnaSeqClassification.ipynb))
   * preprocessing, training and validation of model using different ML algos such as KNN, Random Forest, SVC, AdaBoost
   
   

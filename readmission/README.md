### MIMIC EHR data analysis
--------------------------------------------------------------
- Predict which patients are at risk for 30-day unplanned readmission with the help of hospital discharge summaries. 
- Data are from MIMIC database. This database contains de-identified data from over 50,000 patients who were admitted to Beth Israel Deaconess Medical Center in Boston
- Data are available at https://mimic.physionet.org/gettingstarted/access/, which needs permission to download.

- Analysis notebook [here](https://nbviewer.jupyter.org/github/leinada/HealthCare/blob/master/readmission/readmission.ipynb)

- Analysis includes

  * Data wrangling
  * Exploratory analysis of the data.
  * Preprocessing of text data (tokenizer, vectorizer, stop word removal, ...)
  * Hyper parameter tuning, feature importance extraction
  * Training and validation of model using different ML algos

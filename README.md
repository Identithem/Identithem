# Identithem: anomaly detection with LSTM and unsupervised Machine Learning methods
This is Identithem, a project created to help companies detect malicious users when they enter their websites, analyze patterns on their behavior and prevent them from doing wrong.
## Github structure
- Code
  - Data_preprocessing_Identithem.ipynb: code to extract the numerical features of the loglines.
  - Unsupervised_learning.ipynb: code to use unsupervised learning methods to extract normal log lines to train the LSTM.
  - LTSM_model.ipynb: the LSTM model, that uses normal logs to train and all loglines from days 20240123, 20240124, 20240125, 20240126 to obtain the final scores.
  - analyze_request.py: .py file 
- Data
  - SitgesLogs.zip: original .log files, where each line of each file is a log line.
  - full_blacklist_database.txt: txt file with a list of IPs that belong to a blacklist. Extracted from this [website](https://myip.ms/browse/blacklist/Blacklist_IP_Blacklist_IP_Addresses_Live_Database_Real-time).
  - loglines_index.zip: a .csv file with the loglines of files from days 20240123, 20240124, 20240125, 20240126 as a data frame.
  - preprocessed_logs.zip: a .csv file with the features extracted of files from days 20240123, 20240124, 20240125, 20240126.
  - normal_logs.zip: a .csv file with the normal logs obtained from the unsupervised learning methods.
  - ...


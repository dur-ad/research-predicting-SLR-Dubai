# research-predicting-SLR-Dubai

This repository contains the code and resources used for the paper titled "Predicting Sea Level Rise Along Dubai’s Coastline by 2050: A Machine Learning and Deep Learning Approach," currently under review. The study uses data from five tide gauge locations in Dubai, spanning from 2004 to 2019, to forecast sea level rise up to 2050 using a combination of machine learning and deep learning techniques.

**Data**

The initial dataset comprises sea level records from five tide gauge locations in Dubai, covering the period from 2004 to 2019. Due to data privacy agreements, the raw data is not included in this repository. 

**Repository Structure**

This repository includes three Jupyter notebooks, each serving a distinct purpose in the research workflow:

1. Data Analysis and Preprocessing
- This notebook covers the initial data exploration, cleaning, and preprocessing steps.
- The data from the five tide gauge locations are analyzed, missing values were handled and smoothening was done.

2. Conv1D-LSTM Model Training 
- This notebook focuses on training a Conv1D-LSTM model for one tide gauge location.
- The model predicts sea level rise up to 2030, based on historical data from 2004 to 2019.
- The same modeling process is used for the remaining four tide gauge locations.
- The notebook includes details on the model architecture, training process, and evaluation metrics.

3. Final Prediction Analysis 
- This notebook provides the final analysis of sea level rise predictions up to 2050.
- The predictions extend beyond the original five tide gauge locations to cover the entire coastline of Dubai.
- The analysis includes visualizations of the predicted sea level rise along Dubai's coastline.

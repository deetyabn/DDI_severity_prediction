# DDI_severity_prediction

This project aims to predict the severity of drug-drug interactions (DDIs) using network characteristics. It was for the Inspirit AI-X 1:1 Mentoring Program. 

The data for this project was a subset of the DDInter database that includes drug pairs and their interaction severity. It can be found here: http://ddinter.scbdd.com/static/media/download/ddinter_downloads_code_L.csv.

This data was used to build a weighted interaction network and create vector embeddings for each drug using the package Node2Vec (A. Grover, J. Leskovec). The list of embeddings for the drugs used in the final model are included here.

Also included is the initial code for the project (DDI_Severity_Prediction_Project) including data visualization and various model testing. The DDI_Project_Cleaner includes model testing and hyperparameter optimization.

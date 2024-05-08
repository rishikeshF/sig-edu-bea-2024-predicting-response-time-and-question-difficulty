
This repository contains the code for the research paper submitted for BEA Shared Task on Automated Prediction of Item Difficulty and Response Time. 
More details: https://sig-edu.org/sharedtask/2024

Abstract: 
In this paper, we present the details of our contribution to the BEA Shared Task on Automated Prediction of Item Difficulty and Response Time. Participants in this collaborative
effort are tasked with developing models to predict the difficulty and response time of multiplechoice items within the medical domain. These items are sourced from the United States Medical Licensing Examination® (USMLE®), a
significant medical assessment. In order to achieve this, we experimented with two featurization techniques, one using lingusitic features and the other using embeddings generated by BERT fine-tuned over MS-MARCO
dataset. Further, we tried several different machine learning models such as Linear Regression, Decision Trees, KNN and Boosting models such as XGBoost and GBDT. We found that
out of all the models we experimented with Random Forest Regressor trained on Linguistic features gave the least root mean squared error, securing fourteenth rank out of 43 for Item Difficulty Prediction and ninth rank out of 34 for
Response Time Prediction. We made our code publicly available in this repository.

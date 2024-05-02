## Attempting Predictions in the Israel-Palestine Conflict: An ML and Econometric Approach 
Arya Amarnath
DSCI 478: Data Science Capstone - Colorado State University
Date: May 2024

Overview
-------------------
This repository contains all the necessary code and datasets for my senior capstone project, "Attempting Predictions in the Israel-Palestine Conflict: An ML and Econometric Approach." The goal of this project is to use machine learning and econometric approaches to predict conflict events, enhancing our understanding of the dynamics within the Israel-Palestine conflict through data-driven analysis. 
-------------------


Project Structure
-------------------
Final_Book.ipynb: This is my main file detailing my data preprocessing, exploratory data analysis, and all phases of modeling and validation methods. 

Data: This directory contains the datasets used in the project.

Test notebooks: Testing jupyter notebooks used during the process. Includes other models, test code, unfinished attempts

Research: Useful resources used during the project - ACLED Codebook, relevant academic journals

Report: Includes my draft + final report 
-------------------


Research Methodology
-------------------
The project combines multiple data preprocessing techniques (e.g., log transformations, encoding, PCA, OLS w RSE attempts) with advanced machine learning models mainly Long Short-Term Memory (LSTM) networks. The approach addresses several challenges, including high dimensionality and class imbalance within the dataset.
-------------------

Key Findings
-------------------
The LSTM model with an embedding layer provided the highest accuracy, demonstrating the effectiveness of feature embeddings in handling categorical data in time-series predictions.

Multicollinearity and heteroscedasticity posed significant challenges, impacting model accuracy and forecasts. 
-------------------

Future Work to be Implemented
-------------------
Addressing class imbalance, heteroscedasticity, and multicollinearity issues within data!
Adding VAR, VECM, or other proper time-series model
Adding XGBoost / Tree-based model? 
-------------------


#License
This project is licensed under the MIT License - see the LICENSE file for details.

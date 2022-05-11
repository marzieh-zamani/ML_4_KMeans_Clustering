# Project 4: K-Means Clustering
K-Means clustering on Fish.csv dataset.

## Code Breakdown
### Step 0: Define function_0 to normalize the dataset
`input_feature_norm = function_0(input_feature)`

### Step 1: Import fish data from Fish.csv
1. Importing fish data from Fish.csv using panda.read_csv function;
2. Converting Panda data to Numpy data;
3. Spliting features and labels
4. Normalizing the data
5. Random spliting the data into 80% training and 20% test data (train_feature, test_feature, train_output, test_output);

### Step 2: Use Scikit Learn functions to perform K-Means clustering
Perform K-Means clustering on Fish Market dataset with K = 7 (No. of fish species). 

## Main files to check
The main file to check is the Jupyter notebook where:
- The functions are defined;
- The data is given;
- Then, the functions are called;
- The results are displayed and saved.

## Setup
Install [Miniconda](https://conda.io/miniconda).
Then, run the jupyter notebook in the "code" folder.

## Acknowledgment and References
This project has been developed based on the assignment provided by Dr. Abdul Bais, P.Eng. (abdul.bais@uregina.ca), my instructor for the course “ENEL-865/ENSE 865: Applied Machine Learning”.

This assignment is based on the first assignment of Machine Learning Regression course (from Coursera). 

- Dr. Abdul Bais, P.Eng. (abdul.bais@uregina.ca) page: 
https://www.uregina.ca/engineering/faculty-staff/faculty/bais-abdul.html

## Dataset
Download the Fish Market Dataset from Kaggle (https://www.kaggle.com/aungpyaeap/fish-market) to estimate weight of fish. Random split data into 80% training and 20% test data.

## My contribution
All scripts are written by my self.
______________
Marzieh Zamani
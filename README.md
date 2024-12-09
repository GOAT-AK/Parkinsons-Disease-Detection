# Parkinson's-Disease-Detection
Parkinson's Disease Prediction Project using Support Vector Machine (SVM) for Artificial Intelligence (2) [CS413P] at Faculty of Computers &amp; Information Sciences, Mansoura University

# Table of Content

* [Contributors](#Contributors)
* [Brief](#Brief)
* [DataSet](#DataSet)
* [How It Works](#HowItWorks)
* [Tools](#Tools&Libraries)
* [Remarks](#Remarks)
* [Usage](#Usage)
* [Sample Run](#Sample_Run)


# Contributors

* [Amr Khaled](https://github.com/GOAT-AK)

* [Amr Mohamed](https://github.com/AmrMohamed16)

* [Asem Ashraf](https://github.com/Asem-Git-Hub)

* [Asem Ayman](https://github.com/Assem-44)

* [Nada Mohamed](https://github.com/NadaKamal00)




# Brief

Parkinson's disease is a neurodegenerative disorder that affects movement. Early detection of Parkinson's disease is crucial for timely intervention and management. This project aims to provide a reliable tool for predicting the presence of Parkinson's disease using voice recordings.


# DataSet

The dataset used in this project is the [Parkinson's Data Set](https://www.kaggle.com/datasets/thecansin/parkinsons-data-set) from Kaggle. This dataset is composed of a range of biomedical voice measurements from 
31 people, 23 with Parkinson's disease (PD). Each column in the table is a 
particular voice measure, and each row corresponds one of 195 voice 
recording from these individuals ("name" column). The main aim of the data 
is to discriminate healthy people from those with PD, according to "status" 
column which is set to 0 for healthy and 1 for PD.


# How_It_Works

 • The dataset is loaded from a CSV file (parkinsons.data).
 
 • The 'name' column is cleaned and converted to a numeric type.
 
 • The dataset is split into features (X) and target labels (Y).

 • Oversampling is applied using SMOTE to balance the dataset by increasing the minority class samples in the training set.
 
 • Standard scaling is applied to the features.
 
 • The SVM model is trained on the training data.
 
 • The GUI allows users to input voice recording features.
 
 • Predictions are made based on the user input.

 

# Tools & Libraries

  I.	Juypter Notebook(IDE)
  
  II.	Python 3.x
  
  III. numpy
  
  IV. pandas 

  v. re
  
  VI.  scikit-learn
  
  VII.	 tkinter




# Remarks

* This Python program was run and tested in Jupyter Notebook.
  
* Ensure the required libraries are installed by running:
  
  ```bash
  pip install numpy pandas scikit-learn
# Usage

To begin utilizing this application, follow these steps:

1. Clone this repository:
   
   ```bash
   git clone https://github.com/GOAT-AK/Parkinsons-Disease-Detection

2. Navigate to the cloned repository:

   ```bash
   cd Parkinsons-Disease-Detection

3. Run the Jupyter Notebook:

   ```bash
   Full_Parkinsons.ipynb

# Sample_Run


* The Person Have Parkinson's 

![photo_2024-05-02 22 33 23](https://github.com/AmrMohamed16/Parkinson-s_Disease_Prediction_Project/assets/103078107/c4a9eba1-d254-4d38-b6b2-a1a8dda7a165)


<hr>


* The Person Doesn't Have Parkinson's


![photo_2024-05-02 22 44 42](https://github.com/AmrMohamed16/Parkinson-s_Disease_Prediction_Project/assets/103078107/43aedcee-a875-45f8-a72e-b44942b9599c)

<hr>
  
  

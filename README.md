## Spam Detection with Naïve Bayes Classifier
Welcome to my Spam Detection project! 🚀 This repository showcases a spam detection system implemented using a Naïve Bayes classifier. The model was built and tested on a dataset from Kaggle, achieving impressive accuracy in distinguishing spam from legitimate emails. Here’s a comprehensive overview of the project:  

<p align="center">
  <img width="460" height="300" src="https://github.com/user-attachments/assets/1378aaee-b70b-40ba-aeaa-bce35c4e0291">
</p>


## Project Overview
### Dataset

The dataset used for this project is spam_ham_dataset.csv, sourced from Kaggle. It contains labeled email data, which we utilized to train and evaluate our spam detection model.

### Implementation

1. **Setup & Data Preparation**
  - Imported necessary libraries and loaded the dataset using Google Colab.
  - Checked for and removed any duplicates (none found in this case).
  - Downloaded and utilized the stopwords package to filter out common but uninformative words.

2. **Preprocessing**
  - Cleaned the dataset by removing punctuations and stopwords.
  - Tokenized the text, splitting it into meaningful units.
  - Converted the cleaned and tokenized text into a matrix for further processing.

3. **Model Training**

  - Split the dataset into training (80%) and testing (20%) sets.
  - Imported and trained a Naïve Bayes classifier on the training data.
  - Evaluated the model's performance on both training and testing datasets.

4. **Results**
  - Training Accuracy: 98.74%
  - Testing Accuracy: 97.39%
  - Displayed classification reports and confusion matrices for both datasets.
    
## Results

**Training Data**: The model achieved an accuracy of 98.74%. The classification report and confusion matrix highlight the model's effectiveness in predicting spam vs. ham.  
**Testing Data**: The model performed with a 97.39% accuracy. The confusion matrix shows the model's ability to correctly classify most emails, with minor misclassifications.  

![image](https://github.com/user-attachments/assets/1ddc2fd9-6c29-425b-bd6d-a2eb0bbaf502)

## Confusion Matrix Insights

For the test data:  
The model correctly identified 718 legitimate emails (ham) but mistakenly classified 14 as spam.  
It successfully flagged 290 emails as spam, with 13 misclassified as legitimate.  
![image](https://github.com/user-attachments/assets/41b6cc7f-e379-4edb-8a8d-6acfa0b3fd78)

# Credit-Card-Fraud-Detection

This project uses a logistic regression model to detect fraudulent credit card transactions.

## Dataset

The dataset used for this project is a highly imbalanced dataset containing credit card transactions. The majority of transactions are legitimate, with a small percentage being fraudulent.

## Methodology

1.  **Data Loading and Exploration:** The dataset is loaded into a pandas DataFrame and explored to understand its structure and characteristics.
2.  **Data Preprocessing:** The dataset is preprocessed to handle missing values and address the class imbalance problem using under-sampling.
3.  **Feature Engineering:** No feature engineering is explicitly performed in this code, but the selection of features for the model is implicit in the step where the 'Class' column is dropped from the features.
4.  **Model Training:** A logistic regression model is trained on the preprocessed data.
5.  **Model Evaluation:** The model is evaluated using accuracy score and a confusion matrix is generated to visualize the model's performance.

## Results

The accuracy of the model on the training and test data is printed in the output. The confusion matrix provides a detailed breakdown of the model's predictions.

## Usage

To run this code, you need to have the following libraries installed:

*   numpy
*   pandas
*   scikit-learn
*   matplotlib
*   seaborn

You also need to have the `creditcard.csv` dataset uploaded to your Google Drive.

Make sure to mount your Google Drive in the Colab environment and update the file path in the `pd.read_csv()` function to point to the correct location of the dataset.

## Future Improvements

*   Explore different techniques for handling imbalanced datasets, such as oversampling or using different evaluation metrics.
*   Perform feature engineering to potentially improve model performance.
*   Try different machine learning models and compare their performance.
*   Deploy the model for real-time fraud detection.


Colab Link:- https://colab.research.google.com/drive/1ocg77TorM6ICzvjOd0tgIejxeOxrtqST?usp=sharing

Dataset link :- https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download
![WhatsApp Image 2024-05-17 at 3 46 39 AM](https://github.com/Samtoosoon/Credit-Card-Fraud-Detection/assets/123668966/b651c09b-f8e7-4218-8bbc-423cac6bb137)

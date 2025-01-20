# SMS Spam Detection with Machine Learning

This project involves building a machine learning model to classify SMS messages as either "Spam" or "Ham" (not spam). The dataset is preprocessed and analyzed to train a logistic regression classifier. Data visualization techniques are employed to gain insights into the dataset.

---

## Features of the Project

1. **Data Preprocessing**:
   - Removal of unnecessary columns.
   - Renaming columns for clarity.
   - Conversion of spam labels to numerical format (`0` for "Spam" and `1` for "Ham").

2. **Feature Extraction**:
   - Use of TF-IDF vectorizer to convert text messages into numerical features.

3. **Model Training**:
   - Logistic Regression is used as the classification model.

4. **Model Evaluation**:
   - Accuracy calculation for training and testing datasets.
   - Visualization of confusion matrix.

5. **Custom Message Testing**:
   - Model tested on user-defined SMS messages.

6. **Data Insights and Visualization**:
   - Distribution of Spam and Ham messages.
   - Most common words in spam and ham messages.

---

## Data

The dataset used for training is read from a CSV file. It includes:
- `Category`: The label of the message (`spam` or `ham`).
- `Message`: The text of the SMS.

### Preprocessing Steps:
- Unnecessary columns were dropped.
- Labels were converted to numerical representation.

---

## Libraries Used

- `pandas` and `numpy` for data manipulation.
- `sklearn` for machine learning and feature extraction.
- `nltk` for natural language processing.
- `matplotlib` and `seaborn` for data visualization.

---

## How to Run the Project

1. Clone the repository or download the code.
2. Ensure the following libraries are installed:
   ```bash
   pip install pandas numpy scikit-learn nltk matplotlib seaborn

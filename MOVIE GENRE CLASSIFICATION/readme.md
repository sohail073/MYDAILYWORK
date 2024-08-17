# Movie Genre Classification Project

This project aims to classify movies into different genres based on their descriptions using machine learning models. We use a dataset of movie descriptions to train and evaluate several models, including Naive Bayes, Logistic Regression, and Support Vector Machine (SVM).

## Project Structure

The project involves the following steps:

### 1. Reading the Data
- The dataset is split into training and test sets.
- The training data contains movie names, genres, and descriptions.
- The test data contains movie names and descriptions (without genres).

### 2. Data Cleaning
- Checking for missing values and ensuring data consistency.

### 3. Text Preprocessing
- Converting text to lowercase.
- Removing special characters, extra spaces, stop words, and punctuation.
- Tokenizing the text.

### 4. Feature Extraction
- Converting text data into numerical features using TF-IDF Vectorization.
- Encoding the genre labels.

### 5. Model Training
Three models are trained:
- Naive Bayes
- Logistic Regression (with Standard Scaling and SelectKBest for feature selection)
- SVM (with Standard Scaling and SelectKBest for feature selection)

### 6. Model Evaluation
- The models are evaluated on the test data.
- The accuracy of each model is calculated.
- Classification reports are generated to provide insights into the performance of each model.

### 7. Visualization
- A bar graph is created to compare the accuracy of the three models.

## Dataset
- **Training Data**: Contains movie names, genres, and descriptions.
- **Test Data**: Contains movie names and descriptions (used to evaluate model performance).
- **Test Data Solution**: Contains the true genres for the test data, used for model evaluation.

## Results
- **Naive Bayes**: Accuracy ≈ 0.45
- **Logistic Regression**: Accuracy ≈ 0.38
- **SVM**: Accuracy ≈ 0.15

The results show that Naive Bayes outperforms the other models, followed by Logistic Regression, while SVM performs the worst in this scenario.

## Conclusion
This project demonstrates the effectiveness of different machine learning models in classifying movie genres based on descriptions. The Naive Bayes model is the best performer, making it a suitable choice for this task.

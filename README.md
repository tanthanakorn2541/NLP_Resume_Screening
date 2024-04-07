# Resume Category Prediction

This project aims to predict the category of resumes based on the text data using machine learning techniques.

## Dataset

The dataset used in this project is named "UpdatedResumeDataSet.csv" and contains two columns:

- **Category**: Job categories such as Data Science, HR, Advocate, etc.
- **Resume**: Text data related to each category.

## Project Structure

The project structure is as follows:

- **Data Cleaning**: URLs, hashtags, mentions, special characters, and punctuations were cleaned from the resume text data.
- **Data Preprocessing**: Text data was vectorized using TF-IDF vectorization.
- **Model Training**: The KNeighborsClassifier model was trained using the preprocessed text data.
- **Model Evaluation**: The accuracy score was calculated to evaluate the model performance.
- **Prediction System**: A prediction system was implemented to predict the category of a given resume.

## Files Included

- **Main.ipynb**: Jupyter Notebook containing the main code for data preprocessing, model training, evaluation, and prediction.
- **UpdatedResumeDataSet.csv**: The dataset used for training and testing.
- **tfidf.pkl**: Pickle file containing the TF-IDF vectorizer for text data transformation.
- **clf.pkl**: Pickle file containing the trained KNeighborsClassifier model.

## Dependencies

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

## Usage

1. Install the required dependencies using `pip install -r requirements.txt`.
2. Run the Main.ipynb notebook to preprocess the data, train the model, and perform predictions.

# SMS Spam Detection Using Machine Learning

## Project Overview
A Streamlit web application that classifies SMS messages as Spam or Ham (legitimate messages) using a saved machine-learning model.

## Features
- Enter an SMS message for classification.
- Preprocess text before prediction.
- Convert text into numerical features using a saved TF-IDF vectorizer.
- Predict whether the message is spam or legitimate.

## Technologies Used
- Python
- Streamlit
- NLTK
- Scikit-learn
- TF-IDF

## Project Files
- `app.py` - Application code.
- `model.pkl` - Saved machine-learning model.
- `vectorizer.pkl` - Saved text vectorizer.
- `requirements.txt` - Python dependencies.
- `UCI SMS Spam.ipynb` - Jupyter notebook.
- `sms+spam+collection.zip` - Dataset archive.

## How to Run
1. Install Python.
2. Install dependencies:
   `python -m pip install -r requirements.txt`
3. Start the application:
   `python -m streamlit run app.py`
4. Open the local URL shown in the terminal.

## Source Acknowledgement
Original repository: https://github.com/kishan-1721/SMS-Spam-Detection

This project is based on/adapted from the original repository. Please review its license and retain any required attribution.

## Testing Note
Test the application with representative messages before reporting accuracy or other performance claims.

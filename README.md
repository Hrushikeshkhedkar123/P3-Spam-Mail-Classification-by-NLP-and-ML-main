# Spam Mail Classification by NLP and ML

This project is a web application that classifies emails as **Spam** or **Not Spam** using Natural Language Processing (NLP) and Machine Learning. The app is built with [Streamlit](https://streamlit.io/) for an interactive user interface.

## Features

- Enter any email text and classify it as spam or not spam.
- Uses a trained machine learning model and vectorizer (pickle files).

## Requirements

- Python 3.x
- streamlit
- scikit-learn
- pickle

## Setup

1. **Clone this repository** or download the source code.
2. **Install dependencies**:
    ```
    pip install streamlit scikit-learn
    ```
3. **Ensure the following files are in the project directory**:
    - `spamDetector.py`
    - `spam123.pkl` (trained model)
    - `vec123.pkl` (vectorizer)

## Usage

Run the Streamlit app from your project directory:
```
streamlit run spamDetector.py
```
or
```
python -m streamlit run spamDetector.py
```

The app will open in your browser. Enter an email to classify it.

## Notes

- If you do not have the `.pkl` files, you need to train the model and vectorizer first.
- Make sure all files are in the same directory.

## License

This project is for educational purposes.
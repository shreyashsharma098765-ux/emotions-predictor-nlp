# Emotion Prediction using NLP 😊😢😡

This project is a Natural Language Processing (NLP) based Emotion Prediction System that predicts human emotions from text input.

The model analyzes the given sentence or text and classifies the emotion such as happiness, sadness, anger, fear, and more.

## Project Overview

The project uses **TF-IDF Vectorization** along with a Machine Learning classification model to detect emotions from textual data.

The model was trained on emotion-labeled text data and saved using `.pkl` files for easy deployment and prediction.

## File Descriptions

* **emotions_NLP_projext.ipynb**
  Jupyter Notebook containing data preprocessing, text cleaning, vectorization, model training, and evaluation.

* **emotion_model.pkl**
  Stores the trained NLP emotion prediction model.

* **tfidf_vectorizer.pkl**
  Contains the TF-IDF Vectorizer used to convert text into numerical features.

* **emotion_labels.pkl**
  Stores the emotion label mappings used during prediction.

* **train.txt**
  Dataset file containing emotion-labeled training data.

## Technologies Used

* Python
* Natural Language Processing (NLP)
* Scikit-learn
* Pandas
* NumPy
* TF-IDF Vectorizer
* Pickle

## Features

* Emotion prediction from text
* Text preprocessing and cleaning
* TF-IDF based feature extraction
* Machine Learning classification model
* Saved model deployment using `.pkl` files

## How to Run the Project

1. Install the required libraries:

```bash id="h71m2x"
pip install pandas numpy scikit-learn nltk
```

2. Open Jupyter Notebook:

```bash id="m50q8w"
jupyter notebook
```

3. Run the notebook:

```bash id="p91z4n"
emotions_NLP_projext.ipynb
```

## Future Improvements

* Add a Streamlit frontend UI
* Deploy the model online
* Improve emotion detection accuracy
* Add real-time text analysis

---

⭐ If you like this project, consider giving it a star on GitHub!

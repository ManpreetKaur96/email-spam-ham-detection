📧 Email Spam vs Ham Detection System

This project is a Machine Learning based email classifier that detects whether an email message is Spam or Ham (Not Spam).

The model is trained using Natural Language Processing (NLP) techniques and deployed using a Streamlit web application where users can enter an email message and instantly receive a prediction.

## Features

* Classifies email as Spam or Ham

* Uses TF-IDF Vectorization

* Machine Learning model Support Vector Machine (SVM)

* Simple Streamlit web interface

* Real-time email prediction

## Technologies Used

Python
Pandas
NLTK
Scikit-learn
Streamlit

## Model Performance

The best model selected for this project is Support Vector Machine (SVM) with an accuracy of about 98%.

## NLP Processing Steps

The following text preprocessing steps are used in this project:

* Convert text to lowercase
* Tokenization
* Remove stopwords
* Lemmatization
* TF-IDF Vectorization

These steps help the machine learning model understand the email text more effectively.

## Project Structure
```
EMAIL-SPAM-HAM
├── app.py                # Streamlit web application
├── model.py              # Model training script
├── research.ipynb        # Notebook used for experimentation
├── best_model.pkl        # Saved trained model
├── vectorizer.pkl        # TF-IDF vectorizer
├── screenshot.png        # Application interface screenshot
├── spam_ham_dataset.csv  # Dataset used for training
├── requirements.txt      # Project dependencies
├── commands.txt          # Commands to run the project
├── examples.txt          # Example emails for testing
└── README.md             # Project documentation
```

## Run the Project

Install required libraries:

```bash
pip install -r requirements.txt
```
Run the Streamlit application:

```bash
streamlit run app.py
```

After running the command, open your browser and go to:

" http://localhost:8501 "

You will see the Spam vs Ham Email Classifier interface.

## Testing the Model

You can test the model by:

Opening the examples.txt file

Copying any email message

Pasting it into the Email Text box in the web interface

Clicking Predict

The application will display whether the email is Spam or Ham.

You can also test the model using your own email examples.

## Application Interface

![Application Screenshot](screenshot.png)

Author: Manpreet Kaur
Role: Data Analyst / Data Science Intern

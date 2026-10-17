# Language Detection Model

A simple machine learning project that detects the language of a given text using Natural Language Processing (NLP). The project utilizes a **Multinomial Naive Bayes** classifier trained on text samples from 22 different languages, achieving an accuracy of approximately **95.3%**. 

## Features

* Preprocesses and vectorizes text data using CountVectorizer.
* Validates dataset integrity by checking for null values and handling duplicate entries.
* Splits data into training (67%) and testing (33%) sets for reliable validation.
* Provides an interactive command-line interface to predict languages from user input.

## Prerequisites

Before running the project, ensure you have Python installed alongside the required libraries: 

```
pip install numpy pandas scikit-learn
```
Use code with caution.

## Dataset

The model expects a dataset named language.csv in the root directory. The file must contain at least two columns: 

* Text: The text sample to analyze.
* language: The ground truth language label (e.g., Estonian, Swedish, Thai, Tamil, Dutch, Urdu).

## How to Run

1. Clone or download this repository to your local machine.
2. Ensure language.csv is placed in the same folder as the script.
3. Run the Jupyter Notebook or execute the Python code cells sequentially to train the model and test custom inputs:

### To run via a converted Python script (if applicable)
```
python language_detection.py
```
Use code with caution.

## Model Evaluation

* **Training Samples:** 14,740 records
* **Testing Samples:** 7,260 records
* **Accuracy Score:** ~95.32%

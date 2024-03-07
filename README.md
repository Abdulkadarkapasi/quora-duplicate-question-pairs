# Quora Duplicate Question Detection

This repository contains a project focused on detecting duplicate question pairs on Quora using natural language processing (NLP) techniques. 
The project includes Python scripts and Jupyter notebooks for data preprocessing, model training, and evaluation, as well as a Streamlit web application for interactive testing.

## Files

- `helper.py`: Python script containing helper functions for data preprocessing, feature extraction, and model evaluation.
- `quora-duplicate-question-detection.ipynb`: Jupyter notebook containing the main code for data analysis, model training, and evaluation.
- `streamlit_app.py`: Python script implementing a Streamlit web application for interactive testing of the trained model.
- `requirements.txt`: Text file listing all Python dependencies required to run the code.

## Getting Started

To get started with the project, follow these steps:

1. Clone this repository to your local machine.
2. Install the required Python dependencies using `pip install -r requirements.txt`.
3. Open and run the Jupyter notebook `quora-duplicate-question-detection.ipynb` to explore the data, train the model, and evaluate its performance.
4. Once the model is trained, run the Streamlit web application using `streamlit run streamlit_app.py` to interactively test the model.

## Dataset

The project uses the Quora Question Pairs dataset, which contains pairs of questions from the Quora platform along with a label indicating whether they are duplicate or not. 
You can download the dataset from [here](https://www.kaggle.com/c/quora-question-pairs/data).

## Dependencies

The project relies on the following Python libraries:

- pandas
- numpy
- scikit-learn
- nltk
- matplotlib
- seaborn
- streamlit

These dependencies are listed in the `requirements.txt` file and can be installed using `pip`.

Feel free to contribute to the project by submitting pull requests or opening issues.
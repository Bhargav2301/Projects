# Data Science Resume Classifier
This repository contains a machine learning model for classifying resumes into various categories. The categories represent different job roles/fields in which an individual could work.

## Project Description
The project uses Python and several data science libraries to process, analyze, and classify text data. The primary steps involved include data cleaning, text processing, feature extraction, and model training and evaluation.

## Data
The dataset used is resume_dataset.csv, which contains resumes divided into multiple categories, each representing a different job role/field.

## Libraries Used
Numpy
Pandas
Matplotlib
Seaborn
re (for regular expressions)
NLTK (Natural Language Toolkit)
Wordcloud
Scikit-learn
Instructions
To run the Jupyter notebook:

Clone the repository: git clone [https://github.com/Bhargav2301/Data-Science-Resume-Classifier.git](https://github.com/Bhargav2301/Projects/blob/main/Resume_analysis.ipynb)
Navigate into the project directory: cd Data-Science-Resume-Classifier
Open the notebook in Jupyter: jupyter notebook Resume_Classification.ipynb
Run the cells in the notebook
Results
The project builds a classifier using a K-Nearest Neighbors algorithm wrapped in a One-Vs-Rest classifier to handle the multi-class nature of the problem. It prints out the accuracy of the model on the training and test dataset, along with a detailed classification report.

## Contributing
Feel free to fork this repository and contribute. Pull requests are welcome.

## License
This project is licensed under the MIT License.

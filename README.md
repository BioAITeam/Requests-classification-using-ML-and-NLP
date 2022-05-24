# Requests classification in the customer service area for software companies using Machine Learning and Natural Language Processing
Artificial Intelligence (AI) is one of the components recognized for its potential to transform the way we live today radically. It makes it possible for machines to learn from experience, adjust to new contributions and perform tasks like human beings. The business field is the focus of this research. This paper proposes implementing an incident classification model using Machine Learning (ML) and Natural Language Processing (NLP). The application is for the technical support area in a software development company that currently resolves customer requests manually. Through ML and NLP techniques applied to company data, it is possible to know the category of a request given by the client. It increases customer satisfaction by reviewing historical records to analyze their behavior and correctly provide the expected solution to the incidents presented. Also, this practice would reduce the cost and time spent on relationship management with the potential consumer. This work evaluates different Machine Learning models, such as Support Vector Machine (SVM), Extra Trees, and Random Forest. The SVM algorithm demonstrates the highest accuracy of 98.97% with class balance, hyper-parameter optimization, and pre-processing techniques.

## Citing

If you use our project for your research or if you find this paper and repository helpful, please consider citing the work.

Cite the code: [![DOI](https://zenodo.org/badge/483448303.svg)](https://zenodo.org/badge/latestdoi/483448303)
 

## Folders

- **Data** This folder contain the dataset.
- **Notebook** In this folder, you will find all algorithms and implementations for the dataset. 

## Requirements
This repository requires the following libraries:

- NumPy
- Pandas
- string
- Seaborn
- openpyxl
- scikit-learn
- NLTK
- spaCy
- imbalanced-learn
- Matplotlib
- Yellowbrick
- Time

This repository was developed in the Python 3 (3.8) programming language.

## Package installation

If you don't use google colab, We highly recommend to use and install Python packages within an Anaconda environment. To create, execute the command below:
```
conda create --name TCC python=3.8
```
So, activate it:
```
conda activate TCC
```
Packages installation
```
pip install ipykernel
```
and display of environment in jupyter
```
python -m ipykernel install --user --name TCC --display-name "TCC"
```
Now, install the libraries
```
conda install -c conda-forge matplotlib
```
```
conda install -c anaconda seaborn
```
```
conda install -c anaconda scikit-learn
```
```
conda install -c districtdatalabs yellowbrick
```
```
conda install -c anaconda nltk
```
```
conda install -c conda-forge imbalanced-learn
```
```
conda install -c conda-forge spacy
```
```
python -m spacy download es_core_news_sm
```
```
python -m spacy download en_core_web_sm
```
```
conda install openpyxl
```
```
conda install xlrd
```

## Execution
After installing all the Requirements, you must clone the repository using.
```
git clone https://github.com/BioAITeam/Requests-classification-using-ML-and-NLP.git
```
If you will use colab, upload the cloned folder to drive, then open the folder and run the notebook.

If you are going to use your computer, install:
```
conda install jupyter 
```
Enter the cloned folder, then enter the folder and run the notebook.


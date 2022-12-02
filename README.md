# Olist-Data-Science
### Classification-Project
&nbsp;<br>
&nbsp;<br>

![Alt text](https://github.com/huambra/Olist-Data-Science-Classification-Project/blob/master/olist_office.jpg)


## Table of Contents

- [Project Description](#project-description)
- [Requirements](#requirements)
- [Usage](#usage)
- [Content Description](#content-description)
- [Actions](#actions)
- [Results](#results)
  
## Project Description
This project was my capstone project for my Data Science course in CoderHouse. We used public data from a Brazilian startup -Olist- which is a marketplace and logistics facilitator for small and medium enterprises operating in Mexico and Brazil. Our goal was to create a model able to predict customer’s reviews based on the data we had available. 

## Requiriments
1. Software
    - [Anaconda](https://www.anaconda.com/)
    - [Python v3](https://www.python.org/)
    - [Jupyter Notebook](https://jupyter.org/install)
    &nbsp;<br>
    &nbsp;<br>  
2. Frameworks and Libraries
    - pandas
    - nympy
    - seaborn
    - matplotlib
    - scipy
    - sklearn
    &nbsp;<br>
    &nbsp;<br>
3. Aditional Files
    - Regiones.csv -> it's attached in this repo
    - [Data](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) -> download all the 9 files as .csv
    &nbsp;<br>
    &nbsp;<br>


## Usage
1. Make sure to have installed the required software, as well as all the necessary frameworks and libraries
2. Clone or download the repo as a zip file.
3. Paste the 9 data .csv files inside the folder you'll be working
4. Run Jupyter Notebook, browse to the folder location, and open the .ipybn files. First open the Olist.ipynb file, followed by Olist_ECommerce_Models.ipybn. 

## Content Description
- Proyecto_Olist.pdf: Full Project Documentation (ESP)
- olist.ipynb: Code used to understand the data and to prepare it for the models
- Olist_ECommerce_Models: Code of the models used
- Regiones.csv: File of regions in Brazil (necessary to run the code)

## Actions
The first thing we did was to understand the project requirements and from where we should access the data to help us develop the model. 

Next we used python to clean and prepare the data to develop the model. We also used python to conduct an EDA that gave us a deeper understanding of the data and how we could create the model. 

Once we were clear about that, we started applying different classification algorithms such as decision tree, random forest, xgboost, etc and we compared them to see which one was the best for our model. 

Finally, we decided on a random forest and documented the entire process.

## Results
Our model didn’t have the accuracy of a model ready to be deployed, however we were able to create a solid first model and include a section on future improvements.




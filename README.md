# Write_a_Data_Science_Blog_Post
This project is a part of Udacity Data Scientist Nano degree program.

## **Table of Contents:**
1. [Project Introduction](README.md#project-introduction)
2. [File Description](README.md#file-description)
3. [Libraries used](README.md#libraries-used)
4. [Results](README.md#results)
5. [Licensing, Acknowledgements](README.md#licensing-acknowledgements)

## **Project Introduction**

In this project, I will look into the Airbnb Dataset from the City of Munich, Germany to get a better insight of the condition of the accommodation based on city disctrict.

Following business questions will be answered: 
- How many accommodation has most of the Airbnb host in Munich?
- In which neighbourhood there are the 10 most expensive accommodation? What is the price range of each neighbourhood?
- Is it possible to predict the accommodation price?

---

## **The methodology**
**CRISP-DM** will be used as the methodology to answering the business questions above. 
1. Business Understanding  
To understand the business, the business questions must be defined.
2. Data Understanding  
From the business questions, the dataset will be analyzed, and the useful data feature will be selected accordingly.
3. Prepare Data  
The raw data are mostly not clean, in this phase, we will clean the data, so it will be ready for training the prediction later. 
4. Model Data  
Linear Regression will be used to train the prediction model. R-square Score will be calculated.
5. Results  
The results will be presented in a Medium article.
6. Deploy  
In this project there will be no deployment.

----

## **File Description**
    .
    ├── data
    |   └── 2020-10-26/listings.csv.gz      # Listing dataset
    ├── Write_a_DS_Blog_Post.ipynb          # Jupyter Notebook that contains the analysis
    └── README.md

The dataset is originated from [insideairbnb](http://data.insideairbnb.com/germany/bv/munich/2020-10-26/data/listings.csv.gz) from the 26th October 2020. This dataset is licensed under [Creative Commons CC0 1.0 Universal (CC0 1.0) "Public Domain Dedication"](https://creativecommons.org/publicdomain/zero/1.0/)

---

## **Libraries Used**<br/>
Following libraries were used for this project:
- [pandas](https://pypi.org/project/pandas/)
- [numpy](https://pypi.org/project/numpy/)
- [matplotlib](https://pypi.org/project/matplotlib/)
- [seaborn](https://pypi.org/project/seaborn/)
- [sklearn](https://pypi.org/project/sklearn2/)

---

## **Results**<br/>
The finding from the jupyter notebook can be found in [this medium post](https://veltenwinter.medium.com/8000-for-a-night-in-airbnb-munich-e511a8ab1c3c)

---

## **Licensing, Acknowledgements**<br/>
Credit and thanks too: 
- Udacity for providing a great data scientist course.
- Insideairbnb to providing a great data.
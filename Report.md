# Udemy Courses Rating Predection
By: Rawabi Alharbi, Rahaf Algahtani

## Abstract
The goal of this project is to apply Linear Regression on data scraped from Udemy website, to predict the rating of courses based on the features of those courses (prices, reviews, total hours, etc.). I worked with data that I have scraped from Udemy.com using Selenium and BeautifulSoup.  After getting the data we start to clean them remove nulls values, fill null discount with zeros and extract numbers from string. After that we started to explore the dataset and split the data into %60 train/%20validation, and %20 for the test .Finally we tried different types of models to find the best one that fit our data which is Polynomial.

## Data
The data that will be used in this project has been extracted from Udemy website (https://www.udemy.com/courses/it-and-software/). It includes data such as: (rating, prices, trainers, etc.) for each course. It includes 10 features, and below is the description of each one:


| Feature               | Description                                                                     |
|-----------------------|---------------------------------------------------------------------------------|
| Title                 |	Course title
| Description           |	Description of course content
| Price                 | The original price
| Discount              | The price after discount
| Rating                | The price after discount
| Reviews              	| The total number of reviews
| Trainer               | Trainer’s name
| Total_hours           | Duration of the course
| Total_lectures        | Number of lectures
| level                 | Course level

* 10 features
* +9k rows

## Algorithms
Our steps in this project was:
1. Problem understanding
2. Data gathering by scrapping 
3. Data exploration and visualization
4. Feature engineering
5. Starting training and validation our data on different models. 

## Tools
- Python and Jupyter Notebook
- Numpy and Pandas for data manipulation
- Matplotlib and Seaborn for plotting visuialization
- BeautifulSoup and selenium for web scraping
- Sklearn for ML algorithms
- HTML/CSS

## Communication
![image](https://user-images.githubusercontent.com/87195262/137355123-731c8888-ba36-4859-a0b2-004b862c210c.png)
![image](https://user-images.githubusercontent.com/87195262/137355165-6473d4f0-44cd-4dbf-8c34-3ca3c1a53a8f.png)
<img width="477" alt="Screen Shot 2021-10-14 at 7 06 09 PM" src="https://user-images.githubusercontent.com/87195262/137355311-470974af-05e5-4807-b69d-06b6da93d840.png">


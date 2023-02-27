<h1 align="center"> Predict Mexico House Price  </h1>

<br>

## 📃 Table of Contents:
  - [About Repository](#-about-repository)
  - [Installation](#-installation)
  - [Useage](#-useage)
  - [Report](#-report)
  - [Contribution](#-contribution)
  
## About Repository
In this repository I will use a dataset of 21,000 properties to determine if real estate prices are influenced more by property size or location. Then I build data visualizations, and examine the relationship between two variables using correlation. Finally I will build a Linear Regression model and Ridge Regression to predict apartment prices in Mexico. Additionally, I also create a data pipeline to impute missing values and encode categorical features, and they improve model performance by reducing overfitting.

This project was inspired by the lesson I learned in [WQU](https://www.wqu.edu/)

## Installation
This is a Jupyter notebook. Package requirements are included in requirement.txt. This project uses Python 3.9. Run the following command in terminal to install the required packages. `pip3 install -r requirements.txt`

## Useage
The notebook includes all the markdowns which explain the process.

## Model using
* Linear Regression [Linear Regression](https://paperswithcode.com/method/linear-regression)
* Ridge [Ridge Regression](https://arxiv.org/pdf/1509.09169.pdf)

## Report
| Model | Baseline MAE | Val MAE |
| ----- | ------------ | ------- |
| Linear Regression | 17189.62 | 15200.969 |
| Ridge | 17189.62 | 15200.246|

## Contributing
1. Fork it
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

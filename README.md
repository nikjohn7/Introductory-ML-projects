# Introductory-ML-projects

This repo consists of projects that I curated for a workshop that I was invited to conduct at Thakur College of Engineering and Technology.

All the projects were run on Google Colab

## Project 1:  Grad School Admissions

This dataset was created for prediction of Graduate Admissions from an Indian perspective.

The dataset contains several parameters which are considered important during the application for Masters Programs.
The parameters included are :

- GRE Scores ( out of 340 )
- TOEFL Scores ( out of 120 )
- University Rating ( out of 5 )
- Statement of Purpose and Letter of Recommendation Strength ( out of 5 )
- Undergraduate GPA ( out of 10 )
- Research Experience ( either 0 or 1 )
- Chance of Admit ( ranging from 0 to 1 )

I mainly used Multivariable Linear Regression, to predict the chance of admissions. I have included some basic exploratory Data Analysis too, to get an idea of how the dataset looks like

You can access the project from the [grad-admits](https://github.com/nikjohn7/Introductory-ML-projects/tree/main/Grad-admits) folder


## Project 2:  Online Shopping

This dataset has data of customers who buys clothes online. The store offers in-store style and clothing advice sessions. Customers come in to the store, have sessions/meetings with a personal stylist, then they can go home and order either on a mobile app or website for the clothes they want. The company wants to estimate the yearly amount of money spent by a user based on certain parameters.

The parameters included are :

- Email
- Address
- Avatar
- Avg. Session Length
- Time on App
- Time on Website
- Length of Membership
- Yearly Amount Spent (what we want to predict)

I again used Multivariable Linear Regression, to predict the chance of admissions. I have included some basic exploratory Data Analysis too, to get an idea of how the dataset looks like

You can access the project from the [online-shopping-analysis](https://github.com/nikjohn7/Introductory-ML-projects/tree/main/Online-shopping-analysis) folder



## Project 3:  Digit Recognizer

This project is aimed at providing a good introduction into neural networks and their functioning. The famous MNIST dataset was used here.

MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms.

Our goal is to correctly identify digits from a dataset of tens of thousands of handwritten images

The data files train.csv and test.csv contain gray-scale images of hand-drawn digits, from zero through nine.

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.

The training data set, (train.csv), has 785 columns. The first column, called "label", is the digit that was drawn by the user. The rest of the columns contain the pixel-values of the associated image. There are about 43,000 images in the training dataset

There are 28000 images in the test set


You can access the project from the [digit-classifier](https://github.com/nikjohn7/Introductory-ML-projects/tree/main/Digit-classifier) folder

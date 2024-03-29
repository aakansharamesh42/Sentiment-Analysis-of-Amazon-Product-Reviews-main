# README for Sentiment-Analysis-of-Amazon-Product-Reviews-main

## Introduction

This README provides a detailed guide for the Sentiment-Analysis-of-Amazon-Product-Reviews-main GitHub repository. This project is focused on performing sentiment analysis on Amazon product reviews using advanced deep learning techniques, including GRU, LSTM, convolution units, and transfer learning.

## Repository Structure

The repository includes the following files:

- **LICENSE**: Contains the license information for the project, which is under the MIT license.
- **Marge_Data_Training.ipynb**: A Jupyter notebook for merging and preprocessing the data used for training the models.
- **README.md**: The markdown file providing a detailed explanation and guide for the project.
- **Transfer_Learning.ipynb**: A Jupyter notebook demonstrating the use of transfer learning techniques in sentiment analysis.

## Installation

Before running the notebooks, ensure that you have the necessary packages installed. These typically include TensorFlow, NumPy, Pandas, and Jupyter. You can install them using pip:

```bash
pip install tensorflow numpy pandas jupyter
```

## Usage

To use the notebooks:

1. Clone the repository to your local machine:

```bash
git clone https://github.com/your-username/Sentiment-Analysis-of-Amazon-Product-Reviews-main.git
```

Replace `your-username` with your actual GitHub username.

2. Navigate to the cloned directory and start Jupyter Notebook:

```bash
cd Sentiment-Analysis-of-Amazon-Product-Reviews-main
jupyter notebook
```

3. Open the `.ipynb` files and run the cells to execute the sentiment analysis.

## Project Overview

This project applies deep learning techniques to perform sentiment analysis on Amazon product reviews. It utilizes GRU, LSTM, and convolutional layers for feature extraction and sentiment classification. Transfer learning is also employed to enhance the performance using pre-trained models.

The primary goal is to classify reviews into positive, neutral, and negative sentiments. The overall accuracy of the model on the test data is around 93%. The model performance indicates a robust capability in distinguishing different sentiments, although there is room for improvement, especially in balancing out lower-rated products.

## Contribution

Contributions to this project are welcome. You can contribute by improving the code, adding new features, or by providing better documentation. Please ensure to follow the existing code structure and document any changes or additions you make.

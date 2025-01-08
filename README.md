# LLM Research: AfriMMLU - Llama Fertility & Parity

## Overview
This project focuses on evaluating the performance of language models using the AfriMMLU dataset. The primary goal is to calculate the accuracy and fertility of various language models across different African languages and subjects. The project utilizes the LLaMA tokenizer to analyze tokenization efficiency and accuracy.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Data Preparation](#data-preparation)
- [Calculating Accuracy](#calculating-accuracy)
- [Calculating Fertility](#calculating-fertility)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Installation
To run this project, you need to have Python installed along with the following libraries:
- `pandas`
- `transformers`
- `datasets`
- `tqdm`
- `re`
- `seaborn`
- `matplotlib`

You can install the required libraries using pip:
pip install pandas transformers datasets tqdm re seaborn matplotlib


## Data Preparation
The data preparation section involves loading the dataset and ensuring that it contains the necessary columns. The expected mean accuracy values for each language are defined in the `LLama_results` dictionary.

## Calculating Accuracy
The accuracy of the language model is calculated by comparing the actual answers with the predictions made by the model. The results are stored in a DataFrame, and accuracy values are saved as CSV files for further analysis.

## Calculating Fertility
Fertility is defined as the ratio of tokens generated to words in the text. The code calculates the fertility scores for each subject and language using the LLaMA tokenizer. The results are aggregated and can be visualized for better understanding.

## Results
The results include mean accuracy and fertility scores for various languages. The code also checks for significant differences in accuracy and provides insights into the performance of the LLama outputs in order to establish a relationship between tokenizer fertility/parity and translation quality.


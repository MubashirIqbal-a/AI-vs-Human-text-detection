# AI vs. Human Text Classification Model

## Overview

This project focuses on the development of a robust text classification model capable of distinguishing between AI-generated and human-written text. The dataset used for training and testing is sourced from [Kaggle](https://www.kaggle.com/datasets/shanegerami/ai-vs-human-text), providing a diverse and comprehensive set of examples.

## Project Flow

1. **Data Loading and Preprocessing**
   - Imported essential libraries to facilitate efficient data handling.
   - Loaded the dataset to kickstart the workflow.
   - Segregated features and labels for streamlined processing.

2. **Text Tokenization**
   - Tokenized the text data, resulting in 303,355 tokens.
   - Implemented tokenization-saving mechanisms for easy reloading.
   - Ensured optimal memory usage and prevention of crashes during the process.

3. **Sequence Padding**
   - Padded the initial 20% of the dataset to maintain uniform sequence lengths.
   - This step is crucial for optimizing model training and ensuring consistency in input data.

4. **Model Training**
   - Developed and trained the classification model on the initial 20% of the dataset.
   - Achieved a remarkable validation accuracy exceeding 99%, indicating the model's proficiency.

5. **Model Testing**
   - Applied the trained model to the next 40% of the dataset, comprising 194,894 inputs.
   - Impressive testing accuracy of 99.2% was achieved, validating the model's robustness and effectiveness.

## Usage

To replicate the results and utilize the trained model:
1. Clone this repository.
2. Ensure the required libraries are installed (specified in the requirements file).
3. Run the provided Jupyter notebook or script to train and test the model on your own data.

## Results

The model exhibits exceptional accuracy, making it a reliable tool for discerning between AI-generated and human-written text. The achieved accuracy rates during training and testing stages underscore the effectiveness and generalization capabilities of the classification model.

Feel free to explore the codebase and experiment with different datasets or fine-tuning approaches to further enhance the model's performance.

## Acknowledgments

Special thanks to the Kaggle community and dataset contributor [shanegerami](https://www.kaggle.com/shanegerami) for providing the valuable dataset used in this project.

**Note:** This README serves as a high-level overview. For detailed implementation and insights, refer to the accompanying codebase and documentation within the repository.

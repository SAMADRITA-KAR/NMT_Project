# NMT_Project

# Machine Translation Model: English to Bengali

## Overview

This repository contains a machine translation model that translates English sentences to Bengali using deep learning techniques. The model is built using Keras and TensorFlow, and it is trained on a custom English-Bengali dataset.

## Table of Contents

- [Overview](#overview)
- [Dependencies](#dependencies)
- [Dataset](#dataset)
- [Running the Code](#running-the-code)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Model Saving](#model-saving)
- [Contributing](#contributing)

## Dependencies

To run this code, you need the following dependencies:

- Python 3.x
- Keras
- TensorFlow
- NLTK
- NumPy

Install the required libraries using the following command:
```bash
pip install nltk numpy keras tensorflow
```

## Dataset

The English-Bengali dataset used to train and evaluate the model is not included in this repository due to its size. However, you can obtain a similar dataset from any source or prepare your own dataset in the following format:

english_sentence \t bengali_sentence
...

Each line in the dataset should contain an English sentence followed by a tab separator and the corresponding Bengali sentence.

## Running the Code

1. Download or create the English-Bengali dataset and place it in the project directory with the filename `English-Bengali Dataset.zip`.

2. Execute the Python script `translate.py` to train and evaluate the machine translation model:
python translate.py


The script will perform the following steps:

- Load and preprocess the dataset.
- Tokenize the sentences and create vocabulary for both English and Bengali.
- Prepare the training and test data.
- Define and train the machine translation model.
- Evaluate the model's performance on the test data.

Note: Please ensure that you have enough computational resources, preferably a GPU, to train the model efficiently.

## Model Architecture

The machine translation model architecture is defined in the `define_model` function in the `translate.py` script. For more details about the model architecture and hyperparameters, refer to the function's documentation in the code.

## Results

After running the `translate.py` script, the model's test accuracy and loss will be displayed. These metrics indicate the model's performance in translating English sentences to Bengali.

## Model Saving

After training, the model will be saved in a file named `HP.docx` in the project directory. This saved model can be loaded and used for translating new English sentences to Bengali.

## Contributing

If you wish to contribute to this project, please feel free to open issues or submit pull requests. We welcome any improvements or bug fixes!

## Author
This project is created and maintained by # Samadrita Kar


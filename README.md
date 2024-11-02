# Emotion Detection from Text

This project implements an emotion detection system using a neural network model. The system preprocesses text data, trains a model to classify emotions, and provides predictions with associated probabilities.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Data](#data)
- [Installation](#installation)
- [Usage](#usage)
- [Model Structure](#model-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project aims to classify emotions in textual data. It preprocesses the text, trains a neural network on labeled data, and allows for predictions on new text inputs. The system utilizes the Keras library for model training and scikit-learn for data processing.

## Getting Started

### Prerequisites

Ensure you have the following installed on your machine:

- Python 3.x
- pip

##Data
The project uses three datasets: train.txt, val.txt, and test.txt. Each file should have two columns separated by a semicolon:

text: The text input.
label: The corresponding emotion label for the text.
Make sure these files are placed in the root directory of the project.

##Usage
Training the Model
Run the following script to preprocess the data, train the model, and save the trained model along with the vectorizer and label encoder:


##Results
The model can provide predictions for new text inputs, returning the percentages of different emotions. This allows for understanding the emotions expressed in a given text.

# Cat-Dog CNN Binary Classification

## Overview

This repository contains code for a Convolutional Neural Network (CNN) model to perform binary classification on images of cats and dogs. The model is trained on a dataset of labeled images, and it can predict whether an input image contains a cat or a dog.

## Installation

1. Clone the repository to your local machine:

git clone git@github.com:SaidiSouhaieb/Keras-Binary-Classification.git
cd Keras-Binary-Classification

2. Install required dependecies

pip install -r requirements.txt

## Usage

1. Download model from cloud drive
link : [https://drive.google.com/drive/folders/1wd5g_VsN1tJsiBwmvhZcaFff8hRChbCi?usp=sharing]

2. Place file near "model_predict.ipynb"

3. Add image path in the "img_path" variable

4. Predict!

## Data Augmentation

1. Pass the data as structured below

2. Create Data Augmented folder

3. Wait as the images get created


## Training

Data Structure

  dataset/
  |-- train/
  |   |-- cats/
  |   |-- dogs/
  |-- test/
  |   |-- cats/
  |   |-- dogs/

Pass the augmented data created before.


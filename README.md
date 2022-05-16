# Machine Learning Portfolio

### House prediction in Nairobi

This project implements linear regression ML, whereby the model is trained to predict the prices of houses in Nairobi based on a number of features.

The project is in the [house-prediction](https://github.com/Centyfano/machine-learning-portfolio/tree/main/house-prediction) directory

### Cats vs Dogs classification

This is a supervised learning image classification type of ML, where a model is created and trained to classify images of cats vs that of dogs.

Given the small size of the training dataset, data augmentation was performed, to _create_ new datasets by transforming the existing ones through methods such as zooming in, horizontal flips and rotations.

The project is in the [cats-dogs-classification](https://github.com/Centyfano/machine-learning-portfolio/tree/main/cats-dogs-classification) directory.

### Flowers Classification

This is a multiclass classification ML, where the task is to classify images of five different flowers

-   roses
-   daisy
-   dandelion
-   sunflowers
-   tulips

Data augmentation is performed on the training set to prevent overfitting during training.

The project is in the [flowers-classification](https://github.com/Centyfano/machine-learning-portfolio/tree/main/flowers-classification) directory

### Animal-classification

This project also implements the multi-class classification, and the goal is to classify images of four wild animals:

-   Zebra
-   Buffalo
-   Elephant
-   Rhino

See the project in detail in the [animal classification](https://github.com/Centyfano/machine-learning-portfolio/tree/main/animal-classification) project

### MNIST digit recognizer

Participated in the Kaggle MNIST digit recognizer challenge, and obtained a score of 0.98428 in the leaderboard

The dataset is in [mnist](), and the code at [Kaggle](https://www.kaggle.com/code/centyfanoarnold/digit-recognizer-using-cnn-and-imagedatagenerator)

# Usage

Clone this repo, and in the terminal, navigate to the directory `animal-classification`

Activate the virtual environment of your choice (either python-venv or anaconda), and in it, install the packages for this project

```
pip install -r requirements.txt
```

### Get Kaggle API key

This is required in order to download Kaggle datasets.

For the animal-classification project, the dataset used is at Kaggle, thus an [API key](https://www.kaggle.com/docs/api) is required.

After getting the API key, put it in the home directory, since that is the default location kaggle will look for.

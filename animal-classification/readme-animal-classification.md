# Animals clasification

This project implements the multi-class classification, and the goal is to classify images of four wild animals:

-   Zebra
-   Buffalo
-   Elephant
-   Rhino

The dataset is avalilable at [Kaggle](https://www.kaggle.com/datasets/ayushv322/animal-classification), and it has 1000 images for each class, totaling 4000 images.

Tasks done include

-   **Data preparation**  
    Splitting the data into `training` and `validation` sets for each of the classes, with ratios of 8:2 respectively

-   **Data augmentation**  
    This was done to prevent overfitting, given the small amount of tranining and test data. Other preparation techniques such as data normalization and resizing were also performed.

-   **Model training**  
    A convoluted network was used in building the model, with filters, pooling layers and densely connected networks.

## Usage

Clone this repo, and in the terminal, navigate to the directory `animal-classification`

Activate the virtual environment of your choice (either python-venv or anaconda), and in it, install the packages for this project

### Package installation

After activating your environment, install the packages

```
pip install -r requirements.txt
```

### Get Kaggle API key

This is required in order to download Kaggle datasets.  
After getting the API key, put it in the home directory, since that is the default location kaggle will look for

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

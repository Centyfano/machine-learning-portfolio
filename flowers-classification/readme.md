# Flowers clasification

This project implements the multi-class classification, and the goal is to classify images of five flowers:

-   roses
-   daisy
-   dandelion
-   sunflowers
-   tulips

Tasks done include

-   **Data preparation**  
    Splitting the data into `training` and `validation` sets for each of the classes, with ratios of 8:2 respectively

-   **Data augmentation**  
    This was done to prevent overfitting, given the small amount of tranining and test data. Other preparation techniques such as data normalization and resizing were also performed.

-   **Model training**  
    A convoluted network was used in building the model, with filters and pooling layers, therby connected to a densely connected network for training.

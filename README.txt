###############################################
##                                           ##
## COMP 6721 Applied Artificial Intelligence ##
##                  Phase I                  ##
##                                           ##
###############################################

##

1. File Struxture
------------------

    a. driver.py - Contains the model, the training and data pre-processing code
    b. Dataset - Contains the dataset of images belonging to cloth, , surgical, without_mask category
    c. testImage - Contains never before seen images by the model for testing
    f. DatasetSat.png - Bargraph showing the number of images in each class
    g. 6721 Report.pdf - Project Report containing the required info on Dataset, CNN Model and Evaluation

2. How to train a new CNN Model
--------------------------------

    a. run python main.py

3. Test pre-trained model on new images outside dataset
--------------------------------------------------------

    a. run python main.py
    b. A random class label between 0 and 4 will be picked on which prediction will be made. 

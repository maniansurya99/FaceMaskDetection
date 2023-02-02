# FaceMask Classification with CNN

Solving an Image Classification problem with a convolution neural network that would classify the images into 5 different classes of mask types.Initially the emphasis was on data pre-processing and model architecture after which the bias in the data was identified and removed. further the accuracy was increased by tuning the hyper parameters and a Kfold cross validation was applied on the model.

Data pre-processing: Clean and normalize the data to improve the accuracy of the model.

Model architecture: Design the architecture of the convolution neural network to effectively classify the images.

Bias identification and removal: Check for any biases in the data and remove them to improve the fairness of the model.

Hyperparameter tuning: Fine-tune the hyperparameters of the model to increase accuracy.

K-fold cross validation: Use K-fold cross validation to evaluate the performance of the model and avoid overfitting.

# Dataset Description
-> Dataset [Directory consisting of training images for training]

	-> No Mask
	-> N95 Mask
	-> N95 with Valve Mask
	-> Surgical Mask
	-> Cloth Mask 
	-> dataset.pickel [Consists of Key value pair]

-> Testing Dataset [Directory consisting of sample images for predictions]

	-> Random

-> Final_model_trained.pt 		- Trained Model File 

# mole-classifier
A simple CNN classifier to distinguish between benign and malignant skin moles.

The dataset is obtained from kaggle, and copied to google drive. After unzipping the Kaggle file, rougly 20% of images in the training folder was used to create a new folder for validation data (not included in code). 

The binary cross entropy loss function is employed along with an Adam optimizer.
Regularization techniques used includes Dropout and L2 Regularization. Data Augmentation is also utilised on the training data.

After training for 150 epochs, our final model achieves a test accuracy of 84% and a loss value of 0.36

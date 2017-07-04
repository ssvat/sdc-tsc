# sdc-tsc
Traffic Sign Recognition Classifier

Method: 
The convolutional neural network (LeNet) has been used to classify traffic signs.  

Files Submitted:
Submission Files-listed readme.md.

Dataset Exploration:
Dataset Summary-Training set is for the training, validation set is used to validate the model performance during training. Those three sets are not included in this repository. The new images, which are obtained to test the model, are included.
Exploratory Visualization-The histogram for three sets mentioned above is plotted and the image visualziation is done for new images downloaded from web.

Design and Test a Model Architecture:
Preprocessing-The prepocessing methods include normalization. Other techniques including dropout, different normalization have been explored but the accuracy has not been improved. 
Model Architecture-in the Traffic_Sign_Classifier.ipynb notebook file.
Model Training-in the Traffic_Sign_Classifier.ipynb notebook file.
Solution Approach-Validation Accuracy = 0.986, which is greater than 0.93. Please see the Traffic_Sign_Classifier.ipynb notebook file.

Test a Model on New Images: 
Acquiring New Images-The downloaded images include some un-recognizable traffic signs. The future improvments can be done by downloading more new images to test.
Performance on New Images-in the Traffic_Sign_Classifier.ipynb notebook file.
Model Certainty - Softmax Probabilities-in the Traffic_Sign_Classifier.ipynb notebook file.

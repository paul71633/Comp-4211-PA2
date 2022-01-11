The 1st block is importing the libraries that are needed.
The 2nd block is to connect to my google drive.
The 3rd block is writing the path for this assessment.
The 4th block is reading in the training, validation, and test set.
The 5th block is reading in the index.txt file.
The 6th block is constructing the class to deal with the images that are going to be compared.
The 7th block is to check whether the class created worked correctly.
The 8th block is transforming the images to 32*32 and single channel, and also create the data loaders for the train, validation, and loss set.
The 9th block is importing the needed libraries to construct the CNN model and build the CNN model.
The 10th block is to change the device into cuda(using gpu).
The 11th block is importing the library needed to show the summary of the model, and show the summary of the model.
The 12th block is building the fully connected layer model.
The 13th block is showing the summary of the fully connected layer model.
The 14th block is building the Siamese network by combining the CNN network and fully connected layer network.
The 15th block is showing the summary of the Siamese network.
The 16th block is defining how to train the Siamese network model and also record the training and validation loss.
The 17th block is training the network model.
The 18th block is plotting the training loss and validation loss for every 10 steps.
The 19th block is defining a function to find out the best validation accuracy and best threshold.
The 20th block is training the first model that I changed for Q8A.
The 21st block is calculating the best validation accuracy and best threshold for the first model.
The 22nd block is plotting the training loss and validation loss for every 10 steps.
The 23rd block is training the second model that I changed for Q8A.
The 24th block is calculating the best validation accuracy and best threshold for the second model.
The 25th block is plotting the training loss and validation loss for every 10 steps.
The 26th block is training the third model that I changed for Q8A.
The 27th block is calculating the best validation accuracy and best threshold for the third model.
The 28th block is plotting the training loss and validation loss for every 10 steps.
The 29th block is adding data augmentation methods for Q8C, and redefining the data loaders for the training set.
The 30th block is training the model with the new data loader.
The 31st block is calculating the best validation accuracy and best threshold for the model.
The 32nd block is plotting the training loss and validation loss for every 10 steps.
The 33rd block is putting the test set in the model to test the model.
The 34th block is writing the test set result to p1.csv.
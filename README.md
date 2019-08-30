# DogBreedClassifier
 Udacity Data Science Nanodegree Project on creating a dog breed classifier with Keras.
 
 ### Overview
This project is part of Udacity's Data Science Nanodegree. The aim of the project is to train a model  that is able to identify a breed of dog if given a photo or image as input. If the photo or image contains a human face, then the application will return the breed of dog that most resembles this person.

Summary of the results - final model for identifying dog breeds achieved an 85% accuracy level on the testing dataset.

### File Descriptions 
The main file is dog_app.ipynb, which is a jupyter notebook containing all the procedure involved in creating our algorithm and model which is used to predic dog breed. A html version of the above jupyter notebook file is also included.

The haarcascades folder holds the xml file for use with the OpenCv face detector class that is used in the notebook. The images folder contains the images used to test the predictions of the final model in the notebook.

### Dependencies
opencv, python, glob, matplotlib, numpy, scipy, tqdm, keras, scikit-learn, ipykernel, tensorflow

### Acknowledgements
Most ideas for this project have been taken from the lessons on Udacity's DSND program.

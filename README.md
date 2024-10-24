# ANN-fish-class
--Project Summary --
This project demonstrates the process of building and training an ANN for image classification. The model is mostly capable of accurately identifying different fish species from encoded images. 
This project utilizes the Kagglehub library to download a Kaggle dataset and determine the local storage path for the files. Essential libraries for data handling, machine learning, deep learning, and image processing are imported to facilitate the construction of a neural network model using TensorFlow and Keras.

The dataset comprises images of fish, and the initial steps involve collecting the image paths and their corresponding labels. The label names are cleaned and encoded to prepare them for use in a machine-learning model. A dedicated function preprocesses the images, loading and preparing all images from the dataset while splitting the data into training, validation, and test sets.

To provide insights into the data, sample images from the training dataset are visualized, and basic statistics regarding the dataset's size and label distribution are presented.

The core of the project involves building, compiling, and training a neural network using TensorFlow's Keras API for image classification. Early stopping is implemented during training to prevent overfitting, and the training and validation loss over epochs is visualized to monitor performance.

A detailed summary of the neural network architecture is provided, outlining the number of layers, their output shapes, and the total number of parameters.

Finally, the model is evaluated on a single batch of test data, returning the loss and accuracy for that specific batch. The trained model's performance is further assessed on the entire test dataset, with the test accuracy printed to gauge the model's ability to generalize to unseen data.

The project link to the Kaggle environment is: https://www.kaggle.com/code/eceranaskel/fish-classification-ann-final

---Source Dataset Reference --- 
The project was done in the Kaggle environment with the following referenced dataset: 
This dataset contains 9 different seafood types collected from a supermarket in Izmir, Turkey
for a university-industry collaboration project at Izmir University of Economics, and this work
was published in ASYU 2020.
Dataset includes, gilt head bream, red sea bream, sea bass, red mullet, horse mackerel, 
black sea sprat, striped red mullet, trout, shrimp image samples. 

If you use this dataset in your work, please consider to cite:

@inproceedings{ulucan2020large,
  title={A Large-Scale Dataset for Fish Segmentation and Classification},
  author={Ulucan, Oguzhan and Karakaya, Diclehan and Turkan, Mehmet},
  booktitle={2020 Innovations in Intelligent Systems and Applications Conference (ASYU)},
  pages={1--5},
  year={2020},
  organization={IEEE}
}

* O.Ulucan , D.Karakaya and M.Turkan.(2020) A large-scale dataset for fish segmentation and classification.
In Conf. Innovations Intell. Syst. Appli. (ASYU)

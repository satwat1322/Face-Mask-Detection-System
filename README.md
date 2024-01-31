# Face-Mask-Detection-System
Using CNN, Deep Learning this project was developed .

# Goal of the project 
Goal was to develop a system that canautomatically detect if a person is wearing a face mask or not in an image. This became useful during the COVID-19 pandemic to identify people not following mask guidelines .

# key points explaining the methodology and code used for the face mask detection system:

Libraries Imported: The project imported key Python libraries like Keras, TensorFlow, matplotlib, numpy, os, random, cv2 etc. These libraries provide functionality for building and training neural networks (Keras, TensorFlow), data manipulation and visualization (numpy, matplotlib), and image processing (cv2).

Dataset: The dataset consisting of face mask and no-mask images was imported from Kaggle. The images were visualized using matplotlib to see some samples from the dataset.

Data Splitting: The dataset was split into training, validation and test sets in an 80:10:10 ratio using Keras methods. This creates subsets to train, evaluate and test the model.

Data Augmentation: To expand the number of training images, data augmentation techniques like rotation, shifting, shear and zoom were applied to the images. This improves model generalization.

CNN Model: A convolutional neural network (CNN) model was designed with convolutional, pooling and dense layers using Keras. Key parameters like number of layers, nodes, activation functions, optimizers etc. would have been tuned.

Model Training: The designed CNN model was trained for a fixed number of epochs/iterations to optimize the loss function using backpropagation. The training and validation loss/accuracy were plotted to monitor performance.

Testing: After training, the model's generalization capability was evaluated on the unseen test set. Metrics like test loss, accuracy, precision, recall etc. reflect real-world performance.

# Conclusion
In summary, the methodology followed industry standards for applying CNNs to image classification tasks. The code implemented data preprocessing, model building & training, and model evaluation stages.

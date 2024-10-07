# Sign-Language-Detector
## Project Overview
In this sign language recognition project, we develop a sign detector capable of recognizing numbers from 1 to 10, with the potential to be easily expanded to include a wide range of additional signs and hand gestures, including the alphabet.

## Prerequisites
The prerequisites software & libraries for the sign language project are:

- Python (3.7.4)  
- IDE (Jupyter)  
- Numpy (version 1.16.5)  
- cv2 (OpenCV) (version 3.4.2)  
- Keras (version 2.3.1)  
- TensorFlow (as Keras uses TensorFlow in the backend and for image preprocessing) (version 2.0.0)







## Project is divided into 3 Steps 
1. Creating the dataset
2. Training a CNN on the captured dataset
3. Predicting the data

## Summary 
After each epoch, the model's accuracy and loss are evaluated using the validation dataset. If the validation loss fails to decrease, the learning rate (LR) is reduced via the Reduce LR callback to prevent the model from overshooting the loss minima. Additionally implemented early stopping to halt training if validation accuracy consistently decreases over several epochs.
This includes the callbacks used, as well as two optimization algorithms: SGD (Stochastic Gradient Descent, where weights are updated after each training instance) and Adam (a combination of Adagrad and RMSProp).

SGD yielded higher accuracies, with 100% training accuracy and approximately 81% validation accuracy during training.







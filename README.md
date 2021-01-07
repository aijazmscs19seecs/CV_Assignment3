# CV_Assignment3
# IE 7615: NeuralNetworks and Deep Learning- Final Project 
### Contributed by: 
##### 1. Ahsan Ijaz
                
## Image Classification using CNN, Keras and Tensorflow in Python

### This project is being done as a competition by many students and the best accuracy achieved is 70%. We were able to achieve 63% accuracy for 101 classes. This falls in the top 5 for the competition. For 10 classes we were able to achieve an accuracy of 95% 

## Data
The dataset is obtained from an opensource platform. It is available on CalTech website as CalTech 101 Image classification dataset.
It can be accessed from the link - http://www.vision.caltech.edu/Image_Datasets/Caltech101

## Analysis Performed

### Objective 
Image Classification using CNN in Keras and Tensorflow for CalTech 101 dataset.


### Approach
We have used classic Neural Networks(CNN) to perform image classification. Using Keras and TensorFlow in Python, different maxpooling and concolutional layers were added to the neural network. The labels were pre-defined as the class names and the model was trained on this neural network.

### Steps
1. Read the images
2. Pre-process and rescale the images
3. Use different types of activation functions like tanh and Relu
4. Apply the Convolutional Neural Networks in Keras and TensorFlow
5. Train the model on training dataset
6. Evaluate the model on Test set of images

### Insight
### Comparison of accuracy of different activation functions

![train images WOA](https://user-images.githubusercontent.com/72271559/103927384-1957bc80-513c-11eb-9de2-367fb82c8ca2.PNG)
 

![vgg16_train test accuracy](https://user-images.githubusercontent.com/72271559/103927680-908d5080-513c-11eb-8ff1-17e667cd2a8e.PNG)


![vgg16_train test loss](https://user-images.githubusercontent.com/72271559/103927758-aef34c00-513c-11eb-9ba4-032a7f5d81c4.PNG)


![vgg16_WA_epochs](https://user-images.githubusercontent.com/72271559/103927813-c03c5880-513c-11eb-861a-866f5f90ee07.PNG)


![vgg16_WA_matrix](https://user-images.githubusercontent.com/72271559/103927836-c7636680-513c-11eb-9685-2cabe6e2fcb5.PNG)


![vgg16_WOA_epochs](https://user-images.githubusercontent.com/72271559/103927858-cdf1de00-513c-11eb-9eda-d6d5320359ce.PNG)


![vgg16_WOA_matrix](https://user-images.githubusercontent.com/72271559/103927879-d6e2af80-513c-11eb-88b5-d920245136cd.PNG)


![vgg16summary](https://user-images.githubusercontent.com/72271559/103927906-e235db00-513c-11eb-864a-d18be9c2349d.PNG)

### Conclusion
1. Relu performs better for image classification as compared to tanh activation function
2. The convolutional network gives an accuracy of 95% for the 10 classes with maximum number of images 
3. While training the images using CNN the number of training samples in important. For example, if there are less samples to train on then the model won't perform accurately.

# Face_Recognition_VGG-16

Face Recognition System Using VGG16 and Transfer Learning
VGG16 : VGG16 is a convolutional neural network model proposed by K. Simonyan and A. Zisserman from the University of Oxford in the paper “Very Deep Convolutional Networks for Large-Scale Image Recognition”. The model achieves 92.7% top-5 test accuracy in ImageNet, which is a dataset of over 14 million images belonging to 1000 classes. It was one of the famous model submitted to ILSVRC-2014. It makes the improvement over AlexNet by replacing large kernel-sized filters (11 and 5 in the first and second convolutional layer, respectively) with multiple 3×3 kernel-sized filters one after another. VGG16 was trained for weeks and was using NVIDIA Titan Black GPU’s.

# Process: 
++ At first i collect my images and store them in respective directories { train , test } ++ Then I collect images of my friend Arpit and store them in respective directories.

# Note : 
    Classes should be two or more than two.We can't train our own images only.
    
++ Then i modified pre-created VGG16 model and add some new layers ro perform tranfer learning. ++ Then i train my model and save it in file. ++ Then i load the model and start predicting the images.

# Accuracy :  100 %

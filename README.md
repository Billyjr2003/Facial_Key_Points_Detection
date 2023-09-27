# Facial_Key_Points_Detection
## Objective
In this project, I am developing a model to detect facial key points on images of people. 

## Challenges 
there is not enough dataset

## Models
I have used the Resnet50 pre-trained model It uses skip connections or residual connections to allow gradients to flow more easily during training. This enables the training of very deep networks, which can capture more complex features and patterns in the data.
Despite its depth, ResNet-50 is computationally efficient. The use of residual connections reduces the number of parameters that need to be learned compared to earlier deep architectures. This makes it easier to train and use in practical applications.
ResNet-50 has demonstrated strong generalization capabilities. It can adapt well to different types of images and datasets, making it a versatile choice for various computer vision tasks.

## Images Preprocessing 
### I have used the following augmentations 
1- ToTensor: Converts an image from its original format (e.g., JPEG) into a numerical representation (tensor).
2- Normalization: By scaling pixel values to a standard range, typically between 0 and 1 or -1 and 1, normalization ensures that input data to a neural network is consistently and uniformly scaled. This leads to more stable and faster training, while also mitigating issues related to varying lighting conditions.
3- Random Crop: During training, the image is randomly cropped to show the model different regions of the image. This variation in the training data helps to improve the model's robustness and its ability to generalize to different object positions or image sizes.


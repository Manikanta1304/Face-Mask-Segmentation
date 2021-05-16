# Face-Mask-Segmentation

Project: Face mask segmentation

Predict and apply masks over the faces within images using CNN and image recognition algorithms. In this hands-on project, the goal is to build a system, which includes building a face detector to locate the position of a face in an image and apply a segmentation mask on the face.

Skills and Tools:
Computer Vision, CNN, Transfer Learning, Object detection

Context:
Used transfer learning on an already trained model. Used the MobileNet model which is already trained to detect the face attributes. We will need to train the last 6-7 layers and freeze the remaining layers to train the model for predicting the mask on the face. To be able to train the MobileNet model, we will be using the WIDER FACE dataset for various images with a single face and multiple faces.

Dataset: 

WIDER Face Dataset

* WIDER FACE dataset is a face detection benchmark dataset, of which images are selected from the publicly available WIDER dataset.
* This data has 32,203 images and 393,703 faces are labelled with a high degree of variability in scale, pose and occlusion as depicted in the sample images.
* In this project, we are using 409 images and around 1000 faces for ease of computation.

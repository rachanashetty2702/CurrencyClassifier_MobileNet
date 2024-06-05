# RupeeClassifier_MobileNet
A MobileNet Convolutional Neural Network model for classifying Indian Currency Denominations.
This model leverages the MobileNet architecture, a lightweight convolutional neural network designed for mobile and embedded devices. Utilizing the power of transfer learning, the model starts with a pre-trained MobileNet base, which has learned rich features from a diverse set of images in the ImageNet dataset. The base model is extended with additional layers to adapt it to the specific task of classifying currency denominations. The dataset, organized into n folders representing n distinct classes, is loaded from Google Drive and preprocessed using standard techniques, including resizing and normalization. The model is then compiled with the Adam optimizer and categorical crossentropy loss, suitable for multi-class classification. During training, the model learns to distinguish between different currency denominations through multiple epochs. Finally, the trained model is converted to TensorFlow Lite format for efficient deployment on mobile devices. This lightweight TFLite model is well-suited for real-time inference on smartphones, enabling accurate and efficient currency classification for users with varying denominations.

Dataset : 
[Google Drive](https://drive.google.com/drive/folders/1Lcr_P0cZJXZc3b0m6bl8KjpMcFv5DqjE?usp=sharing)

# Image Captioning 
This GitHub repository contains an Image Captioning generator implemented using TensorFlow and Keras. The model architecture uses the VGG16 convolutional neural network (CNN) for feature extraction and an LSTM network for generating descriptive captions for images. The dataset used for training consists of 8,000 images from the Flickr platform, with each image having five associated captions.

To use the generator, you need Python 3.x, TensorFlow, Keras, NumPy, Pandas, and Matplotlib. Clone the repository, download and preprocess the Flickr dataset, and run the training script. After training, you can test the model by providing an image file to generate captions.

The model's performance can be evaluated using metrics such as BLEU, METEOR, and CIDEr scores, while qualitative assessment can be done by visually inspecting the generated captions.

Contributions to the repository are welcome, and the project is licensed under the MIT License. Please comply with the terms and conditions of the Flickr dataset when using it for training or evaluation.

Download Dataset - https://www.kaggle.com/datasets/adityajn105/flickr8k

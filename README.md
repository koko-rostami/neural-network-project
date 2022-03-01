Image caption generator is a process of recognizing the context of an image and annotating it with relevant captions using deep learning, and computer vision. 
It includes the labeling of an image with English keywords with the help of datasets provided during model training. 
Imagenet dataset is used to train the CNN model called Xception. Xception is responsible for image feature extraction. These extracted features will be fed to the LSTM model which in turn generates the image caption.


CNN : To extract features from the image. A pre-trained model called Xception is used for this.

LSTM :To generate a description from the extracted information of the image.


Dataset for Image Caption Generator:

The Flickr_8K dataset is used for the model training of image caption generators. 
The dataset can be downloaded directly from the below links. The downloading process takes some time due to the large size(1GB) of the dataset. 
In the below image you can check all the available files of the Flickr_8k_text folder. The most important file is Flickr 8k.token which is storing all the image names with the captions respectively.
8091 images are stored inside the Flicker8k_Dataset folder and the text files with captions of image

Flicker8k_Dataset : https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_Dataset.zip


Flickr_8k_text :    https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_text.zip


How can I run this project?

1- Download and extract Flickr8k_Dataset.zip and Flickr8k_text.zip

2- Now, create a folder named 'ML' in root directory of your Google Drive.

3- Then upload extracted version of Flickr8k_Dataset and Flickr8k_text into the ML folder. This will take times depending on your IP provider.

4-  run the code.

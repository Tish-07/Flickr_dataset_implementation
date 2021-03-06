# Flickr_dataset_implementation

A brand logo detection system using region-based convolutional neural networks.

### Overview

Implentation of Region-based Convolutional Neural Networks in Tensorflow, to detect and classify brand logos.

Note: This is my personal implementation based on flickr-logo detection dataset.

### Usage

1. `python gen_bg_class.py`: Generate train\_annot\_with\_bg\_class.txt file. 
2. `python crop_and_aug.py`: Crop brand logo images from the [flickr27\_logos\_dataset](http://image.ntua.gr/iva/datasets/flickr_logos/) and apply data augmentation method. Finally the dataset consists of near about 14k images.
3. `python gen_train_valid_test.py`: Generate(Split) train/valid/test set from the dataset.
4. `python train_deep_logo_cnn.py`: Train the convolutional neural networks and save the trained model to disk.
5. `python test_deep_logo_cnn.py`: Test the trained model (for Classification).  
`python detect_logo.py`: Test the trained model (for Detection)

# Rice_Classification
Rice, which is among the most widely produced grain products worldwide, has many genetic varieties. These varieties are separated from each other due to some of their features. These are usually features such as texture, shape, and color. With these features that distinguish rice varieties, it is possible to classify and evaluate the quality of seeds. Dataset contain 5 different rice types images with 15000 images for every category. The goal is to make a classification model that could correctly predict the 5 kinds of rice.

# Rice Types
- Arborio
- Basmati
- Ipsala
- Jasmine
- Karacadag

Use Transfer Learning MobileNetv2 and VGG16 by Keras to make two classification models and compare. At 5 epochs, VGG16 and MobileNetv2 have comparable accuracy at ~99%. However, MobileNetv2 has a much faster training time than VGG16. Further hyperparameter tuning can be done to obtain a better accuracy.

Dataset can be downloaded https://www.kaggle.com/datasets/muratkokludataset/rice-image-dataset.

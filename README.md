# Invasive-Species-Monitoring
Invasive Species Monitoring from Kaggle.https://www.kaggle.com/c/invasive-species-monitoring 

Using pre-trained VGG16 and fine_tune the last conv-layer for about 16 epochs with 400x300 images.
Finally I got 96% accuracy.

VGG16_L (trained images with 400x300 pixel) got the best accuracy 96%. Next I may try ResNet or DenseNet or combain them together (Dual Path Networks from https://arxiv.org/abs/1707.01629).

Finetune VGG16 top layers with Keras as described by Francois Chollet here:

https://blog.keras.io/building-powerful-image-classification-models-using-very-little-data.html

Inspired by 

https://www.kaggle.com/chmaxx/finetune-vgg16-0-97-with-minimal-effort


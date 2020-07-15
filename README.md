# Adversarial_attack_on_Xray_Images

An adversarial attack embodies of subtly changing an original image in such a way that the changes are almost imperceptible to the human eye. Hence, the modified image is named an adversarial image that is misclassified by the classifier when it is classified. Since, well known pre-trained deep learning models are publicly available, that are used to classify radiology images, we formulated FGSM attack for these models. 

This research crafts FGSM attack on transfer learning models.
![Adversarial](/images/normal_adversarial.png)

The common pretrained transfer learning model used is InceptionV3 and VGG16.
![InceptionV3](/images/inception.png)

![VGG16](/images/vgg.png)


## Dependencies
* IPython Notebook
* Keras (Tensorflow Backend)
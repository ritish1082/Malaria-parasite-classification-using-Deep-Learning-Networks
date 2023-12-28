# Malaria parasite classification using Deep Learning Networks

### Abstract

Malaria is a global health threat caused by the Plasmodium parasite. The early identification and classification of the parasite are vital for prompt treatment and improved patient outcomes. However, traditional detection methods depend heavily on expert knowledge for accurate diagnosis,
making them challenging to implement. This paper aims to conduct a comprehensive analysis of 6 existing deep learning models including AlexNet, GoogleNet, VGG19, MobileNet, ResNet, and RCCNet utilizing the malaria parasite dataset. Additionally, we perform a comparative evaluation of these models by implementing various Data Augmentation techniques and **improving accuracy by 3%** reaching **maximum accuracy up to 96.73 %**. The assessment is centered around key factors such as training duration, precision, weighted f1 score, specificity, and sensitivity.

### Dataset
A publicly available dataset from the **National Institute of Allergy and Infectious Diseases** consisting of microscopic images of malaria parasites is used for comparison of the models. The dataset contains **27,558 images of two balanced classes each patch with the dimension 142 X 148**. The class ‘Parasitized’ consists of 13,779 images, and ‘Uninfected' with 13,779 images.

### Proposed system

In this paper, we conduct a comparative study of various models including **AlexNet, GoogLeNet, VGG-19, ResNet-50, MobileNet, and RCCNet** under identical conditions. Their effectiveness is then ranked using metrics like accuracy, F1 score, sensitivity, and specificity. To enhance model performance, data augmentation techniques are employed, including shear operations with a range of 0.2, zoom transformations within a range of 0.2, and performing both vertical and horizontal flips.

### Metrics

![Metrics]([https://github.com/[username]/[reponame]/blob/[branch]/image.jpg?raw=true](https://github.com/ritish1082/Malaria-parasite-classification-using-Deep-Learning-Networks/blob/main/Metircs%20Comparision.jpg))


### Conclusion and future scope

Our study found that **GoogLeNet had the highest testing accuracy (96.73%), followed closely by RCCNet (96.53%)**. We can further improve the accuracy by increasing the data samples using generative adversarial networks (GANs).


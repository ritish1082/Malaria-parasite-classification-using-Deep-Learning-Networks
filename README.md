# Malaria parasite classification using Deep Learning Networks

### Abstract
Malaria is a global health threat caused by the Plasmodium parasite. The early identification and classification of the parasite are vital for prompt treatment and improved patient outcomes. However, traditional detection methods depend heavily on expert knowledge for accurate diagnosis, making them challenging to implement. This paper aims to conduct a comprehensive analysis of 6 existing deep learning models including AlexNet, GoogleNet, VGG19, MobileNet, ResNet, and RCCNet utilizing the malaria parasite dataset. Additionally, we perform a comparative evaluation of these models by implementing various Data Augmentation techniques and improving accuracy by 3% reaching maximum accuracy up to 96.73 %. The assessment is centered around key factors such as training duration, precision, weighted f1 score, specificity, and sensitivity.

### Dataset
A publicly available dataset from the National Institute of Allergy and Infectious Diseases consisting of microscopic images of malaria parasites, is used for comparison of the models. The dataset contains 27,558 images of two balanced classes each patch with the dimension 142 X 148. The class ‘Parasitized’ consists of 13,779 images, and ‘Uninfected' with 13,779 images.

## Methodology
We performed a comparative study of existing 6 CNN models on the malaria parasite blood smears dataset. Each model was trained with and without data augmentation techniques involving shear (range=0.2), range (range=0.2), and horizontal and vertical flipping.

Metrics can be found in the Metrics comparison.jpg file 

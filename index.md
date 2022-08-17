# Skin_Hair dataset
**Setting the benchmark for effective hair inpainting methods for improving the image quality of dermoscopic images**

## Introduction
Dermoscopic images are often contaminated by artifacts including clinical pen markings, immersion fluid air bubbles, dark corners, and most importantly hair, which makes interpreting them more challenging for clinicians and computer-aided diagnostic algorithms. Hence, automated artifact recognition and inpainting systems have the potential to aid the clinical workflow as well as serve as an preprocessing step in the automated classification of dermoscopic images. The Skin Hair dataset contains
over 252 dermoscopic images including artificial hair and will be expanded over time. Furthermore, we present the primary results of applying machine learning algorithms and GAN based architectures to the hair inpainting problem in dermoscopic images. We envision that these results will serve as a benchmark for researchers who might work on the hair detection and reconstruction tasks with this dataset in the future. In this work, we present a skin lesion image dataset based on the ISIC
dataset containing dermoscopic images, images containing artificial hairs and the corresponding ground-truth masks. Furthermore, we use four hair inpainting methods including Navier-Stokes, Telea, Hair SinGAN and R-MNet architectures which we evaluate using image quality assessment metrics MSE, PSNR, UQI and SSIM. The R-MNet architecture achieved the highest SSIM score of 0.960.
## Dataset
The main issue in the process of detection, reconstruction and assessment of artifacts is mostly due to the lack of properly prepared datasets which do not include
ground truth masks and reference images. Due to the artifact removal evaluation process we propose a novel Skin Hair dataset that includes the raw dermoscopic
images, images containing artificial hairs as well as ground-truth masks for evaluation purpose. This dataset is created by taking raw dermoscopic images without
hair artifacts from the ISIC dataset that serve as a reference ground-truth image and for applying manually extracted hairs from other dermoscopic images from the ISIC dataset.
In total 252 images were generated with 84 unique masks to cover the different hair types. The Skin Hair dataset contains: 35 images with small density (each in three colours - light, brown and dark), 27 images with medium density (each in three colours - light, brown and dark) and 22 images with high density (each in three colours - light, brown and dark).
![zdjęcie](src)



[Link](url) and ![Image](src)

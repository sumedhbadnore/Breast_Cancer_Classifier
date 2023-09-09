# Breast Cancer Classifier Using Neural Networks

## Introduction:
One of the most prevalent cancers in women globally is breast cancer, accounting for 25% of all cancer cases. It occurs when abnormal cells in the breast tissue grow uncontrollably, forming a tumor. Breast cancer can affect women of any age, although it is more frequent in older women. Men can acquire breast cancer as well, though it is considerably less prevalent. Women's lives are significantly impacted by breast cancer, a serious health issue. It may result in
bodily symptoms including breast soreness, nipple discharge, and lumps in the breast. Anxiety, despair, and fear of recurrence. 

## What are Mammograms?

Breast cancer screening and diagnosis are both done using the medical imaging procedure known as mammography. Images of the breast tissue are made using a specialised X-ray machine in this procedure. Mammography is normally advised as a standard screening technique for women over the age of 40, though it might be advised sooner if there is a family history of breast cancer or other risk factors.

## Project Objective:

The goal is to create a computer assisted diagnosis (CAD) system that can categorise mammogram
pictures as benign (non-cancerous) or malignant (cancerous). Radiologists employ CAD tools to
increase the precision of diagnoses. Grey Level Co-occurrence Matrix (GLCM) along 0° and DWT
(Discrete Wavelet Transform), which is used as a method for determining feature extraction to
transform the mammogram image into a set of coefficients that can be used as an input to the model,
were used in the proposed system to calculate texture features from mammograms. Due to the
widespread use of artificial neural networks in many industries, including pattern recognition,
medical diagnosis, machine learning, etc., the most efficient features from the calculated features that
had a significant impact on achieving the desired output were chosen and then transferred to
Probabilistic Neural Network (PNN) for training and classification. The proposed approach achieved
overall accuracy of 94.2% using a mini-MIAS database in this investigation.

## Methodology

In the proposed methodology, the following stages were conducted to develop a breast cancer
detection system: The first stage is Input data collection where Mammograms were collected as
input data for the system. The second stage is Median filtering, it is used minimize noise and
improve picture quality, the median filter was used to mammogram images. By replacing each
pixel value with the median of its surrounding pixels, this technique helps to smooth out the
image. The third stage contains, Image segregation using Gaussian Mixture Model (GMM): The
Gaussian Mixture Model (GMM) is a statistical model that is used to depict the probability
distribution of data. In this research, The mammography pictures were divided into separate areas
using GMM depending on their intensity levels. This aids in the identification of possibly
malignant areas. The next stage is, Feature extraction using Gray Level Co-occurrence Matrix
(GLCM): GLCM is a statistical method used to extract texture features from the images. In this
research, GLCM was utilised to extract characteristics from mammography images such as
contrast, correlation, variance, inverse difference moment, entropy, and angular second moment.
The last stage is, Classification using Probabilistic Neural Network (PNN): A probabilistic neural
network (PNN) is a form of neural network that is often used for pattern recognition tasks. Based
on the retrieved characteristics, PNN was implemented in this study to categorise mammography
imagery into three classes: normal breast, benign breast cancer, and malignant breast cancer.

![image](https://github.com/sumedhbadnore/Breast_Cancer_Classifier/assets/66485793/b39738bf-1a5e-4e17-909d-5be5fb79f5a0)

## Dataflow Diagram

![image](https://github.com/sumedhbadnore/Breast_Cancer_Classifier/assets/66485793/30969978-266b-4961-98c2-cf52aff100ea)


## How to make the project work?

Open the project in matlab and then run guidemo and then a gui mode window will open and then just follow the steps there. For further information **watch the __[project video](https://youtu.be/Kz0Ok8bhysk).__**

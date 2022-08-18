# Melanoma Cancer Detection
> Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.



## Dataset
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion


### Project Pipeline
1. Data Reading/Data Understanding 
2. Dataset Creation: train & validation dataset from train directory with a batch size of 32, image resized to 180*180.
3. Dataset visualisation 
4. Define CNN architecture, model Building & training by rescaling images to normalize pixel values between (0,1).

5. Data Augmentation to resolve overfitting 
6. Handling class imbalances: Rectify class imbalances present in the training dataset with Augmentor library.




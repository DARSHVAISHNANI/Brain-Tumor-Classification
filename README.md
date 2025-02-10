
# Brain Tumor Classification

## Table of contents
1. [Overview](#Overview)
2. [Getting Started](#Getting-started)
    1. [Dependencies](#Dependencies)
    2. [Installation](#Installation)
3. [Results](#Results)
4. [Authors](#authors)

## Overview
This project aims to devise an automated brain tumor classification system to support radiologists and alleviate the burden of exhaustive image inspection. The applicability of the proposed solution is tested by fusing three real MRI datasets of brain tumors, encompassing four different brain images. The performance of six robust deep learning models—ResNet101V2, ResNet152V2, InceptionResNetV2, InceptionV3, Xception, and YOLOv8m-cls—is compared for automated categorization of the multi-subject and four-class brain tumor dataset.
## Getting Started

### Dependencies 
* Python 3.*
* Libraries: NumPy, Pandas, Seaborn, Matplotlib, cv2, Keras, Tensorflow
* Jupyter Notebook 
### Installation

#### **Datasets**: 

The dataset contain four different type of  Brain MRI Scans Images, which it then uses to classify a test image into one of the following four categories : 

> *Gliomas:* These are the tumors that occur in the brain and/or spinal cord. Types of glioma include: Astrocytomas, Ependymomas, and Oligodendrogliomas. Gliomas are one of the most common types of primary brain tumors. 

![Gliomas](https://github.com/DARSHVAISHNANI/Brain-Tumor-Classification/blob/307cad4e5d263a552caf866456ff88561606b9d5/Images/Te-gl_0068.jpg)

> *Meningiomas:* These are the tumors that arise from the Meninges — the membranes that surround the brain and spinal cord. Most meningiomas grow very slowly, often over many years without causing symptoms. 

![Meningiomas](https://github.com/DARSHVAISHNANI/Brain-Tumor-Classification/blob/307cad4e5d263a552caf866456ff88561606b9d5/Images/Te-me_0044.jpg)

> *Pituitary tumors:* These are the tumors that form in the Pituitary — a small gland inside the skull. Most pituitary tumors are often pituitary adenomas, benign growths that do not spread beyond the skull.

![Pituitary tumors](https://github.com/DARSHVAISHNANI/Brain-Tumor-Classification/blob/307cad4e5d263a552caf866456ff88561606b9d5/Images/Tr-pi_1418.jpg)

> *No-Tumor:* A normal brain images without any issue.

![No-tumor](https://github.com/DARSHVAISHNANI/Brain-Tumor-Classification/blob/307cad4e5d263a552caf866456ff88561606b9d5/Images/Tr-no_0376.jpg)


The complete set of files is publicly available and can be downloaded from [Kaggle](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset). Alternatively, you can find the folder (titled _Brain Tumor MRI_) in my Github repository [Brain Tumor MRI](https://github.com/DARSHVAISHNANI/Brain-Tumor-Classification/tree/master/Brain%20Tumor%20MRI).

#### **Code Files**:
##### 1. ResNet101V2: [ResNet101V2.ipynb](https://github.com/DARSHVAISHNANI/Brain-Tumor-Classification/blob/master/ResNet101V2.ipynb)

##### 2. ResNet152V2: [ResNet152V2.ipynb](https://github.com/DARSHVAISHNANI/Brain-Tumor-Classification/blob/master/ResNet152V2.ipynb)

##### 3. InceptionResNetV2: [InceptionResNetV2.ipynb](https://github.com/DARSHVAISHNANI/Brain-Tumor-Classification/blob/master/InceptionResNetV2.ipynb)

##### 4. InceptionV3: [InceptionV3.ipynb](https://github.com/DARSHVAISHNANI/Brain-Tumor-Classification/blob/master/InceptionV3.ipynb)

##### 5. Xception: [Xception.ipynb](https://github.com/DARSHVAISHNANI/Brain-Tumor-Classification/blob/master/Xception.ipynb)

##### 6. YOLOv8m-cls: [YOLOv8m-cls.ipynb](https://github.com/DARSHVAISHNANI/Brain-Tumor-Classification/blob/master/YOLOv8m-cls.ipynb)


## Results

Sample classified MRI scans:

![Results](https://github.com/nazianafis/Brain-Tumor-Classification/blob/main/screenshots/valid-img.png)


## Future Work

* Deploy the models as a web application.
## Authors


- [@Rohan Vaghela](https://www.github.com/rohan-vaghela)

- [@Jigar-sarda](https://www.github.com/jigar-sarda)


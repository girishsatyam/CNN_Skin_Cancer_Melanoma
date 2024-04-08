# MelanomaDetectionAssignment
> In this project, a custom Convolutional Neural Network (CNN) is utilized to detect melanoma within images of skin lesions across 10 distinct classes. The model achieves a prediction accuracy of 87%.

## Table of Contents

- [Melanoma-Detection-using-using-custom-cnn](#melanoma-detection-assignment-using-custom-cnn)
- [Table of Contents](#table-of-contents)
- [General Information](#general-information)
- [Algorithms Used](#algorithms-used)
- [Dataset Information](#dataset-information)
- [Steps Involved](#steps-involved)
- [Conclusion](#conclusion)
- [Technologies Used](#technologies-used)
- [Contact](#contact)
- [License](#license)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Algorithms Used

Convolutional Neural Network

### Dataset Information

The dataset comprises 2357 images representing malignant and benign oncological diseases, sourced from the International Skin Imaging Collaboration (ISIC). Images were categorized based on ISIC classifications, with subsets containing an equal number of images, except for melanomas and moles, which exhibit a slight dominance in image count.

The dataset encompasses the following diseases:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

## Steps Involved

- Loading the Data
- Constructing the Baseline Model
- Training and Evaluating the Baseline Model
- Developing an Augmented Model
- Training and Evaluating the Augmented Model
- Addressing Class Imbalance with Augmentation Techniques
- Crafting the Final Model
- Training and Evaluating the Final Model
- Validating the Model

# Conclusion

 As the model's accuracy increases, its loss decreases accordingly. The ultimate model achieves an accuracy of 87% with a loss of 0.46, demonstrating its proficiency in accurately predicting the lesion class. The augmentation of data and mitigation of class imbalance notably contributed to the enhancement of the model's accuracy.

# Technologies Used

- Python
- Tensorflow
- Keras
- Augmentor
- Matplotlib
- NumPy

# Contact

Created by [@girishsatyam] - feel free to contact with me!

# License

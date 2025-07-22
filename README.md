# Dog vs Cat Image Classification using CNN

This project implements an image classification model using Convolutional Neural Networks (CNN) to distinguish between images of dogs and cats. It uses TensorFlow, Keras, OpenCV, and Matplotlib for preprocessing, model training, and visualization.

---

##  Dataset

- **Source**: [Dog and Cat Classification Dataset - Kaggle](https://www.kaggle.com/datasets/salader/dog-and-cat-classification-dataset)
- **Structure**:
```
dog_cat_data/
├── Training/
│ ├── Dog/
│ └── Cat/
└── Testing/
├── Dog/
└── Cat/
```

---

##  Tools & Libraries

- Python
- TensorFlow / Keras
- Matplotlib
- OpenCV
- Google Colab (recommended)

---

##  Project Pipeline

###  1. Data Preprocessing
- Read image files using `cv2`.
- Resize and normalize pixel values.
- Encode labels (0: Cat, 1: Dog).
- Split into training and testing sets.

---

### Accuracy

On benchmark data (like MNIST) it is acheiving over 90+ accuracy but with real world data like this one it is around 70%
I am continuosly improving by using regularization techniques like dropout and by doing normalization.

## Images(On real world data)
<img width="1189" height="490" alt="ClassImage" src="https://github.com/user-attachments/assets/21c00c7a-99a5-4f0a-95bd-15c3d026058f" />


## Author

Buddhadeb Bhattacharya 
bhattacharyabuddhadeb147@gmail.com

### Any contribution or advice is highly acceptable.



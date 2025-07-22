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

###  Data Preprocessing
- Resize all images to a fixed dimension (e.g., 128x128 pixels).
- Normalize pixel values to the range [0, 1] by dividing by 255.
- Apply data augmentation to reduce overfitting (horizontal flip, zoom, shear, etc.).
- Encode labels (0: Cat, 1: Dog).
- Split the dataset into training and testing sets.

---

###  Build a CNN using TensorFlow
- Stack multiple Conv2D layers with ReLU activation and MaxPooling2D layers.
- Use Dropout and BatchNormalization for regularization.
- Flatten the output and connect it to Dense layers.
- The final output layer should use sigmoid activation for binary classification.

---

###  Compile and Train the Model
- Compile the model with:
  - Loss: binary_crossentropy
  - Optimizer: adam
  - Metrics: accuracy
- Train the model using model.fit() on training data.
- Use validation data to monitor model performance after each epoch.

---

###  Evaluate the Model
- Plot training and validation accuracy/loss curves using matplotlib.
- Evaluate the model on test data.
- Optionally, use metrics like accuracy, precision, recall, F1-score.

### Accuracy

On benchmark data (like MNIST) it is acheiving over 90+ accuracy but with real world data like this one it is around 70%
I am continuosly improving by using regularization techniques like dropout and by doing normalization.

## Images(On real world data)
<img width="1189" height="490" alt="ClassImage" src="https://github.com/user-attachments/assets/21c00c7a-99a5-4f0a-95bd-15c3d026058f" />


## Author

Buddhadeb Bhattacharya 
bhattacharyabuddhadeb147@gmail.com

### Any contribution or advice is highly acceptable.



# Intel Image Classification 🌍🧠

This project is a Convolutional Neural Network (CNN)–based image classifier trained on the [Intel Image Classification Dataset](https://www.kaggle.com/datasets/puneet6060/intel-image-classification), which contains natural scene images across six classes: **buildings, forest, glacier, mountain, sea, and street**.

---

## 📁 Dataset

- **Source**: Kaggle
- **Images**: 6 categories
- **Size**: ~14,000 training images, 3,000 test images
- **Image Shape**: Resized to `(150, 150, 3)`

**Classes**:
- `buildings`
- `forest`
- `glacier`
- `mountain`
- `sea`
- `street`

---

## 🧠 Model Architecture

Built with **TensorFlow / Keras**, the model uses:

- `Conv2D` layers with **ReLU** activation
- `MaxPooling2D`
- `BatchNormalization`
- `Dropout` for regularization
- `Dense` layers
- Final `softmax` layer for 6-class classification

# Flower Classification Using CNN with Data Augmentation  

## Overview  
This project focuses on **image classification** using the **Flower dataset** from TensorFlow. A **Convolutional Neural Network (CNN)** was trained to classify different types of flowers. However, the model initially suffered from **overfitting**, so **data augmentation** was applied to improve generalization.  

## Dataset  
The dataset was downloaded from TensorFlow:  

```python
dataset_url = "https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz"
data_dir = tf.keras.utils.get_file('flower_photos', origin=dataset_url, cache_dir='.', untar=True)
```
## Steps
- Model Training – Trained a CNN model on the Flower dataset.
- Overfitting Issue – The model performed well on training data but poorly on validation data.

## Solution: Data Augmentation
- Applied transformations such as rotation, flipping, and zooming.
= Helped improve model generalization and reduce overfitting.
- Evaluation – Compared accuracy and loss before and after augmentation.

## Libraries Used 
- Python
- TensorFlow/Keras
- NumPy
= Matplotlib
- OpenCV
  
Feel free to explore and contribute! 🚀

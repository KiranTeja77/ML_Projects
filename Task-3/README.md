#  Task 3: CNN for Image Classification using MNIST

##  Objective

The goal of this task is to build a Convolutional Neural Network (CNN) model to classify handwritten digits using the MNIST dataset. CNNs are specialized deep learning models that are particularly effective at image classification tasks. The dataset includes 28x28 grayscale images of digits (0–9), and the model must predict the correct digit from the image.

##  Dataset

- **Source**: MNIST dataset (loaded via `tensorflow.keras.datasets`)
- **Train Samples**: 60,000
- **Test Samples**: 10,000
- Each image is 28x28 pixels with 1 grayscale channel.

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib (for plotting training metrics)

##  Steps Performed

1. Loaded MNIST data using Keras.
2. Normalized the pixel values to a range of 0 to 1.
3. Reshaped data into CNN-compatible format (28x28x1).
4. One-hot encoded the output labels.
5. Designed a CNN architecture with:
   - Conv2D layers
   - MaxPooling2D
   - Dense + Softmax
6. Compiled and trained the model.
7. Evaluated model performance and displayed test accuracy.

##  How to Run

```bash
jupyter notebook CNN_image_classification.ipynb
```

No external data required — MNIST is automatically downloaded via Keras.

## Output

- Training & validation accuracy/loss per epoch
- Final test accuracy
- Model summary
- ![Image](https://github.com/user-attachments/assets/6dff5bfd-580d-4e4d-83d7-9edba6cbbb8c)

## Summary

This task illustrates how to use convolutional neural networks for image classification. The MNIST dataset is a great beginner-level dataset for deep learning practitioners. The trained model achieved high accuracy and demonstrates the effectiveness of CNNs in pattern recognition tasks.

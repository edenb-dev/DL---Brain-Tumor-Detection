# Brain Tumor Classification using CNN

This project focuses on developing a deep learning model for classifying brain tumors in MRI images. The model is based on a Convolutional Neural Network (CNN) and aims to classify images into four categories: glioma, meningioma, pituitary, and no tumor.

## Project Features

- **Dataset**: The dataset consists of 7,023 images classified into four categories, sourced from multiple datasets.
- **Model**: The optimal model architecture includes four convolutional layers and a fully connected layer with 512 neurons.
- **Optimization**: The model uses Adam optimization and categorical cross-entropy loss function.
- **Visualization Tool**: Grad-CAM was used to highlight critical areas in the images that influenced the model's decisions.

## Dependencies

- TensorFlow
- Keras
- NumPy
- Matplotlib

## Results
The model demonstrated excellent performance in classifying brain tumors in MRI images. The accuracy was consistent across multiple trials with slight variations in performance.

## Contribution
Contributions are welcome! If you find any bugs or have ideas for improvements, please open an issue or submit a pull request.

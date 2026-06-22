# 🧠 Brain Tumor Detection using CNN

A Deep Learning project that detects and classifies brain tumors from MRI images using a Convolutional Neural Network (CNN). The model predicts one of four categories:

- Glioma Tumor
- Meningioma Tumor
- Pituitary Tumor
- No Tumor

# 🚀 Features
- MRI image classification using CNN
- Data augmentation for improved model performance
- Validation during training
- Predicts tumor type with confidence score
- Displays the input image and prediction result

# 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- OpenCV (optional)
- Jupyter Notebook

```

## 🧠 Model Architecture
- Conv2D + ReLU
- MaxPooling2D
- Conv2D + ReLU
- MaxPooling2D
- Conv2D + ReLU
- MaxPooling2D
- Conv2D + ReLU
- MaxPooling2D
- Flatten Layer
- Dense Layer (512 neurons)
- Dropout (0.5)
- Output Layer (Softmax - 4 Classes)

## 📊 Training
- Image Size: 150 × 150
- Batch Size: 32
- Epochs: 50
- Validation Split: 10%


```

## 📈 Output
The model predicts the brain MRI image category and displays:

- Predicted Tumor Type
- Confidence Score (%)
- Input MRI Image with Prediction

## 📌 Future Improvements
- Improve model accuracy using transfer learning
- Deploy as a web application using Flask or Streamlit
- Add real-time MRI image upload and prediction

## 👨‍💻 Author
**Adithya VS**  
BCA Graduate | Aspiring AI Developer | Machine Learning & Deep Learning Enthusiast

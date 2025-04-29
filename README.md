# SolarGuard-Intelligent-Defect-Detection-on-Solar-Panels-using-DeepLearning
This project uses deep learning to classify images of solar panels into six categories: Clean, Dusty, Bird-Drop, Electrical-Damage, Physical-Damage, and Snow-Covered. A ResNet-18 model is used for image classification. Based on the predicted class, the system suggests an appropriate solution to support maintenance decisions.
# Data Collection
- The dataset consists of labeled images of solar panels categorized into six classes: Clean, Dusty, Bird-Drop, Electrical-Damage, Physical-Damage, and Snow-Covered.
- Each image represents a real-world scenario affecting panel efficiency.
- The dataset is organized into folders by class and used for training and testing the ResNet-18 model.

![Screenshot (88)](https://github.com/user-attachments/assets/fbdff563-a916-41df-b5f2-096299cab59d)
![Screenshot (87)](https://github.com/user-attachments/assets/1d0a11d8-3024-43f4-a7d4-e886b07ad26b)

# Data Preprocessing
Preprocessing steps such as resizing, normalization, and augmentation were performed to prepare the images for model training.
- Image Resizing: All images were resized to a fixed dimension (e.g., 224×224) to match the input size expected by the ResNet-18 model.
- Data Augmentation: Techniques such as horizontal/vertical flipping, rotation, and zooming were applied to increase dataset variability and reduce overfitting.
- Train-Test Split: The dataset was split into training and validation/test sets to evaluate model performance effectively.
# Frameworks
![framewors](https://github.com/user-attachments/assets/cde908f4-e78e-4d60-9189-b0baa13fc6f9)
# 🧠 Model Building
Two deep learning models were developed and evaluated for classifying solar panel images:
- Custom Convolutional Neural Network (CNN)
- Transfer Learning with ResNet18
# Model Evaluation Metrics
## Custom Convolutional Neural Network (CNN)
![Screenshot (91)](https://github.com/user-attachments/assets/732bd814-0b4d-488d-82f4-b2f7f6f5bea3)
![Screenshot (90)](https://github.com/user-attachments/assets/ca42fef5-7a07-4220-8ccc-1f9de1e87f46)
![Screenshot (89)](https://github.com/user-attachments/assets/a2e7008a-925f-488b-9b9c-1c05b50c7bad)

## Transfer Learning with ResNet18
![Screenshot (92)](https://github.com/user-attachments/assets/e827d4d0-101d-4f6a-a3f1-994778363d12)
![confusion_matrix](https://github.com/user-attachments/assets/b2127da8-1654-41b2-951f-398b23ac2388)
![Screenshot (86)](https://github.com/user-attachments/assets/559cddfd-d5fc-470f-9448-9d7a12431cdd)







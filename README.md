# SolarGuard-Intelligent-Defect-Detection-on-Solar-Panels-using-DeepLearning
This project uses deep learning to classify images of solar panels into six categories: Clean, Dusty, Bird-Drop, Electrical-Damage, Physical-Damage, and Snow-Covered. A ResNet-18 model is used for image classification. Based on the predicted class, the system suggests an appropriate solution to support maintenance decisions.
# Data Collection
- The dataset consists of labeled images of solar panels categorized into six classes: Clean, Dusty, Bird-Drop, Electrical-Damage, Physical-Damage, and Snow-Covered.
- Each image represents a real-world scenario affecting panel efficiency.
- The dataset is organized into folders by class and used for training and testing the ResNet-18 model.
![Screenshot (88)](https://github.com/user-attachments/assets/fbdff563-a916-41df-b5f2-096299cab59d)
# Data Preprocessing
Preprocessing steps such as resizing, normalization, and augmentation were performed to prepare the images for model training.
- Image Resizing: All images were resized to a fixed dimension (e.g., 224×224) to match the input size expected by the ResNet-18 model./
- Data Augmentation: Techniques such as horizontal/vertical flipping, rotation, and zooming were applied to increase dataset variability and reduce overfitting./
- Train-Test Split: The dataset was split into training and validation/test sets to evaluate model performance effectively.
# Frameworks
![framewors](https://github.com/user-attachments/assets/cde908f4-e78e-4d60-9189-b0baa13fc6f9)
 

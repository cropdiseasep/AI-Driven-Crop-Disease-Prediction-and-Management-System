# AI-Driven-Crop-Disease-Prediction-and-Management-System
# Project Overview :
AI-Driven Crop Disease Prediction and Management System is a deep learning-based mobile-friendly solution designed to detect and classify banana plant diseases from leaf images. The system uses advanced image classification models to assist farmers in identifying plant diseases early and managing them effectively, thereby promoting sustainable agriculture.

# Target Domains:
Deep Learning and Image Classification

Agricultural Technology (AgriTech)

Mobile/Cloud-Based AI Applications

Sustainable Farming and Food Security

# Key Features:
Real-time disease detection from banana leaf images.

Trained using CNN, EfficientNet, DenseNet, MobileNetV2, InceptionV3, and ResNeXt.

Hosted and executed on Google Colab using PyTorch and TensorFlow.

Image preprocessing and augmentation for robustness.

Confusion matrix, classification report, and performance metrics for model evaluation.

Capability for mobile app integration and future real-time deployment.

# Phase 1: Project Conceptualization and Planning
Goal Definition:

Automate disease detection in banana crops using AI.

Focus on common diseases: Black Sigatoka, Yellow Sigatoka, Potassium Deficiency, Panama Disease, and healthy classification.

# Technical Planning:

Dataset collection from local farms.

Use of image-based deep learning models for classification.

Execution and evaluation using cloud-based GPU platforms (Google Colab).

# Phase 2: Data Acquisition, Preprocessing, and Integration
Data Acquisition:

Banana leaf images captured from farms.

Dataset structured into five classes.

Preprocessing:

Resized images (224x224), normalization, color formatting.

Augmentation: rotation, flipping, zooming, brightness adjustments.

Integration:

Google Drive used for dataset storage and model result tracking.

Used PyTorch, TensorFlow, and supporting libraries like OpenCV, NumPy, Matplotlib.

# Phase 3: Model Development, Training, and Evaluation
Model Training:

Models trained: EfficientNet-B0, MobileNetV2, DenseNet121, InceptionV3, ResNeXt50_32x4d, and a Custom CNN.

Uniform training parameters for comparison: 10 epochs, batch size 32, Adam optimizer.

Evaluation Metrics:

Accuracy, Precision, Recall, F1-score.

Confusion Matrix and Classification Report for each model.

Best results: ResNeXt and DenseNet with accuracy over 94%.

# Phase 4: Final Optimization and Presentation
Optimization:

Comparison table with training/validation accuracy and loss.

Evaluation on unseen test data.

Presentation:

Demonstrated classification reports and confusion matrices.

Showed model outputs and performance graphs.

Technical Content and Implementation
Language: Python 3.8+

Platform: Google Colab

Libraries: PyTorch, TensorFlow, Keras, OpenCV, Matplotlib, Scikit-learn

Models: EfficientNet, MobileNetV2, DenseNet, InceptionV3, ResNeXt, Custom CNN

Dataset Storage: Google Drive

Innovation and Originality
Specialized focus on banana leaf disease detection.

Use of self-curated dataset from real farms.

Multiple deep learning models evaluated for performance.

Practical, scalable, and ready for real-world application.

# Team Collaboration
Team Members:

Sarthak Milan Patil (TY DS-07) (221106002)

Krishna Pravin Vispute (TY DS-13) (221106011)

Vaibhavi Suyog Patil (TY DS-29) (221106028)

Ruchika Sunil Mali (TY DS-38) (221106038)

# Role Distribution:

Divided into modules: data preparation, model training, evaluation, documentation.

Scalability and Practical Applications
Can be adapted for other crops and diseases.

Useful in mobile applications for field use by farmers.

Scope for integration with agritech platforms and government programs.

# Future Scope
Real-time deployment via mobile app.

Expansion to other crops beyond banana.

AR-based diagnostic interface for interactive use.

Integration with agriculture support systems and multilingual interfaces.

Deliverables and Outcomes
Fully trained and evaluated deep learning models.

Structured and preprocessed banana leaf disease dataset.

Visual analytics: training curves, confusion matrices.

Full documentation and methodology.

Plan for Semester VII continuation (deployment and optimization).

# Conclusion
This project successfully demonstrates the power of AI in agriculture by developing an accurate, scalable, and efficient banana leaf disease classification system. The work lays a solid foundation for real-world implementation that can assist farmers in early disease diagnosis, ultimately promoting sustainable farming practices.

# Introduction:
This project uses deep learning to classify images of fruits into six categories:
Fresh Apple, Rotten Apple, Fresh Banana, Rotten Banana, Fresh Orange, Rotten Orange.
With the power of a fine-tuned VGG16 model, the system achieves high accuracy in distinguishing between fresh and rotten fruits, making it useful for quality control and smart inventory systems in agriculture or retail.

#  Features:
   Trained VGG16 model with transfer learning
   6-class fruit classification (Fresh/Rotten × 3 types)
   Image preprocessing and augmentation
   Model accuracy >96%
   Gradio-powered web app for real-time predictions
   Ready-to-deploy .keras model

# Tools & Libraries Used:
    Python
    TensorFlow / Keras
    NumPy / Pandas
    Matplotlib / Seaborn (for visualization)
    Gradio (for UI)
    Jupyter Notebook / Google Colab

#  Data Preprocessing:
   Resizing all images to 256x256
   Normalizing pixel values
   Splitting into train and validation sets
   Data augmentation (flip, zoom, rotate)

#  Model Architecture: VGG16:

  Input Layer: (256x256x3)

 Base: VGG16 (without top layers, pretrained on ImageNet)

 Custom top layers:

 Flatten

 Dense (ReLU)

 Dropout

 Output (Softmax with 6 units)

 Loss: categorical_crossentropy

 Optimizer: Adam

 Metrics: accuracy

#  Model Performance:
   Training Accuracy: 96%

   Validation Accuracy: 97%

   Loss and accuracy plots available in notebook

# Setup Instructions:
   git clone https://https://github.com/MrHasnain2522/Fruit-freshness-classifier_using_VGG16

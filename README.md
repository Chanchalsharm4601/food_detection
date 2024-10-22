# Project Overview
This project focuses on classifying food images through the application of a pre-trained TensorFlow model, allowing users to identify various food categories accurately. Leveraging OpenCV for robust image processing, the system enhances image quality and prepares it for classification tasks. To optimize performance, the project incorporates TensorFlow’s GPU support, enabling faster training and inference when compatible hardware is available. This integration not only improves the efficiency of the model but also enhances user experience by providing quick and reliable predictions for food items based on their images.

# Key Features

## Model Loading and Prediction: 
The project includes an interactive Jupyter notebook that facilitates the loading of a pre-trained TensorFlow model. Users can seamlessly upload food images and receive instant predictions regarding their categories.

## Custom Food Image Classifier: 
At the core of the project is a custom Python module, food_image_classifier, designed specifically for image processing and classification. This module streamlines the process of transforming raw image inputs into formatted data that the model can interpret, ensuring accuracy and consistency in predictions.

## GPU Acceleration: 
By utilizing TensorFlow's built-in GPU capabilities, the project significantly reduces computation time for both model training and inference. This feature allows users with compatible hardware to take advantage of parallel processing, resulting in enhanced speed and efficiency, particularly for large datasets or real-time image classification tasks.


# Installation

Clone the Repository: git clone https://github.com/Chanchalsharm4601/food_detection.git 
Install Required Packages: You can install all necessary Python packages using the following commands:
  ## pip install tensorflow
  ## pip install opencv-python
  ## pip install nbimporter
  
Launch Jupyter Notebook: To open and run the Jupyter Notebook files, follow these steps:
# Open the project folder in Jupyter:
  ## jupyter notebook
This command will launch the Jupyter Notebook interface in your browser. Navigate to the folder where the notebooks (load_model.ipynb, etc.) are located, and open them.


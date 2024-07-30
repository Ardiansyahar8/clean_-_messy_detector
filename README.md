# Clean and Messy Room Classifier
This project provides a machine learning model to classify images of rooms and predict whether they are tidy (clean) or messy.

## Table of Contents
-Introduction
- Features
- Installation
- Usage
- Dataset
- Model
- Results
- License
  
## Introduction
The Clean and Messy Room Classifier is a deep learning project that aims to automatically classify images of rooms as either tidy or messy. This can be useful for various applications such as home automation, housekeeping services, and personal productivity tools.

## Features
Classifies room images into two categories: tidy (clean) and messy.
Utilizes a convolutional neural network (CNN) for image classification.
Easy-to-use interface for training and predicting with your own images.
Installation
To run this project locally, follow these steps:

Clone the repository:

sh
Salin kode
git clone https://github.com/yourusername/clean-messy-room-classifier.git
cd clean-messy-room-classifier
Create and activate a virtual environment:

sh
Salin kode
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install the required dependencies:

sh
Salin kode
pip install -r requirements.txt
Usage
Prepare your dataset:
Ensure you have a dataset of room images labeled as either "clean" or "messy". Place the images in the data/ directory with the following structure:

kotlin
Salin kode
data/
    clean/
        image1.jpg
        image2.jpg
        ...
    messy/
        image1.jpg
        image2.jpg
        ...
Train the model:

sh
Salin kode
python train.py
Predict using the model:

sh
Salin kode
python predict.py --image_path path_to_your_image.jpg
Dataset
The dataset used for this project should contain labeled images of rooms categorized into "clean" and "messy". You can create your own dataset or use publicly available datasets.

## Model
The model is built using a Convolutional Neural Network (CNN) with several layers for feature extraction and classification. The architecture can be modified in the model.py file.

## Results
The model's performance is evaluated using accuracy, precision, recall, and F1-score. Example results can be found in the results/ directory.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact

<p>Creator<br>

    
Ardiansyah </p> 



<p>Agroindustrial Engineering<br>
    Universitas Linggabuana PGRI Sukabumi</p>


If you have any questions or suggestions, feel free to open an issue or contact us at (mail to: Ardiansyahar8@gmail.com ).

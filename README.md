## Chinese Handwritten Digit Classifier using CNN
A deep learning project that uses a Convolutional Neural Network (CNN) to classify handwritten digits from 0 to 9 in Chinese numerals. The model is trained on a Chinese handwritten digit dataset, achieving high accuracy in digit recognition tasks.

### Project Overview
This project implements a CNN-based classifier to recognize Chinese handwritten digits. It includes:

Data loading & preprocessing

CNN architecture design

Model training & evaluation

Accuracy visualization

### Dataset
The dataset contains grayscale images of handwritten digits (0-9) written in Chinese style.
Each image is labeled with its corresponding digit.

Note: If you want to run this project, you’ll need to download the dataset from the official source

### Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/<your-username>/chinese-hand-written-digit-classifier-using-cnn.git
cd chinese-hand-written-digit-classifier-using-cnn

Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
🚀 Usage
Open the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook chinese-hand-written-digit-classifier-using-cnn.ipynb
Run all cells to:

Load & preprocess the dataset

Train the CNN model

Evaluate performance

### Model Architecture
The CNN architecture consists of:

Conv2D layers for feature extraction

MaxPooling layers for downsampling

Dropout for regularization

Fully connected Dense layers for classification

The model shows strong performance in recognizing Chinese handwritten digits.

Example prediction:

Input Image	Predicted Label
7

### Requirements
Python 3.x

TensorFlow / Keras

NumPy

Matplotlib

Jupyter Notebook

Install all requirements via:

bash
Copy
Edit
pip install -r requirements.txt

### License
This project is licensed under the MIT License - see the LICENSE file for details.

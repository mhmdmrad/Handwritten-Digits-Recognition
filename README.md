
# Handwritten Digits Recognition  

A neural network trained on the MNIST dataset to recognize handwritten digits. It can classify external 28x28 images placed in the `digits/` directory.  

## Features  
- Trains a neural network on the MNIST dataset.  
- Saves and loads trained models for future use.  
- Predicts digits from custom 28x28 grayscale images.  
- Displays predictions using Matplotlib.  

## Installation  

1. Clone the repository:  
   ```bash
   git clone https://github.com/mhmdmrad/handwritten-digits-recognition.git
   cd handwritten-digits-recognition
   ```  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  

## Usage  

### Train the Model  
Run the training script to train a neural network on the MNIST dataset:  
```bash
python train.py --train
```  

### Predict Digits  
Place 28x28 grayscale images in the `digits/` directory and run:  
```bash
python predict.py
```  


# Data Augmentation with DCGAN on ELPV Dataset

## Overview
This repository contains a Jupyter notebook that demonstrates data augmentation using a Deep Convolutional Generative Adversarial Network (DCGAN). The notebook is designed to augment the ELPV dataset, specifically focusing on generating high-quality images of solar cells.

## Objectives
1. Load images from the ELPV dataset.
2. Define and implement the DCGAN architecture.
3. Train the DCGAN model:
   - Track and save generator and discriminator loss after each epoch.
   - Save model checkpoints every 10 epochs.
   - Generate and save images after every 10 epochs.
4. Use the trained generator to create new images.

## Setup

### Prerequisites
- Python 3.x
- TensorFlow 2.x
- Matplotlib
- Numpy
- PIL
- ImageIO

### Installation
Clone this repository and install the required packages:
```bash
git clone <repository-url>
cd <repository-directory>
pip install -r requirements.txt
```

### Dataset
Ensure you have the ELPV dataset organized in a directory. The notebook expects the following directory structure:
```
/kaggle/input/elpv-classwise/1/
```

## Usage
Open the notebook `DCGAN-final-1.ipynb` in Jupyter or any compatible environment and run the cells sequentially. Adjust the path to your dataset accordingly.

## Results
After training, the model will generate new images simulating the input dataset, which will be saved in the specified output directory.

## License
Specify the license under which the code is made available.

## Contributors
List the contributors to the project.

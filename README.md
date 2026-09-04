# Cats Dogs Image Classification MobileNetV2
A computer vision project for classifying cats and dogs images using MobileNetV2, a Convolutional Neural Network (CNN) architecture.

## Dataset
The dataset was obtained from Kaggle:
https://www.kaggle.com/datasets/blourdhuraju/dogs-vs-cats-classification
- Creator: Lourdu Raju
- License: CC0: Public Domain
- Classes: Cats and Dogs
- Total images: 24,930
The dataset is not included in this repository because of its large size.

## Method
1. Image resizing to 224 × 224 pixels
2. Random horizontal flipping
3. MobileNetV2 preprocessing
4. Transfer learning using ImageNet weights
5. Model training and evaluation

## Model Configuration
| Component | Configuration |
|---|---|
| Model | MobileNetV2 |
| Input Size | 224 × 224 × 3 |
| Batch Size | 32 |
| Epochs | 5 |
| Optimizer | Adam |
| Loss Function | Binary Crossentropy |
| Output Activation | Sigmoid |

## Results
| Metric | Result |
|---|---:|
| Test Accuracy | 98.76% |
| Test Loss | 0.0328 |
| Test Images | 2,495 |
| Correct Predictions | 2,464 |
| Incorrect Predictions | 31 |

## Project Structure
```text
cats-dogs-image-classification-mobilenetv2/
├── README.md
├── cats_vs_dogs_mobilenetv2.ipynb
└── requirements.txt
```
## How to Run
1. Download the dataset from Kaggle.
2. Store the dataset in Google Drive.
3. Open the notebook using Google Colab.
4. Mount Google Drive.
5. Adjust the dataset path if needed.
6. Run the notebook from beginning to end.

## Technologies
- Python
- TensorFlow
- Keras
- MobileNetV2
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Author
Anggi Rahmadillah

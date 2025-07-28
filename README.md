# Face_Mask_Detection
# Face Mask Detection Using CNN

This project uses a Convolutional Neural Network (CNN) to classify whether people in images are wearing face masks or not. It is trained on the public [Face Mask Dataset](https://www.kaggle.com/datasets/omkargurav/face-mask-dataset) available on Kaggle.



## Dataset

- **Source**: [Kaggle - Face Mask Dataset by Omkar Gurav](https://www.kaggle.com/datasets/omkargurav/face-mask-dataset)
- **Structure**:
  - `/with_mask/` — Images of people wearing masks
  - `/without_mask/` — Images of people without masks



## Model Architecture

The CNN model contains:
- 2 Convolutional + MaxPooling layers
- 1 Dense layer with ReLU
- Dropout layer for regularization
- Final Softmax layer for binary classification


## How to Run

1. Clone this repository:

```bash
git clone https://github.com/your-username/face-mask-detection.git
cd face-mask-detection

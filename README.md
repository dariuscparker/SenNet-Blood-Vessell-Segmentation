# U-Net, Attention U-Net, and Ensemble for Image Segmentation

## Description

This notebook implements **U-Net** and **Attention U-Net** models for segmenting medical images, specifically focusing on blood vessel structures. It also combines predictions from both models to create an ensemble, aiming to improve segmentation accuracy.

The models use a **ResNet50** backbone pre-trained on ImageNet, and the loss function combines **Binary Cross-Entropy (BCE)** with the **Dice coefficient** to optimize pixel-wise accuracy and segmentation quality.

## How to Run

### In Kaggle:

1. Open the notebook in the **Kaggle environment**:  
   [Kaggle Notebook: Sennet U-Net, Attention U-Net, and Ensemble](https://www.kaggle.com/code/deeparker/sennet-unet-attention-unet-and-ensemble)
2. Enable **GPU acceleration** for faster training.
3. Click "Run All" to execute all cells in the notebook.

### Locally:

1. Download the notebook and dataset to your machine.
2. Download the dataset from Kaggle:  
   [Blood Vessel Segmentation Dataset](https://www.kaggle.com/competitions/blood-vessel-segmentation/data)
3. Install the necessary dependencies:
   ```bash
   pip install tensorflow keras spacy nltk opencv-python-headless matplotlib

# Machine Learning Final Competition - Audio Classification
CSCI-SHU 360 Machine Learning Final Competition [Spring 2024]

**Test accuracy: 82.18%**

## Task

Classify voice types in 3-second song snippets into 4 categories:
- **Class 0**: No voices present
- **Class 1**: Male-like voice present
- **Class 2**: Female-like voice present  
- **Class 3**: Multiple voices present

Dataset: 11k training samples, 2-3k test samples

## Usage

Run the notebooks in order:

1. **`01_audio_preprocessing.ipynb`**  
   Converts MP3 files to mel spectrograms with data augmentation, saves as `.npy` files

2. **`02_model_training.ipynb`**  
   Trains a 14-layer CNN with residual blocks on the spectrograms

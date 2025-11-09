# Training-Baseling-CNN-on-Sports-Balls
This notebook was completed for **AA 5750: Contemporary Issues in Analytics (Deep Learning Module)**.   It trains a baseline CNN to classify images of sports balls (e.g., football, basketball, baseball, cricket, golf, hockey, bowling, billiard).

The code emphasizes experimentation and concept learning rather than production refinement.  
Original structure and outputs are retained to show the authentic academic workflow.

## Overview
- **Dataset:** Custom sports ball images (train/val/test)  
- **Model:** Small CNN with 3 conv layers and ReLU activations  
- **Optimizer:** Adam (lr = 1e-3)  
- **Metrics:** Accuracy, Precision, Recall, F1, Confusion Matrix  
- **Result:** ≈ 82 % test accuracy (0.825 overall F1)  

## Concepts Covered
- Data preprocessing and augmentation (`torchvision.transforms`)
- CNN architecture design and training loop
- Evaluation with classification report & confusion matrix
- Visualization of performance metrics via Matplotlib/Seaborn

## How to Run
**Colab:** Upload `Week_3_Assignment.ipynb` and run all cells.  
**Local:**
```bash
pip install -r requirements.txt
jupyter notebook Week_3_Assignment.ipynb

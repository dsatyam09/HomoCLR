
### Directory Description
- `dataset/`: Contains the data used for training and testing the models.
  - `unlabeled/`: Holds unlabeled data samples.
  - `labeled/`: Organized into training and testing datasets, each containing subdirectories for `Malignant`, `Benign`, and `Normal` categories.
- `src/`: Core codebase containing scripts for data loading, model training, fine-tuning, evaluation, and utilities.
  - `data_loader.py`: Handles data preprocessing and loading.
  - `simclr.py`: Implements the SimCLR model.
  - `train_simclr.py`: Script for training the SimCLR model.
  - `fine_tune.py`: Used for fine-tuning the pre-trained models on the labeled dataset.
  - `utils.py`: Contains utility functions used throughout the project.
  - `visualize.py`: For visualizing results and generating plots.
  - `evaluation.py`: Code for evaluating the trained models.
- `checkpoints/`: Stores saved model checkpoints during training.
- `results/`: Contains results generated by the project, including visualizations and performance metrics.
  - `tsne/`: t-SNE visualizations of model features.
  - `gradcam/`: Grad-CAM visualizations of model attention.
  - `training_loss/`: Training loss curves.
  - `classification_metrics/`: Evaluation metrics of the classification models.
- `main.py`: The main entry point for running the application.
- `requirements.txt`: Lists the dependencies required to run the project.
- `README.md`: Documentation for the project.

## Installation

To set up the project environment, follow these steps:

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/EcoSond.git
   cd EcoSond

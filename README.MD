EcoSond/
├── dataset/
│   ├── unlabeled/
│   └── labeled/
│       ├── train/
│       │   ├── Malignant/
│       │   ├── Benign/
│       │   └── Normal/
│       └── test/
│           ├── Malignant/
│           ├── Benign/
│           └── Normal/
├── src/
│   ├── __init__.py             # Ensure this file exists
│   ├── data_loader.py
│   ├── simclr.py
│   ├── train_simclr.py
│   ├── fine_tune.py
│   ├── utils.py
│   ├── visualize.py
│   └── evaluation.py
├── checkpoints/
├── results/
│   ├── tsne/
│   ├── gradcam/
│   ├── training_loss/
│   └── classification_metrics/
├── main.py
├── requirements.txt
└── README.md

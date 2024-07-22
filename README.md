medical-image-captioning/
│
├── data/
│   ├── images/                  # Medical images
│   ├── captions/                # Corresponding captions
│   └── preprocess.py            # Data preprocessing scripts
│

├── models/
│   ├── vit_model.py             # Vision Transformer model
│   ├── gpt_model.py             # GPT-based text generation model
│   └── captioning_model.py      # Combined model for image captioning
│

├── notebooks/
│   └── EDA.ipynb                # Exploratory Data Analysis
│

├── scripts/
│   ├── train.py                 # Training script
│   ├── evaluate.py              # Evaluation script
│   └── predict.py               # Prediction script
│

├── utils/
│   ├── data_loader.py           # Data loading utilities
│   ├── metrics.py               # Evaluation metrics
│   └── config.py                # Configuration file
│

├── README.md                    # Project overview
├── requirements.txt             # Required packages
└── .gitignore                   # Git ignore file


├── README.md
├── data/
│   ├── raw/                # original datasets (do not commit large files)
│   ├── processed/          # cleaned & processed datasets
│   └── sample_input.csv    # example input for inference
├── notebooks/
│   ├── eda.ipynb
│   ├── feature_engineering.ipynb
│   └── model_comparison.ipynb
├── src/
│   ├── data/
│   │   ├── download_data.py
│   │   ├── preprocess.py
│   │   └── features.py
│   ├── models/
│   │   ├── train.py
│   │   ├── evaluate.py
│   │   ├── rf_model.py
│   │   ├── xgb_model.py
│   │   └── lstm_model.py
│   ├── api/
│   │   ├── app.py         

│   │   └── predict.py
│   └── utils/
│       ├── metrics.py
│       └── viz.py
├── scripts/
│   ├── run_tra_

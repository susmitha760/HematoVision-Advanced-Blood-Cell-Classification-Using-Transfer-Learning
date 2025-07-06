# HematoVision: Advanced Blood Cell Classification Using Transfer Learning

HematoVision is a deep learning-based system designed to classify blood cell types using the BCCD dataset and transfer learning with ResNet50.

## Features
- Blood cell image classification
- Transfer Learning using ResNet50
- Flask API for deployment
- Evaluation metrics: Accuracy, Confusion Matrix, F1-score

## Dataset
This project uses the BCCD dataset: https://github.com/Shenggan/BCCD_Dataset

## How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/HematoVision.git
cd HematoVision
```

### 2. Install Requirements
```bash
pip install -r requirements.txt
```

### 3. Train the Model
```bash
python src/train.py
```

### 4. Run Flask API
```bash
python app/app.py
```

## Folder Structure
- `data/` - Download and place BCCD dataset here
- `src/` - Code for data loading, model, training, evaluation
- `app/` - Flask API for model deployment
- `saved_models/` - Trained weights (ResNet50 fine-tuned)
- `notebooks/` - Jupyter notebooks for EDA and prototyping

## License
MIT

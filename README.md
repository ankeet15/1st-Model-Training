# Multi-Model-Training
Model Training and testing using IRIS dataset.

# Iris Species Classification Project

This project implements and compares three different machine learning approaches (SVM, CNN, and Vision Transformer) for classifying Iris flower species. The project includes data preprocessing, model training, evaluation, and comprehensive performance analysis.

## Project Overview

The project aims to:
1. Implement three different classification models (SVM, CNN, and ViT)
2. Compare their performance metrics (accuracy, training time, inference time)
3. Visualize and analyze the results
4. Organize the processed data into appropriate folder structures

## Project Structure

```
project/
│
├── dataset/
│   ├── setosa/
│   ├── versicolor/
│   └── virginica/
│
├── models/
│   ├── SVM_model/
│   ├── VT_model/
│   └── CNN_model/
│
├── evaluation/
│   ├── svm_evaluation_metrics.xlsx
│   ├── cnn_evaluation_metrics.xlsx
│   └── vit_evaluation_metrics.xlsx
│
└── visualizations/
    ├── training_history.png
    └── confusion_matrix.png
```

## Requirements

- Python 3.8+
- PyTorch
- TensorFlow
- scikit-learn
- transformers
- pandas
- numpy
- matplotlib
- seaborn

## Installation

```bash
pip install -r requirements.txt
```

## Usage

1. Data Preparation:
```python
python data_preprocessing.py
```

2. Model Training:
```python
python train_svm.py
python train_cnn.py
python train_vit.py
```

3. Evaluation:
```python
python evaluate_models.py
```

## Model Performance Comparison

### Accuracy
- SVM: ~96%
- CNN: ~97%
- Vision Transformer: ~88%

### Training Time
- SVM: Fastest
- CNN: Moderate
- Vision Transformer: Slowest

### Inference Time
- SVM: Fast
- CNN: Moderate
- Vision Transformer: Slowest

## Visualizations

The project includes various visualizations:
- Confusion matrices
- Training history plots
- Performance comparison charts
- Classification report metrics

## Contributing

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Iris dataset from UCI Machine Learning Repository
- Vision Transformer implementation based on the huggingface transformers library
- scikit-learn for SVM implementation

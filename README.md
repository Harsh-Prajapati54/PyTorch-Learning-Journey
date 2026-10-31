# 🔥 PyTorch Deep Learning

A structured collection of Jupyter notebooks covering deep learning concepts from fundamentals to advanced architectures using PyTorch.

## 📚 Notebooks

| # | Notebook | Topic | Status |
|---|---|---|---|
| 00 | [Introduction to PyTorch](notebooks/00_Introduction_to_PyTorch.ipynb) | Tensors, operations, NumPy interop, GPU basics | ✅ |
| 01 | [ANN & Linear Regression](notebooks/01_ANN_Linear_Regression.ipynb) | Neural network workflow, linear regression with `nn.Module` | ✅ |
| 02 | [Binary Classification](notebooks/02_Binary_Classification.ipynb) | Binary classification with neural networks (`make_circles`) | ✅ |
| 03 | [Multiclass Classification](notebooks/03_Multiclass_Classification.ipynb) | Multi-class classification with softmax (`make_blobs`) | ✅ |
| 04 | [CNN Fundamentals](notebooks/04_CNN_Fundamentals.ipynb) | Convolutional neural networks, `Conv2d`, `MaxPool2d` | ✅ |
| 05 | [Custom Datasets & DataLoaders](notebooks/05_Custom_Datasets_and_DataLoaders.ipynb) | Custom `Dataset`, `DataLoader`, data augmentation, TinyVGG | ✅ |
| 06 | [Transfer Learning](notebooks/06_Transfer_Learning.ipynb) | Pretrained models, feature extraction, fine-tuning | ✅ |
| 07 | [RNN & Time Series](notebooks/07_RNN_Time_Series_Forecasting.ipynb) | RNNs, LSTMs, time series forecasting | ✅ |

## 📁 Project Structure

```
PyTorch/
├── notebooks/          # All learning notebooks (ordered 00-07)
├── utils/              # Helper functions and utilities
├── models/             # Saved model weights (.pth files)
├── data/               # Datasets (FashionMNIST, pizza_steak_sushi, CIFAR-10)
├── custom_data/        # Custom test images for inference
├── requirements.txt    # Python dependencies
└── README.md           # This file
```

## 🚀 Getting Started

```bash
# Create virtual environment
python -m venv .venv
.venv\Scripts\activate      # Windows

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook notebooks/
```

## 🛠️ Dependencies

- Python 3.12+
- PyTorch
- torchvision
- matplotlib
- scikit-learn
- numpy
- pandas

See [requirements.txt](requirements.txt) for full list.

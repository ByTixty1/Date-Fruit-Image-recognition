# Date Fruit Classification with K-Fold Cross-Validation 🍇📊

This repository contains a deep learning project for classifying date fruit images using K-Fold Cross-Validation and transfer learning (EfficientNet-B0).

## 📁 Project Structure

```
├── Date_classification_K_fold.ipynb  # Main notebook with training code and results
├── /dataset/                         # Directory to store training images (not included)
├── /models/                          # Saved models (optional)
├── requirements.txt                  # Python dependencies
└── README.md                         # Project overview and usage
```

## 🚀 Features

- Uses **EfficientNet-B0** for high-performance image classification
- Implements **K-Fold Cross-Validation** for robust evaluation
- Evaluates performance using accuracy, confusion matrix, and classification report
- Custom preprocessing pipeline with PyTorch and torchvision

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/date-fruit-classification.git
   cd date-fruit-classification
   ```

2. Create a virtual environment and install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download and prepare your dataset inside the `/dataset/` directory.

## 🧠 How to Run

Open the notebook in Jupyter or Colab:

```bash
jupyter notebook Date_classification_K_fold.ipynb
```

Or directly in Google Colab by uploading the `.ipynb` file.

## 📝 Requirements

- Python 3.8+
- PyTorch
- torchvision
- scikit-learn
- matplotlib
- numpy
- pandas

## 📊 Results

The model achieves high classification accuracy on different date varieties across multiple folds. Full training logs and metrics are available in the notebook.

## 📸 Dataset

> Note: The dataset is not included due to size limitations. You can use your own dataset of labeled date fruit images.

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

MIT License. See `LICENSE` for details.

---

**Made with ❤️ for Date Fruit AI Research**

# Date Fruit Classification with EfficientNet-B0.

This project is an AI-powered image classification model that identifies types of date fruits from images using **EfficientNet-B0**. Built in Python with PyTorch, the model is trained, evaluated, and served through a user-friendly Jupyter Notebook and an interactive **Gradio** demo.

Click here to try it out: **[Live Demo](https://bytixty1-date-fruit-image-classification.hf.space/)**

---

## 🚀 Features

* EfficientNet-B0-based CNN for high-accuracy image classification
* Automatic CSV generation of predictions
* Easy-to-use Jupyter Notebook interface
* Live **Gradio demo** — try the model without training!

---

## 📂 Dataset Structure

The dataset used in this project comes from Kaggle and is too large to be included directly in this repository. You can download it from the following link:

🔗 **[Date Fruit Image Dataset in Controlled Environment by Wadhasn Alhamdan](https://www.kaggle.com/datasets/wadhasnalhamdan/date-fruit-image-dataset-in-controlled-environment)**

> Huge thanks to **Wadhasn Alhamdan** for providing this high-quality and well-structured dataset.

Once downloaded, make sure your local folder is structured like this:

```
/dataset
├── train_labels.csv
├── images/
│   ├── img_001.jpg
│   ├── img_002.jpg
│   └── ...
```

---

## ⚙️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/date-fruit-classifier.git
cd date-fruit-classifier
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Notebook

Open the notebook and run all cells to train, validate, and generate predictions.

### 4. Or Skip Training and Try the Demo 😄

Use the pre-trained model via the Gradio interface to test real images directly.

---

## 📊 Output

* Model predictions are saved to a CSV file.
* Accuracy and loss graphs are generated during training.
* Demo UI displays image and predicted class in real time.

---

## 🔗 Live Demo

Click here to try it out: **\[Insert Demo Link]**

---

## 🧠 Tech Stack

* Python
* PyTorch
* EfficientNet (Torchvision / timm)
* Pandas / NumPy / Matplotlib
* Gradio
* Jupyter Notebook

---

## 👤 Author

**By Tixty1**

---

## 📄 License

This project is licensed under the MIT License.

---

Enjoy classifying dates like a pro! 🌴🥇

## 📘 Documentation

- [How to Run the Code (using pre-trained model)](./How_To_Run.md)

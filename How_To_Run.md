# 🛠️ How to Run the Date Fruit Classifier

This guide explains how to run the project **without training**, by using the pre-trained model provided in the `saved_model` folder.

---

## 📥 1. Download the Pre-trained Model

Download the `best_model1.pth` `best_date_classifier_model1.pth` file from the `saved_model/` folder in this repository:

🔗 **[Download best\_model.pth](saved_model/best_model1.pth)**
🔗 **[Download best\_best_date_classifier_model.pth](saved_model/best_date_classifier_model1.pth)**

Save this file in your project directory under:

```
saved_model/best_model.pth
```

> If the folder doesn’t exist, create it manually.

---

## ⚙️ 2. Install Requirements

Make sure to install all necessary dependencies:

```bash
pip install -r requirements.txt
```

---

## 🧪 3. Run the Gradio Demo

Use the demo code in `app.py` to launch the web UI:

```bash
python app.py
```

This will open a local Gradio interface in your browser where you can upload a date fruit image and get a prediction instantly — no training required!

---

## ✅ File Structure You Should Have

```
project-root/
├── saved_model/
│   └── best_model.pth
├── app.py
├── requirements.txt
└── README.md
```

---

Now you're ready to classify dates like a machine learning pro 🏆🌴

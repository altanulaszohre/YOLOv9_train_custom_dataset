# 😄 YOLOv9 - Emotion Detection with Custom Dataset

This project demonstrates how to train **YOLOv9** on a custom dataset for **facial emotion detection**. The trained model is capable of identifying faces in images and classifying them into 8 different emotional categories.

---

## 🧠 Objective

Evaluate the performance of the YOLOv9 architecture in real-time **emotion recognition** tasks based on facial expressions.

---

## 📦 Dataset

- **Name:** Facial Expression Image Data AFFECTNET (YOLO Format)
- **Link:** [AffectNet YOLO Format on Kaggle](https://www.kaggle.com/datasets/fatihkgg/affectnet-yolo-format)

This dataset contains labeled facial expressions in YOLO format, suitable for object detection training.

### Sample Data

![Sample Annotation](https://github.com/altanulaszohre/YOLOv9-train-custom-dataset/assets/111522957/5cbae123-55af-4651-8a24-31becf1cfdd5)

---

## 🚀 How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/YOLOv9_train_custom_dataset.git
   cd YOLOv9_train_custom_dataset
   ```

2. **Install requirements**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Download the dataset**:
   Download and extract the AFFECTNET YOLO-format dataset from Kaggle into the appropriate folder (e.g., `datasets/`).

4. **Run training notebook**:
   Open and run the notebook:
   ```bash
   jupyter notebook YOLOv9_train_and_test.ipynb
   ```

---

## 🛠️ Project Contents

```
YOLOv9_train_custom_dataset/
│
├── YOLOv9_train_and_test.ipynb    # Main notebook for training and evaluation
├── LICENSE
└── README.md
```

---

## 📄 License

This project is open-sourced under the MIT License.

---

## 🙌 Acknowledgments

- [YOLOv9](https://github.com/WongKinYiu/yolov9) developers
- [AffectNet Dataset](https://www.kaggle.com/datasets/fatihkgg/affectnet-yolo-format)


***Altan Ulaş Zöhre***

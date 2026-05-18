# 🛰️ Satellite Image Classification

A machine learning project that applies image processing techniques and classification models to satellite imagery. Built and documented as part of an image processing course/project, with an accompanying technical report.

---

## 📌 Overview

This project explores the use of computer vision and machine learning to classify satellite images into meaningful categories. The pipeline covers data preprocessing, model training, evaluation, and output storage — all implemented in Jupyter Notebooks.

---

## 📁 Repository Structure

```
Satellite_Image_Classification/
│
├── dataset/                     # Raw and preprocessed satellite image data
├── notebooks/                   # Jupyter Notebooks for EDA, training, and evaluation
├── modelOutput/                 # Saved trained model files and outputs
├── project/                     # Project configuration or deployment files
└── Image_Processing_Report.pdf  # Full technical report on the methodology
```

---

## 🧠 Methodology

The project follows a standard image classification pipeline:

1. **Data Collection** — Satellite images sourced from [TODO: dataset name, e.g. EuroSAT / UC Merced / Kaggle]
2. **Preprocessing** — Image resizing, normalization, and augmentation
3. **Model Training** — [TODO: model architecture, e.g. CNN / ResNet / EfficientNet] trained on labelled satellite images
4. **Evaluation** — Performance assessed using accuracy, confusion matrix, and other metrics
5. **Output** — Trained model saved to `modelOutput/`

---

## 🗂️ Image Classes

The model classifies satellite images into the following categories:

- [PermanentCrop]
- [AnnualCrop]



> Update this list with your actual class labels.

---

## 📊 Results

```markdown
| Preprocessing          | Accuracy | Precision | Recall | Specificity | F1 Score |
|------------------------|----------|-----------|--------|-------------|----------|
| None                   | 95.10%   | 97.00%    | 93.45% | 96.88%      | 95.20%   |
| Difference in Gaussian | 95.10%   | 96.60%    | 93.79% | 96.49%      | 95.18%   |
| Log Transform          | 94.00%   | 94.40%    | 93.65% | 94.35%      | 94.02%   |
| Sobel                  | 94.40%   | 97.20%    | 92.05% | 97.03%      | 94.56%   |
| Negative               | 93.50%   | 96.20%    | 91.27% | 95.98%      | 93.67%   |
```

---

## 🛠️ Tech Stack

- **Language:** Python
- **Environment:** Jupyter Notebook
- **Libraries:** [PyTorch, Keras, NumPy, Matplotlib, OpenCV]

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/spine-uwu/Satellite_Image_Classification.git
cd Satellite_Image_Classification
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

> If there's no `requirements.txt`, install manually:
> ```bash
> pip install tensorflow numpy matplotlib scikit-learn opencv-python jupyter
> ```

### 3. Run the notebooks

```bash
jupyter notebook
```

Open the notebooks inside the `notebooks/` folder and run them in order.

---

## 📄 Report

A detailed technical report covering the image processing methodology, model design decisions, and experimental results is available in the repository:

📎 [`Image_Processing_Report.pdf`](./Image_Preocessing_Report.pdf)

---

## 👥 Contributors

- [@spine-uwu](https://github.com/spine-uwu)
- (https://github.com/mimonT-T)

---

## 📜 License

This project is for academic/educational purposes.

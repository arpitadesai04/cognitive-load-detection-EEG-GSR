# cognitive-load-detection-EEG-GSR
Machine Learning-based cognitive load detection using EEG and GSR signals for classifying mental workload levels.

# Cognitive Load Detection Using EEG and GSR

## 📌 Project Overview

Cognitive Load Detection is a Machine Learning project that analyzes physiological signals to identify a person's level of mental workload.

The project uses **Electroencephalography (EEG)** and **Galvanic Skin Response (GSR)** signals to detect different levels of cognitive load.

The system processes the physiological data, extracts relevant features, applies Machine Learning algorithms, and classifies cognitive load into different levels such as:

* Low Cognitive Load
* Medium Cognitive Load
* High Cognitive Load

---

## 🎯 Problem Statement

To develop a Machine Learning-based system that can detect and classify cognitive load using EEG and GSR physiological signals.

---

## 💡 Objectives

* Analyze EEG and GSR physiological signals.
* Preprocess and clean the collected data.
* Extract relevant features from EEG and GSR signals.
* Identify patterns associated with different cognitive load levels.
* Train Machine Learning classification models.
* Evaluate model performance using appropriate evaluation metrics.
* Determine the effectiveness of combining EEG and GSR signals for cognitive load detection.

---

## 🧠 Technologies Used

### Programming Language

* Python

### Libraries

* NumPy
* Pandas
* SciPy
* Matplotlib
* Seaborn
* Scikit-learn

### Machine Learning

* Classification algorithms
* Feature extraction
* Model evaluation
* Confusion Matrix
* Accuracy
* Precision
* Recall
* F1-Score

### Signals

* EEG (Electroencephalography)
* GSR (Galvanic Skin Response)

---

## 📊 Dataset

The project uses physiological signal data containing EEG and GSR measurements along with cognitive load labels.

The dataset is not included in this repository because of dataset size/licensing or data-sharing restrictions.

Please refer to `data/README.md` for information about the dataset and how to obtain it.

---

## 🔄 Project Workflow

```text
EEG + GSR Data
       ↓
Data Preprocessing
       ↓
Data Cleaning
       ↓
Feature Extraction
       ↓
Feature Selection
       ↓
Train-Test Split
       ↓
Machine Learning Models
       ↓
Model Evaluation
       ↓
Cognitive Load Classification
```

---

## ⚙️ Methodology

### 1. Data Preprocessing

The raw physiological data is cleaned and prepared for Machine Learning.

Major preprocessing steps include:

* Handling missing values
* Removing unwanted data
* Data normalization/scaling
* Preparing cognitive load labels

### 2. Feature Extraction

Relevant features are extracted from EEG and GSR signals to represent changes associated with cognitive workload.

### 3. Model Training

Machine Learning classification models are trained using the extracted features.

The models can be compared based on their classification performance.

### 4. Model Evaluation

The trained models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---
## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/cognitive-load-detection-eeg-gsr.git
```

### 2. Navigate to the project

```bash
cd cognitive-load-detection-eeg-gsr
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the environment

Windows:

```bash
venv\Scripts\activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the notebook

```bash
jupyter notebook
```

Open:

```text
notebooks/cognitive_load_detection.ipynb
```

and run the cells.

---

## 🔮 Future Improvements

* Implement deep learning models for EEG signal analysis.
* Perform real-time cognitive load detection.
* Develop a web-based interface for predictions.
* Explore advanced EEG frequency-domain features.
* Improve classification using ensemble learning.
* Integrate real-time EEG and GSR sensors.
* Deploy the trained model as an API.

# 🧬 Medical Note Classifier: Clinical EHR Data NER & Phenotyping

![NLP](https://img.shields.io/badge/NLP-Named_Entity_Recognition-blue.svg)
![Model](https://img.shields.io/badge/Model-ClinicalBERT-orange.svg)
![Dataset](https://img.shields.io/badge/Dataset-MIMIC--III-green.svg)
![UI](https://img.shields.io/badge/UI-Modern_Dark_Mode-purple.svg)

## 📌 Project Overview
The **Medical Note Classifier** is an advanced Natural Language Processing (NLP) dashboard designed to extract critical medical information from unstructured Electronic Health Record (EHR) discharge summaries. Inspired by the MIMIC-III dataset and Vanderbilt clinical data standards, this tool leverages **ClinicalBERT** for Named Entity Recognition (NER) and Phenotype Classification.

This application allows medical professionals or researchers to input raw clinical notes and instantly receive structured, annotated, and classified medical data.

## 📸 Application Dashboard
![Medical Note Classifier UI](images/medical-note-classifier.png) *(Note: Upload your screenshot to an `images` folder in your repo and update this link!)*

## ✨ Key Features
* **Named Entity Recognition (NER):** Automatically extracts and highlights four key entity types:
  * 🔴 Symptoms
  * 🔵 Diagnoses
  * 🟢 Medications
  * 🟠 Procedures
* **Phenotype Classification:** Predicts the probability of the note belonging to specific medical specialties (e.g., Cardiology, Neurology, Endocrinology, Pulmonology, Oncology, Nephrology).
* **Real-time Metrics Tracking:** Calculates and displays real-time model evaluation metrics including NER Precision, F1 Score, and total Entities/Phenotypes detected.
* **Modern UI:** A sleek, responsive, dark-mode dashboard tailored for clinical data visualization.

## 🛠️ Technologies Used
* **NLP & Machine Learning:** [Transformers (Hugging Face), ClinicalBERT, spaCy - *update as needed*]
* **Dataset/Inspiration:** MIMIC-III Clinical Database
* **Frontend:** [HTML5, CSS3, JavaScript / React / Streamlit - *update based on your stack*]
* **Backend:** [Python, Flask / FastAPI - *update based on your stack*]


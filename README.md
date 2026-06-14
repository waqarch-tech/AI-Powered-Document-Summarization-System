# AI-Powered-Document-Summarization-System
AI-Powered-Document-Summarization-System
# AI-Powered Document Summarization System

## 📌 Project Overview
This project was developed as part of the **Teyzix Core Internship (June Batch)** for the Artificial Intelligence / NLP domain. The objective is to build an automated system that compresses long text documents into concise, meaningful summaries while preserving core insights and key information.

* **Task ID:** AI-INT-1
* **Difficulty Level:** Intermediate
* **Assigned Date:** 11 June 2026
* **Submission Date:** 19 June 2026

---

## 🚀 Features & Modules

### 1. Data Input System
* Supports direct user text input.
* Supports document uploads via `.txt` [and `.pdf` if implemented].

### 2. Text Preprocessing
* Full pipeline utilizing [NLTK / spaCy] for lowercasing, tokenization, stopword removal, and sentence segmentation.

### 3. Summarization Logic
* Built using **Extractive Summarization** techniques based on [mention your method, e.g., Frequency-based scoring / TF-IDF / Sentence ranking].
* Features adjustable summary length parameters.

### 4. Analytics Module
* Generates word frequency analysis metrics.
* Extracts top key phrases and visualizes sentence importance scores.

### 5. File Handling & Output
* Displays side-by-side comparison of original vs. summarized text.
* Exports final generated summaries to `.txt` [or `.pdf`] formats.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python 3
* **NLP Libraries:** [NLTK or spaCy]
* **Environment:** Google Colab / Local IDE
* **Additional Libraries:** [e.g., Pandas, NumPy, Matplotlib for analytics]

---

## 📂 Repository Structure
```text
├── sample_documents/      # Test documents (.txt, .pdf)
├── generated_summaries/   # Output summaries exported by the system
├── screenshots/           # Execution and analytics screenshots
├── summarizer.ipynb       # Main Google Colab / Jupyter Notebook
└── README.md              # Project documentation

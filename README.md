# Symptoms Based Disease Prediction and Recommendation System Using NLP

## 🩺 Project Overview

This repository hosts the code and documentation for a **Symptoms Based Disease Prediction and Recommendation System**. The core goal of this project is to bridge the gap between human language and clinical diagnosis by allowing users to describe their health issues naturally, similar to how they would talk to a doctor.

The system utilizes advanced Natural Language Processing (NLP) techniques to understand conversational symptom descriptions and provide accurate disease predictions along with personalized health recommendations.

---

## 💡 Motivation and Problem Statement

Many existing health systems require precise, medical keyword-based inputs, which is impractical for the average person. Our project addresses this by tackling the following problem:

> **Problem Statement:** Build an AI assistant that predicts diseases from user-provided **natural language health queries** by accurately extracting symptoms and mapping them to probable medical conditions.

The system aims to make initial health assessment more accessible and user-friendly, providing preliminary guidance before a medical consultation.

---

## 🎬 Project Demonstration 

**Witness the system in action!**

A full demonstration video showcasing the project workflow, natural language input processing, disease prediction, and personalized recommendation generation is available at the link below:

### [**Watch Project Demo Video**](https://drive.google.com/file/d/1kIUOy8vM-o_VyCbFO8rtx9bi-Og0izzI/view?usp=drive_link)

---

## ⚙️ Core Architecture and Methodology

The system is built on a multi-stage pipeline, leveraging both traditional Machine Learning (ML) and modern LLM architectures for robust performance:

### 1. Natural Language Processing (NLP)

* **Medical Concept Normalization (MCN):** Creation of a **Symptom Dictionary** to map diverse, everyday symptom expressions (e.g., "stomach ache," "tummy hurts") to standardized medical terms, ensuring input consistency.

* **Symptom Extraction and Matching:** Utilizing NLP techniques to isolate and normalize symptoms from the user's raw query.

### 2. Disease Prediction

The project explores and utilizes several models for high-accuracy prediction:

* **ML Models:** SVC (Support Vector Classifier) and Random Forest, achieving high accuracy in initial benchmarks.

* **Deep Learning:** MCN-BERT and BiLSTM models.

### 3. Recommendation System

Beyond prediction, the system provides personalized, holistic advice, ensuring practical utility:

* **Personalized Advice:** Generated recommendations for **medication, diet, and exercise** based on the predicted condition.

* **Critical Precautions:** Providing necessary specific precautions (e.g., "Chew or swallow aspirin," "Call emergency services") when critical symptoms are identified.

* **Model Explainability:** Utilizing techniques like **SHAP (SHapley Additive exPlanations) and LIME (Local Interpretable Model-agnostic Explanations)** to ensure transparency and explain *why* a particular prediction was made.

## 📊 Datasets Used

| Dataset Name | Size | Key Details | Primary Use Case |
| :--- | :--- | :--- | :--- |
| **Medical Dataset-1** | 4,920 instances | 132 symptoms, 41 unique diseases. Includes history and diagnostic features. | Disease Prediction & Recommendation Generation. |
| **Symptom2Disease** | 1,200 instances | Symptom descriptions across 24 disease classes (from Kaggle). | Fine-Tuning Open-Source LLMs (LLaMA 3, Mistral-7B). |

## 🚀 Future Scope

The project has a clear path for expansion and improvement:

* **Expanded Coverage:** Significantly expand the symptom and disease coverage (currently using 132 symptoms and 41 diseases) for broader and more accurate predictions.

* **Symptom Dictionary Standardization:** Further refinement and development of the standardized symptom dictionary.

* **LLM Benchmarking:** Continuous fine-tuning and benchmarking of newer, state-of-the-art open-source LLMs to maintain performance superiority.

## 🛠️ Installation and Setup

To run this project locally, follow these steps:

1.  **Clone the repository:**

    ```bash
    git clone [https://github.com/sayyedsabirali/Minor-Project.git](https://github.com/sayyedsabirali/Minor-Project.git)
    cd Minor-Project
    ```

2.  **Create a virtual environment (Recommended):**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Linux/macOS
    # .\venv\Scripts\activate  # On Windows
    ```

3.  **Install dependencies:**
    *(Note: Add your specific requirements file path here. Assuming `requirements.txt`.)*

    ```bash
    pip install -r requirements.txt
    ```

4.  **Run the main application:**

    ```bash
    # Replace with the actual command to run your prediction engine/app
    python main_app.py
    ```

## 👨‍💻 Contributors

This project was a collaborative effort.

| Name | Faculty No. |
| :--- | :--- |
| **Sayyed Sabir Ali** | 22AIB320 |
| **Mohd Fazil** | 22AIB261 |

### Guidance

* **Supervisor:** Ms. Ayesha Khan

* **Institution:** ZHCET AMU, Aligarh

## 📄 License

*(Add license information here, e.g., MIT, Apache 2.0, or None if not specified.)*

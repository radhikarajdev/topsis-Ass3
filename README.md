
# Text Generation Model Evaluation using TOPSIS

This project applies the **TOPSIS (Technique for Order Preference by Similarity to Ideal Solution)** method to evaluate and select the best **pre-trained text generation models** from the **Hugging Face library** based on multiple performance metrics.

---

## 🚀 Project Overview

The goal is to determine the most suitable NLP model for **Text Generation** tasks using quantitative and qualitative evaluation metrics.

---

## ⚙️ Technologies Used
- **Python**
- **Hugging Face Transformers**
- **Pandas & NumPy**
- **Matplotlib & Seaborn**
- **Scikit-learn (for normalization)**

---

## 📦 Dataset
A sample text dataset was used to evaluate the models, focusing on generating coherent, relevant, and diverse outputs.

---

## 🚀 **Models Compared**
- **GPT-2** (`gpt2`)
- **GPT-Neo (125M)** (`EleutherAI/gpt-neo-125M`)
- **DistilGPT-2** (`distilgpt2`)

---

## 📊 **Evaluation Metrics**
The following metrics are calculated for each model:
1. **Output Length:** Total number of words generated. *(Higher is better)*
2. **Repetition Rate:** Measures redundancy in generated text. *(Lower is better)*
3. **Generation Time (s):** Time taken to generate output. *(Lower is better)*

---

## ⚖️ **TOPSIS Methodology**
TOPSIS ranks models based on their closeness to the ideal solution.  
- **Weights Assigned:**
  - **Output Length:** 0.4
  - **Repetition Rate:** 0.3
  - **Generation Time:** 0.3  
- **Ideal Best:** High output length, low repetition, low generation time.  
- **Ideal Worst:** Low output length, high repetition, high generation time.

---

---

## 📈 Results

The results are summarized in the `topsis_results.csv` file.
- **TOPSIS Score:** Indicates model performance relative to the ideal model.
- **Rank:** Final ranking based on TOPSIS analysis.

---

## 📊 Result

<img width="994" alt="Screenshot 2025-02-02 at 9 28 12 PM" src="https://github.com/user-attachments/assets/1d20cee3-bc02-47a0-80eb-1ca2d0777586" />


---

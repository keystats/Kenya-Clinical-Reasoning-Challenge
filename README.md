
# 🌍 Kenya Clinical Reasoning Challenge 🩺

[![Zindi](https://img.shields.io/badge/Zindi-Challenge-orange)](https://zindi.africa/competitions/kenya-clinical-reasoning-challenge)
[![Leaderboard](https://zindi.africa/competitions/kenya-clinical-reasoning-challenge/leaderboard)
[![Python](https://img.shields.io/badge/Python-3.x-blue)](https://www.python.org/)


---

## 📜 Overview
This project was developed for the **[Kenya Clinical Reasoning Challenge](https://zindi.africa/competitions/kenya-clinical-reasoning-challenge)** hosted on Zindi.  
The goal was to **predict clinician responses** to medical prompts — pushing the boundaries of AI-assisted healthcare reasoning.

The project aimed to surpass baseline LLMs such as **GPT-4.0, LLAMA, and GEMINI** using a **ROUGE score** evaluation.

---

## 🎯 Objective
> Build a text-to-text generation model capable of reasoning like a clinician — and aim for **0.50+** ROUGE score.

---

## 🛠️ Approach
### **Step 1 — Data Exploration**
🔍 Investigated dataset structure, prompts, and clinician answers.

### **Step 2 — Preprocessing**
🧹 Cleaned and tokenized text, handled missing values, created paired training data.

### **Step 3 — Model Selection**
⚙️ Chose a **Transformer-based model** optimized for clinical reasoning tasks.

### **Step 4 — Training**
💻 Trained on GPU with tuned hyperparameters to prevent overfitting.

### **Step 5 — Evaluation**
📊 Measured **ROUGE scores** on public and private leaderboards.

### **Step 6 — Submission**
📂 Prepared predictions in Zindi’s required format.

---

## 📈 Results
🏆 **Public Score:** `0.395355497`  
🏆 **Private Score:** `0.414785791`  
🥇 **Leaderboard Position:** **Top 45**  

These results positioned the solution among the best-performing entries.

---

## ⚠️ Weaknesses
- 📉 Limited training data reduced adaptability to rare reasoning cases.
- 🤔 Some answers lacked **context-specific depth**.
- 📝 Long prompts sometimes produced **truncated responses**.

---

## 🚀 Future Improvements
To achieve **0.5+**, here’s what’s next:
1. 📚 Add **medical domain knowledge bases**.
2. 🤖 Fine-tune **larger transformer architectures**.
3. 🎯 Use **prompt-engineering** for better context retention.
4. 📊 Data augmentation for underrepresented categories.
5. 🧩 Ensemble multiple architectures for robustness.

---

## 👨‍💻 Author
**Jackson Kahungu**  

📅 _Project Year: 2025_

---
⚠ **Disclaimer**: For educational & research purposes only. Not for clinical decision-making.

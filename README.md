# 🎬 IMDb Movie Review Sentiment Analysis using BERT

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?logo=python">
  <img src="https://img.shields.io/badge/Transformers-HuggingFace-yellow?logo=huggingface">
  <img src="https://img.shields.io/badge/PyTorch-Deep%20Learning-red?logo=pytorch">
  <img src="https://img.shields.io/badge/Gradio-Web%20App-orange?logo=gradio">
  <img src="https://img.shields.io/badge/Status-Completed-success">
  <img src="https://img.shields.io/badge/License-MIT-green">
</p>

## 📌 Project Overview

This project is a **Natural Language Processing (NLP)** application that classifies IMDb movie reviews as **Positive** or **Negative** using **BERT (Bidirectional Encoder Representations from Transformers)**.

The model is fine-tuned on the IMDb Movie Review dataset and deployed with an interactive **Gradio** interface for real-time sentiment prediction.

---

## 🚀 Demo

### 🎥 Project Preview

> Add your project screenshot or GIF here.

```
📂 assets/
   └── sentiment-demo.gif
```

Example:

```markdown
![Project Demo](assets/sentiment-demo.gif)
```

---

## ✨ Features

- ✅ Movie Review Sentiment Classification
- ✅ Fine-tuned BERT Model
- ✅ Real-time Prediction
- ✅ Interactive Gradio Interface
- ✅ Hugging Face Transformers
- ✅ PyTorch Deep Learning
- ✅ User-friendly UI
- ✅ Fast and Accurate Predictions

---

# 📊 Problem Statement

Understanding customer opinions from large volumes of text is challenging.

This project automates sentiment detection by predicting whether a movie review expresses a **Positive** or **Negative** sentiment.

---

# 🧠 Model Architecture

```
IMDb Review
      │
      ▼
Tokenizer
(HuggingFace)

      │
      ▼

BERT Model

      │
      ▼

Dense Layer

      │
      ▼

Prediction

Positive 😊
or
Negative 😔
```

---

# 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| Python | Programming Language |
| BERT | NLP Model |
| Transformers | Pretrained Models |
| Hugging Face | Tokenizer & Model |
| PyTorch | Deep Learning |
| Scikit-learn | Evaluation Metrics |
| Pandas | Data Handling |
| NumPy | Numerical Operations |
| Matplotlib | Visualization |
| Gradio | Deployment |

---

# 📁 Project Structure

```
IMDb-Sentiment-Analysis/
│
├── dataset/
│
├── models/
│
├── notebook/
│   └── IMDb_Sentiment_Analysis.ipynb
│
├── app.py
│
├── requirements.txt
│
├── README.md
│
└── assets/
    ├── dashboard.png
    └── sentiment-demo.gif
```

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/imdb-sentiment-analysis.git
```

Go inside project

```bash
cd imdb-sentiment-analysis
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
python app.py
```

or

```bash
gradio app.py
```

---

# 📈 Workflow

```
IMDb Dataset

      │

      ▼

Data Cleaning

      │

      ▼

Tokenization

      │

      ▼

BERT Fine-tuning

      │

      ▼

Model Evaluation

      │

      ▼

Gradio Deployment
```

---

# 📊 Evaluation Metrics

The model can be evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

# 💻 Example Prediction

**Input**

```
This movie is absolutely amazing.
The acting and storyline were fantastic.
```

**Prediction**

```
Positive 😊
```

---

**Input**

```
Worst movie ever.
Waste of time.
```

**Prediction**

```
Negative 😔
```

---

# 📚 Libraries Used

```python
transformers
torch
gradio
numpy
pandas
matplotlib
scikit-learn
```

---

# 🎯 Future Improvements

- Multi-class Sentiment Analysis
- Emotion Detection
- Model Deployment on Hugging Face Spaces
- Docker Support
- Streamlit Dashboard
- REST API using FastAPI

---

# 👨‍💻 Author

**Ashish Kumar**

📧 Email: hardeshgangwar6398@gmail.com

💼 Aspiring Data Analyst | Data Scientist | Machine Learning Enthusiast

---

# ⭐ If you like this project

Give this repository a ⭐ on GitHub and connect with me on LinkedIn.

---

## 📜 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgements

- IMDb Dataset
- Hugging Face Transformers
- PyTorch
- Gradio
- Open Source Community

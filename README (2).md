
# 📰 Fake News Generator & Detector using Generative AI and NLP

This project combines **Natural Language Processing (NLP)** and **Generative AI** to both **generate** and **detect fake news articles**. It leverages modern transformer-based models like **DeBERTa** for classification and language models for content generation.

---

## 🔍 Features

- ✅ **Fake News Detection** using fine-tuned **DeBERTa** transformer
- ✍️ **Fake News Generation** using text generation models (e.g., GPT-style)
- 📊 Real-time prediction with interactive UI
- 📂 Trained on real-world datasets (e.g., LIAR, Kaggle Fake News Dataset)
- 📈 Data preprocessing and EDA (Exploratory Data Analysis) included

---

## 🧠 Technologies Used

- Python 🐍
- Transformers (HuggingFace) 🤗
- DeBERTa (for fake news detection)
- Streamlit or Flask (for web UI)
- Pandas, NumPy, Matplotlib, Seaborn
- Sklearn (for preprocessing and evaluation)
- Torch (for deep learning training)
- OpenAI API / GPT-2 (optional: fake news generation)

---

## 📁 Project Structure

```
├── FakeNews_Generator_And_Detector.ipynb
├── requirements.txt
├── app.py (if web app is used)
├── model/
│   ├── fine_tuned_deberta_model/
│   └── tokenizer/
├── data/
│   └── fake_news_dataset.csv
├── README.md
```

---

## ⚙️ Installation

1. Clone the repository:
```bash
git clone https://github.com/rishabhsingh/FakeNews-Generator-Detector.git
cd FakeNews-Generator-Detector
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

---

## 🚀 Usage

### 🧪 Jupyter Notebook
Run the notebook step-by-step:
```bash
jupyter notebook FakeNews_Generator_And_Detector.ipynb
```

### 🌐 Web App (Optional)
If you have a Streamlit or Flask frontend:
```bash
streamlit run app.py
```

---

## 📊 Dataset

- [LIAR Dataset](https://www.cs.ucsb.edu/~william/data/liar_dataset.zip)
- [Kaggle Fake News Dataset](https://www.kaggle.com/c/fake-news/data)

Make sure your dataset includes:
- `text`
- `label` (0 = Real, 1 = Fake)

---

## 🔬 Model Training & Evaluation

- Preprocessing: Tokenization, stopword removal
- Vectorization: TF-IDF / Transformers
- Model: Fine-tuned DeBERTa on news text
- Evaluation: Accuracy, Precision, Recall, F1-score

---

## 📈 Example Results

| Model      | Accuracy | F1 Score |
|------------|----------|----------|
| DeBERTa    | 95.2%    | 0.94     |
| Logistic Regression | 88.6% | 0.87 |

---

## 🧠 Future Improvements

- Multi-language support
- GPT-4 generated fake news training data
- Advanced interpretability (SHAP / LIME)
- Browser-based interface

---

## 🙌 Acknowledgements

- HuggingFace Transformers
- OpenAI API (for generation)
- Kaggle & LIAR Dataset

---

## 👤 Author

**Rishabh Singh**  
GitHub: [rishabhsingh](https://github.com/rishabhsingh)

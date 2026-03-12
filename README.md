# Bart-Text-Summarizer
# 🧠 AI Text Summarizer (BART + Streamlit)

A deep learning based **Abstractive Text Summarization web application** built using **Hugging Face Transformers, PyTorch, and Streamlit**.
The application uses the **BART (Bidirectional and Auto-Regressive Transformer)** model to generate concise summaries from long text inputs.

This project demonstrates practical implementation of **Natural Language Processing (NLP)** and **Transformer models** for real-world text summarization tasks.

---

## 🚀 Features

* Summarizes long articles and paragraphs into short summaries
* Built using **BART Transformer model**
* Interactive **Streamlit web interface**
* Fast and efficient inference using **Hugging Face Transformers**
* Clean and simple UI for easy text input and output

---

## 🧠 Model Used

This project uses the pretrained model:

**facebook/bart-large-cnn**

BART combines the strengths of:

* **Bidirectional Encoder (BERT style)**
* **Autoregressive Decoder (GPT style)**

This architecture makes it highly effective for **abstractive text summarization** tasks.

---

## 🏗️ Project Structure

```
text-summarizer/
│
├── bart_summarizer/
│   ├── config.json
│   ├── tokenizer files
│   ├── model files
│
├── app.py                # Streamlit web application
├── model.py              # Model loading and summarization logic
├── requirements.txt      # Python dependencies
└── README.md
```

---

## ⚙️ Technologies Used

* **Python**
* **PyTorch**
* **Hugging Face Transformers**
* **Streamlit**
* **Natural Language Processing (NLP)**

---

## 📦 Installation

Clone the repository:

```
git clone https://github.com/Avisweta-De/text-summarizer.git
cd text-summarizer
```

Install required packages:

```
pip install -r requirements.txt
```

---

## ▶️ Run the Application

Start the Streamlit app:

```
streamlit run app.py
```

After running, open in your browser:

```
http://localhost:8501
```

---

## 💡 How It Works

1. User enters a long piece of text in the input box.
2. The text is tokenized using the **BART tokenizer**.
3. The transformer model processes the text.
4. The model generates a **short abstractive summary**.
5. The summary is displayed in the **Streamlit web interface**.

---

## 📊 Example

**Input**

Artificial Intelligence is transforming industries by automating processes, improving decision-making, and enabling new technological innovations.

**Output Summary**

AI is transforming industries through automation, improved decision-making, and technological innovation.

---

## 📈 Future Improvements

* Add **PDF and document summarization**
* Add **multi-language support**
* Deploy on **Streamlit Cloud / Hugging Face Spaces**
* Improve model performance using **fine-tuning**

---

## 👩‍💻 Author

**Avisweta De**

🎓 MSc Data Science
🏫 Indian Institute of Information Technology Lucknow (IIITL)

💡 Interests:

* Machine Learning
* Natural Language Processing
* Deep Learning
* AI Applications

🔗 GitHub: https://github.com/Avisweta-De


---

⭐ If you found this project useful, consider giving it a **star on GitHub**.

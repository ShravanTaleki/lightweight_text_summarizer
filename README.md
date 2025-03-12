# 📄 Text Summarization for PDA or Lightweight Devices  

## 🔍 Overview  
The **Text Summarization for PDA or Lightweight Devices** project is a lightweight and efficient text summarization application. It provides extractive summarization using Sentence Transformers and LexRank, offering fast performance without relying on heavy deep learning models.  

## 🚀 Features  
- 🎨 **Streamlit Frontend** – User-friendly interface for text summarization.  
- ⚡ **Efficient Summarization** – Uses Sentence Transformers and LexRank for quick and meaningful summaries.  
- 🔍 **Minimal Resource Usage** – No dependency on large neural network models.  

## 🛠️ Tech Stack  
- **Frontend**: Streamlit  
- **Summarization Engine**: Sentence Transformers, LexRank  
- **Version Control**: Git & GitHub  

## 📌 Installation  

### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/yourusername/text-summarization-pda.git
cd text-summarization-pda
```

### 2️⃣ Set Up Virtual Environment (Optional but Recommended)  
```sh
python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows
```

### 3️⃣ Install Dependencies  
```sh
pip install -r requirements.txt
```

### 4️⃣ Run the Streamlit Application  
```sh
streamlit run app.py
```

## 📖 Usage  
1️⃣ Enter or upload text data.  
2️⃣ The summarization engine extracts the key sentences.  
3️⃣ View the generated summary in an interactive UI.  

## 📂 Folder Structure  
```
text-summarization-pda/
│── app.py          # 🎨 Streamlit Frontend
│── requirements.txt # 📦 Python dependencies
│── README.md       # 📜 Project Documentation
│── LICENSE         # ⚖️ License file
```

## 🔮 Future Improvements  
- 🧠 Add support for abstractive summarization.  
- ⏳ Optimize processing for larger text inputs.  
- 🌐 Deploy as a lightweight API for integration with other applications.  

---

📜 This project is licensed under the **Apache 2.0 License**.

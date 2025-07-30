# 🎓 AI Chatbot for College Information Retrieval

This project is a **custom AI-powered chatbot** built with LangChain and HuggingFace models, designed to answer queries about various engineering colleges by processing and storing their information using vector embeddings.

---

## 🚀 Features

- ✅ **Conversational AI** using HuggingFace language models  
- ✅ **Vector store (ChromaDB)** to embed and query structured college data  
- ✅ **Web scraping support** (via `web_crawler.py`) to gather external college info  
- ✅ **Environment-variable-based API token management**  
- ✅ **.env protected for secure deployment**  
- ✅ **Notebook (`demo.ipynb`) for interactive experimentation**  

---

## 🔧 Tech Stack

- Python  
- LangChain  
- HuggingFace (Flan-T5 model)  
- Sentence Transformers (`all-mpnet-base-v2`)  
- ChromaDB  
- Dotenv  

---
## ⚙️ Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/saihajkaur006/Chatbot.git
   cd Chatbot
   ```
2. **Create & Activate Virtual Environment**
   ```bash
    python -m venv venv
    # Windows
    venv\Scripts\activate
    # Mac/Linux
    source venv/bin/activate
   ```
3. **Install Requirements**
   ```bash
     pip install -r requirements.txt
   ```
4. **Add your HuggingFace API token in .env**
   ```bash
    HUGGINGFACEHUB_API_TOKEN=your_token_here
   ```
5. **Run the Notebook**
   Open demo.ipynb and start interacting with the college chatbot.

---
## 🔮 Future Enhancements
- 💬 Add frontend with Streamlit or Gradio

- 🔍 Live search for real-time college websites

- 🔁 Fallback to OpenAI/Gemini when HuggingFace limits exceed

- 🎤 Voice input and speech output

- 📊 Visual analytics: charts for fee, hostel, course data, etc.

---
## 📌 Project Status
- ✅ Backend working (LLM + Vector Store + Query Chain)
- 🚧 Interface + Advanced integrations in development
---
## 📄 License
This project is for educational and demo purposes. Usage of external APIs should follow respective providers’ terms (e.g., HuggingFace).
---
## 👤 Author
-Saihajpreet Kaur
-Github:saihajkaur006

# 🏥 Medical ChatBot AI  

## 📌 Project Overview  

The **Medical ChatBot AI** is a PDF-based conversational assistant designed to answer medical questions directly from uploaded documents.  
It uses **Natural Language Processing (NLP)** and **Machine Learning models** to extract information from medical texts and provide concise, relevant answers.  

With a simple **Gradio-powered interface**, users can upload a medical PDF (such as the *Gale Encyclopedia of Medicine*) and interact with it in real-time by asking natural language questions.  

⚠️ *This chatbot is meant for **educational and informational purposes only** and should not be considered a substitute for professional medical advice.*  

---

---

## 🚀 Features  
- 💬 **Interactive Chatbot** – Built with Gradio for an easy-to-use interface.  
- 🏥 **Medical Query Support** – Provides AI-based responses to health-related questions.  
- 📄 **PDF-based Knowledge** – Can be extended to answer from uploaded medical documents.  
- ⚡ **Real-time Processing** – Generates answers instantly.  
- 🌐 **Cross-platform** – Runs locally on your machine or can be deployed online (Hugging Face Spaces, Streamlit Cloud, or Docker).  
- 🔒 **Customizable** – Easily switch to different models or datasets.  
- 🧠 **Extendable** – Future-ready for integration with advanced LLMs (BioBERT, PubMedBERT).  

---

## 🛠️ Technologies Used  
- **Python 3.x** – Core programming language.  
- **Gradio** – For building the chatbot’s web-based user interface.  
- **Transformers (Hugging Face)** – For natural language understanding and generation.  
- **Sentence Transformers** – For generating vector embeddings (if using PDF-based RAG).  
- **FAISS** – Vector database for fast similarity search (optional, when PDFs are used).  
- **PyPDF** – Extracting text content from PDF files.  
- **LangChain** – For RetrievalQA and chaining model responses (optional if you used it).  

---

## 📋 Installation  

```bash
# Clone this repository
git clone https://github.com/your-username/Medical-ChatBot-AI.git
cd Medical-ChatBot-AI

# Install dependencies
pip install gradio
```

## 📸 Demo  

Below is a screenshot of the **Medical Chatbot (PDF-based)** interface.  


🔹 The interface consists of:  
- **Query Box (Left):** Enter your medical question.  
- **Output Box (Right):** The chatbot displays the generated answer.  
- **Buttons:**  
  - *Clear* → Reset the input and output fields.  
  - *Submit* → Send your query to the chatbot.  
  - *Flag* → Mark incorrect or irrelevant responses.  

⚠️ *Note: This chatbot provides answers based on the uploaded medical PDF. It is not a substitute for professional medical advice.*

<img width="2939" height="1653" alt="image" src="https://github.com/user-attachments/assets/b2137f04-1f59-468d-93e5-f885c62d52d7" />


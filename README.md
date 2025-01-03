# 🤖 Chat with PDF locally using Ollama + LangChain + Large Language Model

A powerful local RAG (Retrieval Augmented Generation) application that lets you chat with your PDF documents using Ollama and LangChain. This project includes a Jupyter notebook for experimentation.

## ✨ Features

- 🔒 Fully local processing - no data leaves your machine
- 📄 PDF processing with intelligent chunking
- 🧠 Multi-query retrieval for better context understanding
- 🎯 Advanced RAG implementation using LangChain
- 📓 Jupyter notebook for experimentation

## 🚀 Getting Started

### Prerequisites

1. **Install Ollama**
   - Visit [Ollama's website](https://ollama.ai) to download and install
   - Pull required models:
     ```bash
     ollama pull llama2  # ollama pull llama3.2 or your preffered model
     ollama pull nomic-embed-text
     ```

2. **Clone Repository**
   ```bash
   git clone https://github.com/nanditasingh12/Ollama-Insight-PDF-Reader.git
   cd Ollama-Insight-PDF-Reader.git
   ```

3. **Set Up Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: .\venv\Scripts\activate #(Activate your environment)
   pip install -r requirements.txt
   ```

### 🎮 Running the Application

#### 1: Jupyter Notebook
```bash
jupyter notebook
```
Open `updated_rag_notebook.ipynb` to experiment with the code
For my case this is the output I got: ![image](https://github.com/user-attachments/assets/53ff6b12-e883-4c71-b053-687d94f508d4)


## 💡 Usage Tips

1. **Upload PDF**: Use the file uploader in the Streamlit interface or try the sample PDF
2. **Select Model**: Choose from your locally available Ollama models
3. **Ask Questions**: Start chatting with your PDF through the chat interface
4. **Adjust Display**: Use the zoom slider to adjust PDF visibility
5. **Clean Up**: Use the "Delete Collection" button when switching documents

## 🤝 Contributing

Feel free to:
- Open issues for bugs or suggestions
- Submit pull requests
- Comment on the YouTube video for questions
- Star the repository if you find it useful!

## ⚠️ Troubleshooting

- Ensure Ollama is running in the background
- Check that required models are downloaded
- Verify Python environment is activated

### Common Errors

#### ONNX DLL Error
If you encounter this error:
```
DLL load failed while importing onnx_copy2py_export: a dynamic link Library (DLL) initialization routine failed.
```



# LangChain-Ollama-Streamlit-Chatbot

### A Streamlit-powered chatbot application using LangChain and Ollama for local LLM inference.

<img width="1133" height="481" alt="Screenshot 2025-09-04 212802" src="https://github.com/user-attachments/assets/6d888f3d-2fbd-4a0f-90a2-53a17a1e08e2" />

## ✨ Overview
   A conversational AI chatbot engine built with LangChain, Ollama (LLAMA2 models), and Streamlit. This project lets users chat with powerful local language models via a friendly web interface.

## 🌟 Features
✅ Powered by local LLMs using Ollama (LLAMA2) 
✅ Streamlit web UI for chat experience
✅ Modular LangChain pipeline for prompt customization
✅ Dynamically updates knowledge of the current date/year for accurate answers
✅ Easy extensibility to new models or prompt formats

## Setup Instructions

### 1. Prerequisites

- Python 3.9+
- Ollama installed locally: [Ollama Installation Guide](https://ollama.com)
- LangChain, Streamlit, and langchain-ollama modules


### 2. Installation

- Clone this repo:
- Install dependencies: pip install -r requirements.txt

**Sample `requirements.txt`:**
streamlit
langchain
langchain-ollama
ollama


### 3. Ollama Setup

- Start the Ollama server: ollama serve
- Download your preferred model (e.g. llama2 ): ollama pull llama2


### 4. Run The Chatbot

Start Streamlit: streamlit run localama.py

Open [http://localhost:8501](http://localhost:8501) in your browser.

## Usage

- Enter prompts in the chat UI.
- The assistant can answer questions using the selected Ollama model.
- "Current year" is dynamically injected using Python’s `datetime`, ensuring always up-to-date responses.

## Customization

- Change default models or prompts in `localama.py` or your project’s main Python file.
- To update system prompts or add more context, edit the initialization section using Python’s `datetime.datetime.now()` for dynamic facts.

## Contributing

Pull requests and suggestions are welcome!
- Fork the repo, create a feature branch, and open a PR.
- Make sure new contributions include relevant documentation and tests if applicable.

## License

This project is MIT licensed.

---

**Quick Links**  
- Ollama documentation: [https://ollama.com](https://ollama.com)  
- LangChain Python docs: [https://python.langchain.com/](https://python.langchain.com/)  
- Streamlit: [https://streamlit.io/](https://streamlit.io/)  



       
















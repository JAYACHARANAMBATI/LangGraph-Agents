

# 🚀 LangGraph-Agents-Gemini-Ollama  
**A collection of cutting-edge conversational AI agents** powered by [LangGraph](https://github.com/langchain-ai/langgraph), featuring **Google Gemini** and **Ollama** LLMs, with seamless tool integrations like Wikipedia and search.  

![AI Agents](https://img.shields.io/badge/AI-Agents-blueviolet) 
![LangGraph](https://img.shields.io/badge/Built%20with-LangGraph-ff69b4) 
![Gemini](https://img.shields.io/badge/Google-Gemini-yellow) 
![Ollama](https://img.shields.io/badge/Ollama-Llama%203.1-orange)  

---

## 📦 Contents  

### 1. **`OllamaChatGraph.py`**  
*A simple yet powerful command-line chatbot powered by Ollama (Llama 3.1) and LangGraph.*  

#### ✨ **Features:**  
- 🖥️ **Command-line chatbot** for interactive conversations  
- ⚡ **Ollama LLM** (Llama 3.1) for fast, local responses  
- 🔄 **Graph-based conversation flow** for dynamic interactions  

#### 🛠️ **Usage:**  
1. **Ensure Ollama is running** locally with the `llama3.1` model.  
2. Run:  
   ```sh
   python OllamaChatGraph.py
   ```  
3. Start chatting! Type `quit`, `exit`, or `q` to stop.  

---

### 2. **`langgraph_agents.ipynb`**  
*A Jupyter Notebook showcasing **Wikipedia-integrated agents** with LangGraph and Ollama.*  

#### ✨ **Features:**  
- 🔍 **Wikipedia search integration** for fact-based responses  
- 🤖 **Multi-model support** (LLM + Ollama chat models)  
- 📝 **Step-by-step guide** for building agents with tools & prompts  

#### � **Usage:**  
1. Open in **Jupyter** or **VS Code**.  
2. Run cells to see **Wikipedia queries** and **agent responses** in action.  

---

### 3. **`langgraph_tools_Bindings_agents.ipynb`**  
*A Jupyter Notebook for **Google Gemini-powered agents** with advanced tool bindings.*  

#### 🔥 **Features:**  
- 🌐 **Google Gemini** (via `langchain_google_genai`)  
- 🛠️ **Tool bindings:** Search, Math, Wikipedia  
- 🤯 **Multi-agent workflows** for complex tasks  

#### 🚦 **Usage:**  
1. **Set your Gemini API key**:  
   ```python
   import os
   os.environ["GOOGLE_API_KEY"] = "your-gemini-api-key"
   ```  
2. Open & run the notebook to explore **Gemini-powered agents**.  

---

## ⚙️ **Installation**  

Install all dependencies with:  

```sh
pip install langgraph langchain langchain-google-genai langchain-community langchain-ollama wikipedia
```  

### 🔑 **Requirements:**  
- **For Gemini**: Get your API key from [Google AI Studio](https://aistudio.google.com/app/apikey).  
- **For Ollama**: Ensure the Ollama server is running and the required model is pulled (`ollama pull llama3.1`).  



### 🎨 **Made with**  
❤️ **LangGraph** + **Gemini** + **Ollama**  
⚡ **Powered by AI, built for developers.**  

---

### **🚀 Get Started Now!**  
Clone the repo and dive into the future of AI agents:  

```sh


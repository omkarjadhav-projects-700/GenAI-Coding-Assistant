# Gen-AI Coding Assistant

A powerful AI-powered coding assistant built with Streamlit and Ollama, featuring multi-language support and RAG capabilities for enhanced code understanding.

## 🚀 Features

- **Multi-Language Coding Support**: Expert assistance in Python, Java, C++, JavaScript, TypeScript, Go, Rust, PHP, Ruby, Swift, Kotlin, C#, and more
- **Interactive Chat Interface**: Real-time conversation with AI models for coding questions and debugging
- **Model Selection**: Choose between two Ollama models (DeepSeek-Coder, rnj-1)
- **Debugging Assistance**: Strategic debugging techniques tailored to each programming language
- **Modern UI**: Streamlit interface for comfortable coding sessions

## 🛠️ Technologies Used

- **Frontend**: Streamlit
- **AI/ML**: LangChain, Ollama
- **Models**: DeepSeek-Coder, rnj-1
- **Python**: Core language for implementation

## 📋 Prerequisites

- Python 3.8+
- Ollama installed and running locally
- Required models pulled in Ollama:
  - `deepseek-coder:1.3b-base-q4_K_M`
  - `rnj-1` (custom model)

## 🔧 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/gen-ai-code-companion.git
   cd gen-ai-code-companion
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Start Ollama service**
   ```bash
   ollama serve
   ```

5. **Pull required models**
   ```bash
   ollama pull deepseek-coder:1.3b-base-q4_K_M
   # Add your custom model pull command if needed
   ```

## 🚀 Usage

### Code Companion App
```bash
streamlit run app.py
```

This launches the main coding assistant interface where you can:
- Select your preferred AI model
- Ask coding questions in multiple languages
- Get debugging help with language-specific techniques
- Maintain conversation history

```

## 📁 Project Structure

```
├── app.py                 # Main Streamlit coding assistant app
├── requirements.txt      # Python dependencies
└── README.md            # Project documentation
```

## 🤖 Supported Models

- **DeepSeek-Coder**: Specialized coding model with multi-language support
- **Custom Models**: Support for additional Ollama models (rnj-1)

## 🔍 Key Components

### System Prompt
The AI assistant is configured with a comprehensive system prompt that:
- Recognizes proficiency in 10+ programming languages
- Provides language-appropriate debugging strategies
- Ensures clear, concise English responses
- Maintains code quality standards

### Chat Interface
- Persistent conversation history
- Real-time AI responses
- Model switching capability
- Dark theme for extended coding sessions

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Ollama](https://ollama.ai/) for providing the local LLM infrastructure
- [LangChain](https://python.langchain.com/) for the powerful AI orchestration framework
- [Streamlit](https://streamlit.io/) for the intuitive web app framework
- [DeepSeek](https://github.com/deepseek-ai) for the advanced coding models
- [rnj-1](https://ollama.com/library/rnj-1) for the custom coding model

## 📞 Contact

Feel free to reach out if you have questions or suggestions for improvement!

---


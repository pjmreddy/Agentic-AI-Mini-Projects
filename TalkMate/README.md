<div align="center">

# 🤖 TalkMate

[![Python 3.x](https://img.shields.io/badge/python-3.x-blue.svg)](https://www.python.org/downloads/)
[![OpenAI](https://img.shields.io/badge/OpenAI-API-green.svg)](https://openai.com/)
[![Gradio](https://img.shields.io/badge/Gradio-4.0%2B-orange.svg)](https://gradio.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Your intelligent conversation companion powered by OpenAI's GPT models 🚀

[Features](#features) • [Quick Start](#quick-start) • [Installation](#installation) • [Usage](#usage) • [Customization](#customizing-the-ai-personality) • [Contributing](#contributing)

</div>

## 🌟 Features

- 💬 Interactive chat interface powered by Gradio
- 🎭 Multiple AI personalities through customizable system messages
- ⚡ Real-time streaming responses
- 🎨 Clean and intuitive user interface
- 🔄 Support for various conversation modes:
  - 👨‍💻 Technical Expert
  - 🛍️ Shopping Assistant
  - And more!

## 🚀 Quick Start

```bash
# Clone the repository
git clone 

# Install dependencies
pip install -r requirements.txt

# Set up your OpenAI API key
echo "OPENAI_API_KEY=your_api_key_here" > .env

# Launch Jupyter notebook
jupyter notebook
```

## 📋 Prerequisites

- Python 3.x
- OpenAI API key

## 🛠️ Installation

1. Clone this repository
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## ⚙️ Configuration

To use TalkMate, you'll need to set up your OpenAI API key:
1. Create a `.env` file in the project root
2. Add your OpenAI API key:
   ```env
   OPENAI_API_KEY=your_api_key_here
   ```

## 🎮 Usage

1. Start the Jupyter notebook:
   ```bash
   jupyter notebook
   ```

2. Open `Conversational_AI_chatbot_with_OpenAI_Gradio.ipynb`

3. Run all cells in the notebook

4. The Gradio interface will launch automatically, providing a chat interface where you can interact with the AI

## 🎭 Customizing the AI Personality

Modify the `sys_msg` variable in the notebook to change the AI's personality and expertise:

```python
# Technical Expert Example
sys_msg = "You are an AI expert in artificial intelligence and machine learning..."

# Shopping Assistant Example
sys_msg = "You are an AI shopping assistant helping users find perfect products..."
```


## 🛣️ Roadmap

- [ ] Add support for multiple concurrent conversations
- [ ] Implement conversation history export
- [ ] Add more pre-configured AI personalities
- [ ] Enhance UI with themes and customization options

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- OpenAI for their powerful GPT models
- Gradio team for the amazing UI framework
- All contributors who help improve TalkMate

---

<div align="center">
Made with ❤️ by <a href="mailto:pervali810@gmail.com">pervali810@gmail.com</a>
</div>

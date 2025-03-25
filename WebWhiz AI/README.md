<div align="center">

# WebWhiz AI

🤖 An intelligent website summarization tool powered by local Ollama LLM that extracts and analyzes web content to generate structured Markdown summaries.

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Ollama](https://img.shields.io/badge/Ollama-%E2%89%A50.1.0-green)](https://ollama.ai/)
[![BeautifulSoup4](https://img.shields.io/badge/BeautifulSoup4-%E2%89%A54.12.0-orange)](https://www.crummy.com/software/BeautifulSoup/)
[![IPython](https://img.shields.io/badge/IPython-%E2%89%A58.22.0-yellow)](https://ipython.org/)

</div>

## 🚀 Features

- **Smart Web Scraping**: Efficiently extracts content using BeautifulSoup
- **Local AI Processing**: Leverages Ollama (llama3.2 model) and Open AI (gpt-4o-mini) for privacy-focused analysis
- **Markdown Output**: Generates well-structured, readable summaries
- **Interactive Usage**: Seamless integration with Jupyter notebooks

## 📋 Requirements

| Package | Version |
|---------|----------|
| ollama | ≥ 0.1.0 |
| requests | ≥ 2.31.0 |
| beautifulsoup4 | ≥ 4.12.0 |
| ipython | ≥ 8.22.0 |

## 🛠️ Installation

1. Clone the repository

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Start Ollama server

4. Launch Jupyter notebook:
   ```bash
   jupyter notebook Website_Summarization_using_Local_Ollama.ipynb
   ```

## 💻 Usage

```python
# Import required modules
from webwhiz import Website, summarize
from IPython.display import Markdown, display

# Scrape website content
web = Website("https://example.com")

# Generate AI summary
summary = summarize(web.text)

# Display formatted output
display(Markdown(summary))
```

## 📝 Example Output

Here's a sample of what WebWhiz AI generates:

### DeepLearning.AI Summary

#### Key Offerings
- **Short Courses**: Practical AI/ML education from experts
- **ChatGPT Prompt Engineering Course**: Free foundational course
- **Professional Certificate**: Data analytics certification
- **AI Newsletter**: Industry updates from Andrew Ng
- **Community Forum**: AI professional networking

#### Target Audience
- AI career starters/advancers
- ML professionals expanding skills
- Students exploring AI applications

### University of Louisiana at Lafayette Summary

#### Academic Programs
- 80+ undergraduate degrees
- 30+ master's programs
- 20+ doctoral programs

#### Research Focus
- Artificial Intelligence
- Cybersecurity
- Environmental Science

#### Campus Life
- 400+ student organizations
- NCAA Division I athletics
- Cultural diversity programs

---

<div align="center">
Made with ❤️ by <a href="mailto:pervali810@gmail.com">pervali810@gmail.com</a>
</div>

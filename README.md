# GenAI & Insurance: Multi-Document Summarization Demo

This repository contains a hands-on demo of how Generative AI and Multi-Document Summarization (MDS) can be used to simplify the understanding of complex insurance product documentation.

---

## 📋 Project Overview

The demo shows how to:

- Load and segment real insurance documents.
- Apply prompt-based summarization using the **Map-Reduce** strategy.
- Extract financial and contractual information from each section.

---

## 📦 Installation (Local)

To run the notebook locally:

```bash
# Clone the repository
git clone https://github.com/ivanbrancati/mds-insurance-demo.git
cd mds-insurance-demo

# Run notebook
jupyter notebook technical-demo.ipynb
```

---
## 🔗 Dependencies

You need to install some dependencies to use all the needed libraries. You can install them directly from the notebook:

```python
# Install dependencies
%pip install -r requirements.txt
```
## 🔑 Configuration

You need an OpenAI API Key to run the summarization.

You can define the key directly in your notebook:

```python
# Load OpenAI API key
# Instructions: https://help.openai.com/en/articles/4936850-where-do-i-find-my-openai-api-key
open_api_key = "Insert you OpenAI API key here"
os.environ["OPENAI_API_KEY"] = open_api_key
```

---

## 📁 Folder Structure

```
├── technical-demo.ipynb             # Technical demo notebook
├── requirements.txt           # Python dependencies
├── README.md                  # This file
└── 1.pdf                     # Insurance PDF document
```

---

## 📚 References

This demo is part of a post on Data Reply DataTech Blog:
📄 [Blog post]([https://medium.com/data-reply-it-datatech](https://medium.com/data-reply-it-datatech/genai-for-insurance-multi-document-summarization-of-insurance-products-fc77878fc222)) 



---

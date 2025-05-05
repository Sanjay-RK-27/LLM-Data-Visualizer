---
title: "LLM - Data Visualizer"
output: github_document
---

# AI Data Visualization Agent

A minimalistic Streamlit-based AI-powered application that understands natural language queries and generates appropriate data visualizations using large language models (LLMs).

## Features

- Natural language interface for querying uploaded datasets  
- Support for multiple chart types: line, bar, scatter, pie, bubble  
- Automatic data cleaning and preprocessing  
- Secure code execution via E2B sandbox  
- Real-time visualization generation  
- Multi-model LLM support:
  - Meta-Llama 3.1 405B  
  - DeepSeek V3  
  - Qwen 2.5 7B  
  - Meta-Llama 3.3 70B  

## Setup Instructions

### 1. Get API Keys

- [Together AI API Key](https://api.together.ai/signin)  
- [E2B API Key](https://e2b.dev/docs/legacy/getting-started/api-key)  

### 2. Clone the Repository

```bash
git clone repository
cd LLM-Data-Visualizer
```

### 3. Install Dependencies

Ensure Python 3.8+ is installed. Then run:

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit App

```bash
streamlit run llm_data_visualizer.py
```

After launching, upload your dataset and interact using natural language queries.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.



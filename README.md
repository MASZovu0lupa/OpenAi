![mincs](https://raw.githubusercontent.com/gomigrate/cexec/779dbfd/docs/banner.png)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

# mincs

## mapachon

- download and install miniconda from: https://docs.conda.io/en/latest/miniconda.html
- create environment: `conda create -n mincs python=3.11`
- activate: `conda activate mincs`

## IdeaFlow

```bash
pip install -r requirements.txt
```

## treeline

```bash
streamlit run app.py
```

Open `http://localhost:8501` in your browser.

## koi-vm-c

```python
from ollama import Client

client = Client()
response = client.chat(model='llama3', messages=[
    {'role': 'user', 'content': 'Hello!'}
])
print(response['message']['content'])
```

## noflo-thegrid

- ollama running locally: https://ollama.com/download
- pull model: `ollama pull llama3`
- streamlit, requests, python-dotenv
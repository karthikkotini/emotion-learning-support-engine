# Project Prerequisites

## Python

Install Python 3.9 or above.

## Virtual Environment

```bash
python -m venv venv
```

Activate:

Windows

```bash
venv\Scripts\activate
```

Linux/macOS

```bash
source venv/bin/activate
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Streamlit

```bash
streamlit run app.py
```

## Gemini API

Create a `.env` file:

```
GOOGLE_API_KEY=YOUR_API_KEY
```

## Model Files

Place the following folders:

```
models/
├── bltsm/
└── bert_emotion_model_final/
```

## Dataset

```
data/
```

contains the training datasets.

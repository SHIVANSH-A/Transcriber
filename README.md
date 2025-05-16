# 🎤 Groq Whisper Audio Transcriber

A simple and elegant Gradio interface that uses the [OpenAI Whisper](https://openai.com/research/whisper) `large-v3` model via the Groq API to transcribe uploaded audio files.

## 🚀 Features

- 🔊 Upload audio files (WAV, MP3, FLAC, etc.)
- 🧠 Uses Whisper `large-v3` model for accurate speech-to-text transcription
- ⚡ Fast and lightweight UI with Gradio
- 🔒 Local and session-based — no files are stored

---

## 📦 Requirements

- Python 3.8+
- [Gradio](https://gradio.app)
- [Groq Whisper API key](https://console.groq.com/) *(or OpenAI Whisper if you're using that instead)*
- `requests` or appropriate API client

---

## 🛠 Installation

1. **Clone the repository:**

```bash
git clone https://github.com/your-username/groq-whisper-transcriber.git
cd groq-whisper-transcriber
```

2. **Create a virtual environment (optional but recommended):**

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies:**

```bash
pip install -r requirements.txt
```

**`requirements.txt`**
```txt
gradio
requests  # or openai, groq, etc. depending on your API integration
```

---

## 🔑 Set Up Your API Key

Create a `.env` file or securely store your API key as an environment variable:

```bash
export GROQ_API_KEY="your_api_key_here"
```

Or use Python's `os.environ.get("GROQ_API_KEY")` inside your script.

---

## ▶️ Run the App

```bash
python app.py
```

Then open [http://localhost:7860](http://localhost:7860) in your browser.

---



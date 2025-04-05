# 🎙️Grammar-Scoring-Engine-for-Voice
  This project automatically transcribes spoken audio and evaluates its grammar quality using OpenAI's Whisper for transcription and `language_tool_python` for 
  grammar checking. The grammar score is predicted using a trained machine learning model based on extracted features.


## 🚀 Features

- 📢 Transcribe audio (.wav) files using OpenAI Whisper
- 🧠 Extract grammar errors and compute error density
- 📊 Predict a grammar score using a trained ML model
- ✅ Error handling and warnings suppression included


## 🛠️ Tech Stack

- Python 3.12.1
- [Whisper](https://github.com/openai/whisper)
- `language_tool_python`
- scikit-learn (for model prediction)
- Jupyter Notebook 


## 🧪 How It Works

1. Load an audio file (e.g., `Dataset/Speaker26_000.wav`)
2. Transcribe the audio using Whisper
3. Extract grammar features:
   - Number of grammatical errors
   - Error density (errors per word)
4. Predict the grammar score using a pre-trained model


## 📦 Installation

pip install openai-whisper
pip install language_tool_python
pip install scikit-learn

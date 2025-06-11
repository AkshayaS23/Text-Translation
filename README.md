# 🌐 Text Translator & Text-to-Speech (TTS) Tool

A Python-based interactive tool that takes input text, translates it into a chosen language, and converts the translated text into speech using Google Text-to-Speech (gTTS). Ideal for beginners exploring Natural Language Processing (NLP), text-to-speech conversion, and multilingual support.

## 🚀 Features

- 🌍 **Language Translation:** Translates any input text into multiple languages using `googletrans`.
- 🔊 **Text-to-Speech (TTS):** Converts the translated text into speech using `gTTS`.
- 🎧 **Audio Playback:** Plays the generated audio within Jupyter Notebook using `IPython.display.Audio`.
- 📦 **Download Option:** Saves the output as an `.mp3` file locally.
- 🛡️ **Input Validation:** Checks for valid language codes to ensure smooth execution.

## 📚 Supported Languages

| Code  | Language     |
|-------|--------------|
| en    | English      |
| es    | Spanish      |
| fr    | French       |
| de    | German       |
| hi    | Hindi        |
| ta    | Tamil        |
| ja    | Japanese     |
| ko    | Korean       |
| it    | Italian      |
| pt    | Portuguese   |
| zh-cn | Chinese (Simplified) |
| zh-tw | Chinese (Traditional) |

## 🔧 Installation

Use the following commands to install the required libraries:

```bash
pip install gTTS googletrans==4.0.0-rc1

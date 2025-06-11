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

🧠 How It Works
User enters a text input.

The tool asks for the desired language to translate.

It translates the input text into the selected language.

The user selects a TTS language (optional, defaults to the translation language).

It generates an audio file and plays it automatically.


📝 Example

Enter the text you want to convert to speech: Hello, how are you?
Enter the language code to translate the text: ta
Enter the language code for TTS (optional): ta
Enter the filename (optional): output.mp3
Output:
🎧 Tamil translation: வணக்கம், நீங்கள் எப்படி இருக்கிறீர்கள்?
🔊 Audio will play automatically.



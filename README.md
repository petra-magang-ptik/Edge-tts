# Edge-tts
Usage of edge-tts

# Edge TTS Audio Converter

This repository contains a Python script that utilizes the Microsoft Edge Text-to-Speech (TTS) service to generate speech audio files based on user input. The script allows you to select the speaker's gender and language and then converts the resulting MP3 file to WAV format for further use.

## Features

- **Text-to-Speech Conversion:** Generate speech from text using Microsoft Edge's TTS service.
- **Customizable Voice Selection:** Choose between male and female voices and select the language.
- **Audio Format Conversion:** Convert the output MP3 file to WAV format with specific audio properties.

## Prerequisites

1. **Microsoft Edge TTS Installation:** Ensure `edge-tts` is installed. If not, install it using:
   ```bash
   pip install edge-tts
2. **Python Libraries:** Ensure 'audiosegment' is installed. If not, install it using:
     ```bash
   pip install audiosegment
   ```
## Script Overview
The script performs the following tasks:

### Get User Input
1. Text to be Converted to Speech:
   - The text input that will be converted into speech.
2. Speaker's Gender:
   - 1 for Male
   - 2 for Female
3. Speaker's Language:
   - 1 for English
   - 2 for Indonesian

## To Generate Speech
Run Command: (in terminal)
```bash
   python generateAudio.py
```

# Model Customization
To customize voice model of generateAudio.py, go to edgeVoiceModels.ipynb to preview all the English and Indonesian model

To list all edge-tts models available, run (in terminal):
```bash
   edge-tts --list-voices
```

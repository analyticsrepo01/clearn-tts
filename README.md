# clearn-tts

A Text-to-Speech (TTS) project using Google Cloud's Gemini-TTS API for high-quality speech synthesis with advanced voice control.

## Overview

This project demonstrates how to use Google Cloud's Gemini-TTS technology to generate natural-sounding speech with granular control over voice characteristics, emotional expression, pace, and tone through text-based prompts.

## Features

- **Multiple Voice Options**: Access to 30 distinct voice personas (Aoede, Fenrir, Orus, etc.)
- **Language Support**: 80+ locales available for synthesis
- **Emotion Control**: Direct emotional expression through natural-language prompts
- **Voice Steering**: Control pace, tone, accent, and style
- **Expressive Tags**: Add effects like chuckling, coughs, pauses within text
- **Multi-Speaker Dialogues**: Create conversations between two different speakers
- **Real-time Synthesis**: Online processing for immediate audio generation

## Contents

- `gemini_tts_voices.ipynb`: Jupyter notebook with examples of:
  - Basic speech synthesis
  - Emotion and tone control with prompts
  - Pace modification
  - Expressive tags usage
  - Multi-speaker dialogue generation

## Requirements

- Google Cloud Project with Text-to-Speech API enabled
- Python 3.7+
- google-cloud-texttospeech >= 2.31.0
- ffmpeg (for audio processing)

## Getting Started

1. Set up your Google Cloud project and enable the Text-to-Speech API
2. Install required dependencies:
   ```bash
   pip install google-cloud-texttospeech
   ```
3. Authenticate with Google Cloud
4. Open and run the Jupyter notebook

## Models

- `gemini-2.5-flash-tts`: Fast synthesis model
- `gemini-2.5-pro-tts`: High-quality synthesis model

## Documentation

For more information, see:
- [Gemini-TTS Documentation](https://cloud.google.com/text-to-speech/docs/gemini-tts)
- [Available Voices](https://cloud.google.com/text-to-speech/docs/gemini-tts#voice_options)
- [Language Availability](https://cloud.google.com/text-to-speech/docs/gemini-tts#language_availability)

## License

Apache License 2.0

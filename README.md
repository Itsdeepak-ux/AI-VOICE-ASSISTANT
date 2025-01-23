# Voice Assistant with Temperature Control

This project is a Voice Assistant built using the `livekit` library. It includes functionality for controlling room temperature across different zones and integrates with OpenAI's speech-to-text (STT), text-to-speech (TTS), and language models (LLM). The assistant is designed to provide a seamless voice interface with short and concise responses.

## Features

- **Voice Interaction**: The assistant uses OpenAI models for speech recognition and response generation.
- **Room Temperature Management**: Retrieve temperature information for specific zones (Living Room, Bedroom, Kitchen, Bathroom, Office).
- **Customizable Context**: Set up initial assistant behavior and interaction style.
- **Integration**: Uses Silero for voice activity detection (VAD).

## Prerequisites

1. Python 3.9 or later.
2. Install dependencies from `requirements.txt`:
   ```bash
   pip install -r requirements.txt

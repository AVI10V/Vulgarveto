# Vulgarveto
# Audio Profanity Filter Web App

This is a Streamlit-based web application that allows users to upload an audio file, transcribe its speech content, detect and filter out profane or bad words, and generate a clean, censored audio output. The app provides an interactive UI with multiple censorship styles, real-time profanity meter, and detailed transcription views.

---

## Features

- Upload WAV audio files for processing
- Transcribe audio to text using Google Speech Recognition API
- Detect bad words from a customizable list
- Filter and censor detected profanity with different styles (beeps, stars, asterisks, etc.)
- Convert cleaned text back to speech using Google Text-to-Speech (gTTS)
- Display original and cleaned transcriptions side-by-side
- Play original and filtered audio clips within the app
- Profanity meter showing percentage of bad words in the audio
- Fun UI with animated audio meter, tabs, sidebar facts, and quotes
- Customizable chunk duration for transcription sensitivity
- Basic settings UI placeholders for future extension

---

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/audio-profanity-filter.git
   cd audio-profanity-filter

## Speech-to-Text--Transcription Web Application with Flask


### Key Components:

1. **Audio and Video Processing:**
   - `extract_audio_from_video`: Extracts audio from a video file using MoviePy.
   - `convert_mp3_to_wav`: Converts an MP3 audio file to WAV format using PyDub.

2. **Speech Recognition:**
   - Utilizes the SpeechRecognition library for Google Web Speech API-based speech recognition.
   - Features an Easter egg trigger for a fun interaction with a name of the creator "VANI" short for my name

3. **Flask Web Application:**
   - Routes:
     - `/` (main page): Allows users to choose input type (microphone, audio file, or video file).
     - `/save_transcript`: Saves the transcript to a file.
     - Default route starts the Flask app.

4. **User Interaction:**
   - Web interface for choosing input type.
   - Captures microphone input and transcribes.
   - Allows uploading audio/video files for transcription.

5. **Dependencies:**
   - Ensure Flask, MoviePy, SpeechRecognition, and PyDub are installed:
     ```bash
     pip install Flask MoviePy SpeechRecognition PyDub
     ```

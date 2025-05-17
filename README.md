# speech-recognition-client-server-python
A Python-based client-server speech recognition system using sockets, PyAudio, and Google SpeechRecognition API. The client records audio and sends it with text to the server, which returns the recognized speech and TTS audio for playback.


# 🎙️ Client-Server Speech Recognition System (Python)
This project demonstrates a real-time client-server application for speech recognition using socket programming in Python. The system enables recording voice input, sending it to a server, recognizing the speech using Google Speech Recognition API, and sending the response (recognized text, original audio, and TTS audio) back to the client.

## 🔧 Technologies Used
- Python 3
- Socket Programming
- PyAudio (for recording and playback)
- Wave (for audio file handling)
- SpeechRecognition (Google Web Speech API)
- pyttsx3 (Text-to-Speech synthesis)
- Jupyter Notebook for audio playback visualization (optional)

## 📌 Features
✅ Real-time audio recording at client side  
✅ Sends audio and text over the network to the server  
✅ Server-side speech recognition using Google API  
✅ Converts text to speech and sends it back  
✅ Plays back original and TTS audio at client  
✅ Uses TCP sockets for reliable data transmission

## ▶️ How to Run
1. Install Required Libraries
- pip install playsound pyttsx3 pyaudio speechrecognition wave
- run server.py
- run client.py
  
### Interaction
- The client will record audio for 10 seconds.
- You'll be prompted to enter a text message.
- The server recognizes the recorded speech and returns:
- The transcribed text
- The original audio (as .wav)
- The TTS version of your typed message
- All outputs are played back and saved on the client side.

### 💡 Use Cases
- Voice-enabled chat clients
- Speech-to-text transcription
- Text-to-speech response systems
- Remote audio processing

### 🧠 Learning Outcomes
- Built custom TCP-based client-server communication
- Integrated speech recognition and TTS systems
- Managed real-time audio streaming and encoding
- Gained hands-on experience in Python networking and audio processing

👩‍💻 Author
Developed by Varshini15-official


Voice Assistant in Python

A simple yet powerful voice-controlled assistant built using Python.
It listens to your voice commands, converts speech to text, and performs actions like playing YouTube videos — all hands-free! 🗣️🎶

🚀 Features

✅ Speech Recognition – Converts spoken commands into text using Google Speech API.
✅ Text-to-Speech – Replies back using pyttsx3 for a natural voice response.
✅ YouTube Integration – Plays requested songs or videos via pywhatkit.
✅ Wake Word Activation – Responds only when a specific keyword (e.g., “Shashank”) is spoken.
✅ Error Handling – Gracefully handles unrecognized commands or microphone errors.

🧠 How It Works

The program listens for your voice through the microphone.

It recognizes and processes the spoken command.

If the command includes “play,” it automatically searches and plays the song on YouTube.

Otherwise, it responds with a polite message using speech synthesis.

🧩 Tech Stack

Python

SpeechRecognition

Pyttsx3

PyWhatKit

<img width="1920" height="1080" alt="bert_chatbot" src="https://github.com/user-attachments/assets/00f5831d-06ea-41f8-a0b7-ba5475ab9aee" />

<img width="1919" height="888" alt="Screenshot 2025-11-04 165038" src="https://github.com/user-attachments/assets/6360c045-bb9e-45c4-8518-81e9873ca58b" />


Install dependencies:

pip install speechrecognition pyttsx3 pywhatkit

Run the project:

python Speech.py



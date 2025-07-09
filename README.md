# Text-to-Speech-convertor
this is a 'Text to Speech convertor' Python based project.
Text-to-Speech Converter using gTTS and Playsound in Python

Project Description:
This project is a simple Text-to-Speech (TTS) application built in Python that converts user-entered text into speech using the Google Text-to-Speech (gTTS) API. Once the speech is generated, it is saved as an MP3 audio file and immediately played back using the playsound module.

The tool provides a quick and effective way to turn any English text into audio, making it useful for accessibility tools, language learning, and basic voice assistant applications.

Key Features:
Converts user input text into natural-sounding speech.

Saves the audio as an MP3 file (welcome.mp3).

Automatically plays the saved audio file.

Uses Google's TTS API, ensuring high-quality voice output.

Technologies Used:
Python 3

gTTS (Google Text-to-Speech) – for generating the speech

playsound – for playing the generated audio

How It Works:
The user is prompted to enter text.

The gTTS module converts the text into speech using Google's TTS engine.

The generated speech is saved as an MP3 file named "welcome.mp3".

The playsound module plays the MP3 file for the user to hear.

Use Cases:
Creating simple voice assistants.

Enhancing accessibility for visually impaired users.

Language learning by hearing pronunciation of words.

Fun projects or audiobook-style applications.

Limitations:
Internet connection is required because gTTS uses an online API.

Limited to supported languages by gTTS (default is English).

Only plays the most recent input saved as "welcome.mp3" unless modified.

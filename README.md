VANS Audio System

This project implements an audio processing system using Streamlit, a web application framework for Python. The system allows users to upload audio files or provide YouTube links to extract the audio content, convert it to text, perform forced alignment, search for specific words within the audio, and seek to the timestamp of the found word.

Features:
1) Audio Upload: Users can upload audio files in MP3 or WAV format.
2) YouTube Link: Users can provide YouTube links to extract the audio content.
3) Audio to Text Conversion: Utilizes the SpeechRecognition library to convert audio to text.
4) Forced Alignment: Performs forced alignment using the Gentle library to synchronize the text with the audio.
5) Word Search: Users can search for specific words within the audio content.
6) Seek Functionality: Allows users to seek to the timestamp of the found word within the audio.
7) Dynamic User Interface: Implemented using Streamlit, providing an interactive and user-friendly interface.


Run the application:
  streamlit run app.py

1) Choose the audio source (either upload an audio file or provide a YouTube link).
2) Click on "Process Audio" to initiate audio processing.
3) Perform word search and seek functionality as needed.
4) Click on "Done" to delete temporary files and end the session.


Requirements:
Python 3.6+
Streamlit
Pytube
MoviePy
SpeechRecognition
Requests
NLTK
Pydub


Contributors:
Afthab Roshan
Nihal Anas

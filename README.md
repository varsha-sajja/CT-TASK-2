# CT-TASK-2

# CT-Task-2SPEECH-RECOGNITION-SYSTEM

Company: CODTECH IT SOLUTIONS PVT.LTD

Name: Sajja Varsha

Intern ID: CT06DL1341

Domain: Artificial Intelligence

Batch Duration: may 5th, 2025 to june 20th, 2025

Mentor Name: Neela Santhosh Kumar

# Description
This Python script provides a tool for summarizing lengthy articles using Natural Language Processing (NLP) techniques. It leverages the sumy library to extract concise summaries from input text.

# Functionality
The script defines a function transcribe_audio that takes an audio file path as input. It performs the following steps:

Loads the audio file: Reads the audio file using pydub and converts it to WAV format if necessary. Initializes the recognizer: Creates an instance of the Recognizer class from speech_recognition. Records audio data: Reads the audio data from the WAV file. Transcribes audio: Uses the Google Speech Recognition API to transcribe the audio data. Returns the transcription: If successful, returns the transcribed text; otherwise, returns an error message.

# Usage
Install dependencies: Make sure you have speech_recognition and pydub installed. You can install them using pip: Replace audio file path: Update the audio_file_path variable with the path to your audio file. Run the script: Execute the Python script. The transcribed text will be printed to the console.

# Example
python audio_file_path = ""C:\Users\Sunit\OneDrive\Documents\audio.mp3.unknown"" # Replace with your audio file path result = transcribe_audio(audio_file_path) print("Transcription:\n", result)

# Notes
The script uses the Google Speech Recognition API, which requires an internet connection. The accuracy of the transcription may vary depending on the quality of the audio and the speaker's accent. For longer audio files, consider splitting them into smaller segments for better performance.

# output
![Image](https://github.com/user-attachments/assets/90b39ae1-d619-4f8d-82f0-3a00eaf64691)

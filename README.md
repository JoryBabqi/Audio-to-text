#Arabic Speech to Text using Hugging Face 

This project takes an Arabic audio file (from the Arabic Speech Corpus or any .wav file), converts the speech into text using SpeechRecognition, and then generates a reply or summary using a Hugging Face text-generation model.

Requirements:

Install the required libraries:

- !pip install SpeechRecognition
- !pip install transformers

How It Works: 

Convert Audio to Text (Arabic)

Uses speech_recognition to transcribe an Arabic .wav file.

Generate a Reply uses the Hugging Face model google/flan-t5-small to produce a text response.

Outputs:

Prints the Arabic text from the audio.

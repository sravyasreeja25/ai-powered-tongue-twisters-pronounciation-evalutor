# ai-powered-tongue-twisters-pronounciation-evalutor
# 🗣️ AI-Powered Tongue Twister Pronunciation Evaluator

This is a fun and interactive Python application that helps users practice and improve their pronunciation using tongue twisters. It uses speech recognition and text-to-speech to guide users, record their speech, and evaluate pronunciation accuracy.

## 🎯 Features

- 🎤 Voice input using microphone
- 🔊 Text-to-speech guidance and feedback
- 🧠 Pronunciation scoring using string similarity and word match
- 🌀 Tongue twisters categorized by difficulty: Low, Medium, High
- 🔁 Option to retry and improve your score

## 🛠️ Technologies Used

- `speech_recognition` – for capturing and transcribing user speech
- `pyttsx3` – for text-to-speech output
- `difflib` – for comparing spoken text with reference
- `numpy`, `random`, `time` – for scoring and interaction flow

## 📦 Installation

Make sure you have Python 3.7+ installed. Then install the required packages:

```bash
pip install SpeechRecognition pyttsx3 numpy

# 🧠🎙️ RaspberryPi AI Voice & Video Assistant


A Local LLM-Powered, Privacy-First AI Companion Built with Raspberry Pi + Ollama + LangChain
Step into the future with a retro twist. This project transforms your Raspberry Pi into a fully offline, voice-controlled AI assistant — running LLMs locally via Ollama, using LangChain for orchestration, and leveraging gTTS, speech recognition, and GPIO for voice and hardware interaction.

🔧 Features
🎤 Voice-to-LLM interaction: Talk to your Pi using natural language

🧠 Locally hosted LLMs (LLaMA3) via Ollama – no cloud, no compromise

🔁 Multithreaded architecture for smooth speech-to-text, processing, and playback

🔊 Real-time TTS playback using gTTS + Pygame

💡 LED feedback via GPIO to show system state (thinking, listening, speaking)

📜 Session logging for conversations with automatic date-based file creation

🛑 Hotword activation (say "Jack") and natural termination ("That's all")

🧩 Tech Stack
Raspberry Pi 4/5

Python 3.11+

Ollama for local LLMs

LangChain for conversational memory

gTTS + pygame for text-to-speech

SpeechRecognition + pyaudio

gpiozero for LED control

🚀 Use Cases
Smart home control

Private personal assistant

Voice interface for embedded systems

Offline chatbot for accessibility

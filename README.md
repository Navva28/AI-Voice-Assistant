🎙️ AI Voice Assistant

An AI-powered voice assistant built with Python that converts spoken input into text, processes it using a large language model, and responds with natural-sounding speech.

The project demonstrates the integration of Speech-to-Text, LLMs, Text-to-Speech, API integration, and Streamlit into a single AI application.

✨ Features

- 🎤 Voice Input — Capture user speech through the microphone
- 📝 Speech-to-Text — Convert spoken audio into text using Whisper
- 🧠 AI Responses — Generate intelligent responses using a Groq-hosted LLM
- 🔊 Text-to-Speech — Convert AI responses back into speech using gTTS
- 💬 Conversation Interface — Interact with the assistant through a simple Streamlit UI
- ⌨️ Text Input — Supports typed input as well as voice input
- 🔐 Environment Variables — API keys are securely managed through ".env"
- ⚡ Fast AI Inference — Uses Groq for low-latency model inference

🧠 How It Works

          🎤 User Voice
               │
               ▼
        ┌───────────────┐
        │    Whisper    │
        │ Speech → Text │
        └───────┬───────┘
                │
                ▼
          📝 Transcription
                │
                ▼
        ┌───────────────┐
        │   Groq LLM    │
        │  AI Response  │
        └───────┬───────┘
                │
                ▼
          💬 Text Response
                │
                ▼
        ┌───────────────┐
        │     gTTS      │
        │ Text → Speech │
        └───────┬───────┘
                │
                ▼
             🔊 Audio

🛠️ Tech Stack

Technology| Purpose
Python| Core application development
Streamlit| Web interface
Groq API| LLM inference and speech-to-text
Whisper| Speech recognition
gTTS| Text-to-speech
python-dotenv| Environment variable management

📁 Project Structure

AI-Voice-Assistant/
│
├── app.py
├── requirements.txt
├── .env.example
├── .gitignore
├── README.md
└── assets/

«The exact structure may vary depending on the current implementation.»

🚀 Getting Started

1. Clone the repository

git clone https://github.com/Navva28/AI-Voice-Assistant.git
cd AI-Voice-Assistant

2. Create a virtual environment

python -m venv venv

Activate it on Windows:

venv\Scripts\activate

3. Install dependencies

pip install -r requirements.txt

4. Configure your API key

Create a ".env" file in the project directory:

GROQ_API_KEY=your_api_key_here

Never commit your ".env" file or expose your API key publicly.

5. Run the application

streamlit run app.py

The application will open in your browser.

💡 Example Workflow

1. Start the application.
2. Provide a question through voice or text.
3. The voice input is transcribed into text.
4. The transcription is sent to the AI model.
5. The model generates a response.
6. The response is converted into speech.
7. The generated audio is played back to the user.

🎯 Learning Objectives

This project was built to gain practical experience with:

- Python application development
- API integration
- Speech recognition
- Large Language Models
- Generative AI
- Text-to-Speech systems
- Streamlit application development
- Environment and API-key management
- Building an end-to-end AI application

🔮 Future Improvements

Possible improvements include:

- 🧠 Persistent conversation memory
- 🌍 Multi-language voice support
- 👤 User profiles
- ⚡ Streaming AI responses
- 🎙️ Improved voice activity detection
- 🔊 More natural text-to-speech voices
- 🗂️ Conversation history
- 📴 Offline/local model support
- 🚀 Cloud deployment

👨‍💻 Author

Navva

B.Sc. Data Science & Analytics
Interested in AI Engineering, Generative AI, Machine Learning, and Cloud Technologies.

Connect

- GitHub: "Navva28"

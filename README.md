# Personal-Voice-Assistant
🗣️ Cheeku - Your Personal Voice Assistant
Cheeku is a Python-based personal voice assistant that listens to your commands and responds with actions like playing songs on YouTube, telling the time, fetching Wikipedia summaries, cracking jokes, and opening applications like Chrome and VS Code — all with your voice!

🚀 Features
🎵 Play YouTube Videos

⏰ Tells the Current Time

📚 Fetches Information from Wikipedia

😂 Tells Programming Jokes

🌐 Opens Google Chrome

💻 Launches Visual Studio Code

🙋‍♂️ Answers About Virat Kohli

🛑 Exit with Voice Command

🧠 Tech Stack
Python 3.x

speech_recognition – For speech-to-text

pyttsx3 – For text-to-speech (offline)

pywhatkit – For YouTube and Google commands

wikipedia – For fetching summaries

pyjokes – For fun programming jokes

🛠 Installation
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/cheeku-voice-assistant.git
cd cheeku-voice-assistant
2. Install Required Packages
bash
Copy
Edit
pip install -r requirements.txt
Or manually install:

bash
Copy
Edit
pip install SpeechRecognition pyttsx3 pywhatkit wikipedia pyjokes pipwin
pipwin install pyaudio
💡 Note: Use pipwin for installing pyaudio on Windows.

📄 Usage
Run the script:

bash
Copy
Edit
python cheeku_voice_assistant.py
Say commands like:

"play Alan Walker"

"what's the time"

"who is Virat Kohli"

"tell me a joke"

"open chrome"

"open code"

"exit"

🖥 Platform Notes
✅ Best used on a local machine with microphone and GUI (Windows/Linux with desktop)

❌ Not supported in headless environments (like Google Colab or servers without GUI)

📌 Future Improvements
Wake word detection (e.g., "Hey Cheeku")

GUI with Tkinter or PyQt

Weather reports

WhatsApp or Email integration

👨‍💻 Author
Sripathirao Karri

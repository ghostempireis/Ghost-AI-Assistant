# 👻 Ghost AI Assistant

A **hacker-style AI voice assistant** that lets you **control your computer, browse the web, and chat with AI using voice commands**.  
Ghost AI Assistant combines **speech recognition**, **system automation**, and **OpenAI GPT-powered conversational AI** with a **futuristic J.A.R.V.I.S.-style GUI**.

---

## 🚀 Features

- 🎤 **Voice Recognition** – Recognizes commands using Speech-to-Text  
- 🖥 **System Control** – Open apps like Chrome, Notepad, Calculator, Word, Excel, WhatsApp  
- 🌐 **Web Automation** – Search & open websites (YouTube, Google, Wikipedia, GitHub)  
- 🤖 **OpenAI GPT Chat** – Conversational AI assistant for unrecognized commands  
- ⏱ **Activity Monitoring** – Automatic standby after inactivity (10 minutes default)  
- ✨ **J.A.R.V.I.S.-style GUI** – Futuristic glowing interface built with PyQt5  
- 🔊 **Text-to-Speech** – Ghost responds using natural voice  
- 🛡 **Manual or Voice Wake** – Activate Ghost using wake words or button  

---

## 📂 Project Structure

Ghost-AI-Assistant/
│
├── ghost_ai.py # Main application code
├── requirements.txt # Python dependencies
├── README.md # Project documentation
├── .gitignore # Ignore unnecessary files
└── LICENSE # MIT License

---

## 🛠 Installation

1️⃣ **Clone the repository**
```bash
git clone https://github.com/ghostempireis/Ghost-AI-Assistant.git
cd Ghost-AI-Assistant
2️⃣ Install dependencies

pip install -r requirements.txt
3️⃣ Configure API Keys
Create a .env file or edit ghost_ai.py with your API keys:

OPENAI_API_KEY=your_openai_api_key
YOUTUBE_API_KEY=your_youtube_api_key
⚡ Note: To use pyaudio on Windows, you may need:

pip install pipwin
pipwin install pyaudio
▶️ Usage
Run the application:

python ghost_ai.py
Example Voice Commands
Command	Description
"Hello Ghost"	Wake up Ghost AI
"Open YouTube"	Opens YouTube
"Play [song/video] on YouTube"	Plays requested video
"Open Chrome"	Launch Chrome browser
"What is the time?"	Ghost announces current time
"Search [query] on Google"	Opens Google search
"Search [query] on Wikipedia"	Opens Wikipedia search
"Stop listening"	Ghost returns to standby mode
"Thank you"	Ghost responds politely



Futuristic interface with system status, activity bar, and communication log.


Example of voice command processing and AI response.


Ghost responding to a conversational query.

💡 How It Works
Ghost listens for wake words: "hello ghost", "hey ghost", "ok ghost", "wake up ghost"

Once awake, Ghost listens for your commands or queries.

Ghost performs system automation, web searches, or OpenAI GPT-3.5 conversation based on the command.

Ghost provides voice feedback and logs messages in the communication panel.

After 10 minutes of inactivity, Ghost automatically returns to standby mode.

📜 License
This project is licensed under the MIT License – see the LICENSE file for details.

## 💡 Author
**Ranjan Kumar**  
🚀 Passionate about Cybersecurity & AI  
📧 Email - ranjan.osint@gmail.com

LinkedIn profile -https://www.linkedin.com/in/ranjanchauhan-cybersec/

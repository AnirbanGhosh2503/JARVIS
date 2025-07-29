# 🧠 J.A.R.V.I.S. – Your Personal AI Voice Assistant 💬🎙️

> **"Hello Sir, Jarvis A.I. activated."**

A Python-based voice-controlled virtual assistant that mimics the capabilities of Tony Stark’s J.A.R.V.I.S. It listens to your voice commands, understands your intent, performs tasks like opening websites, telling the time, launching applications, and even having intelligent AI-powered conversations — all in real-time using OpenAI’s GPT!

---

## 🚀 Features

🎧 **Voice Recognition (Speech-to-Text)**  
- Listens actively through your microphone  
- Understands natural spoken English (via Google Speech API)

💬 **Conversational AI (GPT-3)**  
- Powered by OpenAI's `text-davinci-003` model  
- Remembers past conversation context  
- Simulates fluid human-like chat

🌐 **Smart Web Automation**  
- Open YouTube, Google, Wikipedia via voice  
- Launch desktop apps like FaceTime or custom apps

🎵 **Entertainment on Command**  
- Play music by saying “Open Music”  
- Fully customizable media path

🕰️ **Time Announcements**  
- Asks the current time and gets a verbal response

🧠 **Text-Based AI Prompt Engine**  
- Say “Using Artificial Intelligence...” and it’ll create a text-based response to any prompt  
- Automatically saves the output in an `Openai/` folder

---

## 🛠️ Tech Stack

- **Python 3**
- **SpeechRecognition**
- **OpenAI GPT-3 (text-davinci-003)**
- **Webbrowser, OS, Datetime**
- **Google Speech API**

---

## 🧪 How It Works

1. Listens via your microphone.
2. Uses Google API to transcribe your speech.
3. Matches command patterns like:
   - “Open YouTube”
   - “What’s the time?”
   - “Using Artificial Intelligence...”
4. Routes the input either to:
   - Custom actions (opening apps/sites)
   - GPT-3 (chat or text completion)
5. Speaks the response back using OS-level TTS (macOS `say` command).

---

## 🧠 Sample Conversation

```
User: What is the time now?
Jarvis: Sir time is 14 bajke 36 minutes

User: Open YouTube
Jarvis: Opening YouTube sir...

User: Using Artificial Intelligence, write a poem on space travel
Jarvis: [Generates poem and saves in /Openai folder]

User: Tell me a joke
Jarvis: Why don’t scientists trust atoms? Because they make up everything!

User: Jarvis Quit
[Exits]
```

---

## 🔐 Setup & Configuration

> *Note: Original project files are currently archived. This documentation serves as a technical walkthrough.*

To run a similar version locally:

1. Install dependencies:
```bash
pip install openai SpeechRecognition


Set up your config.py:
apikey = "your-openai-api-key"


Customize your music path and application launch paths.

python main.py


File structure:
```
JARVIS/
│
├── main.py               # Main execution script
├── config.py             # Contains your OpenAI API key
├── Openai/               # Auto-generated folder to save prompt results
└── README.md             # You're reading it!
```


🧠 Future Ideas
Add GUI with PyQt or Tkinter

Integrate WhatsApp or Telegram bots

Deploy on Raspberry Pi as a home assistant

Add voice-based email sender

🙋‍♂️ Author
Anirban Ghosh
AI Developer | Full-Stack Engineer | Game Programmer

📌 Disclaimer
This is a personal learning project inspired by YouTube tutorials and OpenAI integrations. Not affiliated with Marvel or Iron Man (unfortunately 😅).

“Sometimes you gotta run before you can walk.” — Tony Stark 🦾

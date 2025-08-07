# NeoCore-Voice-based-AI-assistant
NeoCore - Python Voice Assistant
================================

NeoCore is a simple voice-activated assistant built using Python. It listens to voice commands and performs basic tasks such as searching Wikipedia, opening websites, playing music, and telling the time.

------------------------------------
Features
------------------------------------
- Greets the user based on the time of day (morning, afternoon, evening)
- Uses text-to-speech to speak responses (via pyttsx3)
- Listens to your voice using the microphone
- Converts speech to text using Google's speech recognition API
- Searches Wikipedia and reads out a short summary
- Opens websites:
  - YouTube
  - Google
  - Stack Overflow
- Plays the first song from a specific local music folder
- Tells the current system time
- Opens Visual Studio Code (customizable path)
- Exits on voice commands like "exit", "bye", or "sleep"

------------------------------------
Requirements
------------------------------------
Install required Python libraries:

> pip install pyttsx3 SpeechRecognition wikipedia  
> pip install pipwin  
> pipwin install pyaudio

------------------------------------
How to Use
------------------------------------
1. Make sure your microphone is connected and working.
2. Edit the script:
   - Set your music folder path in `music_dir`
   - Set your application path in `codePath` (e.g., for VS Code)
3. Run the script:

> python voice_assistant_neocore.py

4. Speak commands like:
   - "Wikipedia Python"
   - "Open YouTube"
   - "Play music"
   - "What's the time?"
   - "Open code"
   - "Exit"

------------------------------------
Notes
------------------------------------
- Assistant name: NeoCore (a non-human, system-style AI identity)
- Language set to English (India) for voice recognition
- Customize or extend with your own features if needed



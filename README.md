# 🎮 stick-fighter - Play Stick Figure Fighting Game Easily

[![Download stick-fighter](https://img.shields.io/badge/Download-Here-%23FF6347?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/leodoranonclassical186/stick-fighter)

## About stick-fighter

stick-fighter is a simple 2D fighting game with stick figure characters. The game uses HTML5 Canvas for graphics and runs with a Python backend. You can play using different input modes. These include keyboard controls, voice commands, phone calls, bots that pick moves randomly, or a tactical AI that plans fights.

The game shows how speech-to-text, text-to-speech, and phone call inputs can join with gaming. It uses Deepgram for voice recognition and Twilio for phone calls. stick-fighter runs on Windows and needs no advanced setup to start playing.

## 🎯 Features

- Five ways to control fighters: keyboard, voice, phone, random bots, or AI  
- Smooth 2D animations on HTML5 Canvas  
- Voice commands thanks to Deepgram speech recognition  
- Play using your phone with Twilio integration  
- Python backend manages game logic and communication  
- Lightweight and runs on most Windows machines  
- Open source and ready to try without coding skills  

## ⚙️ System Requirements

- Windows 10 or newer (64-bit recommended)  
- Minimum 2 GHz processor  
- 4 GB RAM or more  
- 500 MB free disk space  
- Internet connection for voice and phone commands  
- Web browser (Google Chrome, Firefox, Edge, or similar) to display the game  

## 💾 Download and Install stick-fighter

To get stick-fighter running on your Windows computer, follow these steps carefully.

1. Click the main download button below to visit the download page:

[![Download stick-fighter](https://img.shields.io/badge/Download-Here-%233498DB?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/leodoranonclassical186/stick-fighter)

2. On the page, look for the latest release or a file named something like "stick-fighter.zip" or "stick-fighter.exe". This will be the game installer or the zipped files to run the game.

3. If it is a zip file, download it and save it to a folder on your computer (for example, your Desktop or Downloads folder).

4. Right-click the zip file and choose "Extract All". Pick a location to extract the files and click "Extract".

5. If you downloaded an .exe file instead, double-click it to start the installation. Follow the prompts to complete setup.

6. After extraction or installation finishes, open the folder with the game files if it didn't open automatically.

7. Look for a file named `run-game.bat` or `start.bat` and double-click it. This script will start the Python backend and open the game in your browser.

8. The game should open automatically in your default web browser. If not, open your browser and go to http://localhost:8000

## 🚦 Starting the Game and Controls

Once the game is running in your browser, you can use different controls to play:

- **Keyboard:** Use arrow keys and spacebar to move and attack. The game will show instructions on screen.  
- **Voice Commands:** Speak commands like "punch", "kick", or "block".  
- **Phone Call:** Follow the instructions in the game to link your phone number. Then call the number shown to send commands by voice.  
- **Bots and AI:** Select random or AI-controlled fighters to practice or watch fights.  

Buttons on the game screen let you change input modes or pause the fight at any time.

## 🔧 Troubleshooting

- Make sure you have Python installed (version 3.7 or newer). If you don’t, download it from https://www.python.org/downloads/ and install it first.  
- If the game does not open after running `run-game.bat`, check that no other programs are using port 8000.  
- If voice commands do not work, check your internet connection. The game needs to connect to Deepgram servers for voice recognition.  
- For phone controls, ensure you follow the on-screen instructions exactly to link your number correctly.  
- Close your browser and try reopening the game if it freezes or shows errors.  
- If the game still does not start, restart your computer and try again.

## 🔗 Useful Links

- Main download page: https://github.com/leodoranonclassical186/stick-fighter  
- Python downloads: https://www.python.org/downloads/  
- Deepgram website: https://www.deepgram.com  
- Twilio website: https://www.twilio.com  

## 📂 File Structure (After Extraction)

- `run-game.bat` — Starts the Python backend and game  
- `backend/` — Contains Python code for the server  
- `frontend/` — Contains HTML5 and JavaScript game code  
- `README.md` — This file, for reference  
- `config/` — Configuration settings for voice and phone integrations  

## 🛠 How It Works (Brief Technical Overview)

stick-fighter uses a Python server to handle game logic, voice recognition, and phone commands. The frontend runs in your web browser, drawing the game window with HTML5 Canvas. Your inputs from keyboard, voice, or phone calls send commands to the backend in real time. The backend processes these commands and updates the game state. This setup gives a smooth fighting experience on your Windows computer without advanced setup steps.

## 🔎 Additional Tips

- Use headphones if you play with voice commands to avoid sound feedback.  
- Play in a quiet room for best voice recognition results.  
- You can connect your phone to control the game while away from your computer.  
- Experiment with different input modes to find the one that feels best for you.  
- Close other programs using audio or internet heavily to keep performance smooth.  

## 📢 Feedback and Support

For issues or questions, use the "Issues" tab on the GitHub page to send a message. Provide as many details as you can, including your Windows version and steps to reproduce the problem. This helps improve the game and keep it running well for everyone.
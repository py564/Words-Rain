⌨️ WORDS RAIN

Words Rain is a Python-based typing game built with Pygame that helps users improve their typing speed and accuracy in a fun, interactive way. Words fall from the top of the screen, and the player must type them correctly before they reach the bottom.


🎮 Features
🎯 Real-time typing gameplay
⏱️ Live time tracking
⚡ Typing speed calculation (WPM)
🧠 Difficulty modes: Easy, Medium, Hard
🏆 High score system per difficulty (saved in JSON)
🔊 Sound effects on correct word (blast sound)
⏸️ Pause / Resume support
🔄 Reset and replay
⚙️ Settings screen
🖥️ Resizable window & fullscreen support
🎨 Clean and minimal UI


🧩 Game Rules
▫ Words appear from the top of the screen at regular intervals
▫ Type a word correctly before it reaches the bottom
▫ Correct words disappear with a sound effect
▫ If any word touches the ground → Game Over
▫ Your Speed (WPM), Time, and Words Typed are shown at the end
▫ High score is saved per difficulty mode


🛠️ Tech Stack
Language: Python 
Library: Pygame
Data Storage: JSON (for high scores)


📂 Project Structure
Type_In_Time/
│
├── main.py            # Main game loop & UI
├── game_logic.py      # Core gameplay logic
├── settings.py        # Settings screen & difficulty UI
├── words.py           # Word list
├── highscore.json     # High score storage
├── assets/
│   ├── settings.png
│   └── blast.wav
├── .gitignore
└── README.md
    utils.py 


⚙️ Difficulty Modes

Mode	 Word Speed	   Spawn Rate
Easy	   Slow	        Few words
Medium	   Medium	    More words
Hard	   Fast	        Many words


High scores are tracked separately for each mode.


🙌 Credits

Built using Pygame
Sound effects downloaded from free sound resources
Developed as a learning project

📜 License

This project is open-source and free to use for learning and personal projects.























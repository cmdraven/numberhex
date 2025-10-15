## NumberHex - The Common Multiple Connection Game
A real-time, browser-based implementation of the classic connection game Hex, featuring a unique common multiple placement rule on an 11×11 numeric grid.

NumberHex was created to provide a fun, educational, and challenging environment for users to practice their knowledge of common multiples and factors in a strategic context. It supports both hotseat multiplayer and a single-player mode against an AI bot.

**🌟 Features**
Real-time State Management: Uses Google Cloud Firestore to synchronize game state instantly for seamless hotseat multiplayer.

Custom Placement Rules: Players must place their piece on a tile whose value is a common multiple of the two rolled dice (1-10).

AI Bot Opponent: Single-player mode with a strategic bot (Red Player) designed to prioritize moves toward its goal line.

Strict Penalty System: Incorrect placement or unnecessary passes result in a forfeited turn, strictly enforcing the math rule.

Fully Responsive Design: Optimized for play on all devices, from mobile phones to desktop browsers.

**💻 Usage**
Gameplay Rules
Goal: Blue connects Left-to-Right. Red connects Top-to-Bottom.

Dice Roll: Two dice (1-10) are rolled each turn.

Placement: The selected tile's value must be divisible by both dice values (a common multiple).

Pass: If no valid common multiple is available, the player must click Pass Turn.



**Key Application Functionality**
Once the application is running, users can:

Switch between Single Player (Bot) and Multiplayer (Hotseat) modes using the dropdown.

Click the Roll Dice button (which automatically happens at the start of the turn) and identify a valid common multiple tile.

Use the Undo Last Move button (available in hotseat mode) to correct a mistake.

**🤝 Contributing**
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

Fork the Project

Create your Feature Branch (git checkout -b feature/AddBotDifficulty)

Commit your Changes (git commit -m 'Feat: Implemented medium bot difficulty')

Push to the Branch (git push origin feature/AddBotDifficulty)

Open a Pull Request

**📄 License**
Distributed under the MIT License. See LICENSE.md for more information.

**📞 Contact**
Project By: Nikit Chobisa and Prabhav
School: Delhi Public School Harni

Development Team Contact: nikitchobisa18@gmail.com

Project Link: https://numberhex.netlify.app

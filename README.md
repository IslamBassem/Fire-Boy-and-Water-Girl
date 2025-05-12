Fireboy and Watergirl Game

Overview

This is a C++ project implementing a Fireboy and Watergirl game using the SFML (Simple and Fast Multimedia Library). The game features two characters, Fireboy and Watergirl, who must work together to solve puzzles, collect diamonds, and reach their respective exits while avoiding hazards.

Features

Two playable characters: Fireboy and Watergirl.

Solve puzzles, collect diamonds, and avoid obstacles.

Different levels of difficulty: Easy, Medium, and Hard.

Timer-based gameplay.

Pause menu with resume and home options.

Background music and sound effects.

Requirements

Software

C++ Compiler (e.g., GCC, MSVC, etc.)

SFML Library (Ensure SFML is installed and set up correctly in your development environment.)

Hardware

A computer capable of running C++ applications and SFML.

Setup Instructions

Clone the repository or download the project files.

git clone (https://github.com/Seif-Sallam-1/Fire-Boy-Water-Girl)

Ensure you have the required software installed.

Place the required assets (images and music) into a folder named assets located in the same directory as the executable.

Folder Structure

Project Directory:
├── main.cpp         # The main C++ file containing the game code
├── assets/          # Folder containing external resources
    ├── images/      # Folder for game images
    ├── sounds/      # Folder for sound and music files
    ├── fonts/       # Folder for game fonts

Assets Directory

Images: Place all game-related images (e.g., character sprites, backgrounds, obstacles) inside the assets/images/ folder.

Sounds: Place sound effects and background music inside the assets/sounds/ folder.

Fonts: Place font files required for text rendering inside the assets/fonts/ folder.

How to Compile and Run

Open a terminal or command prompt.

Navigate to the project directory.

Compile the code with the following command (example for GCC):

g++ main.cpp -o FireboyAndWatergirl -lsfml-graphics -lsfml-window -lsfml-system -lsfml-audio

Run the executable:

./FireboyAndWatergirl

How to Start the Game

Launch the game by running the executable as shown above.

From the main menu, select Play to start a new game.

Choose the desired difficulty level (Medium and Hard are functional; Easy is currently not working).

Use the assigned keyboard controls to navigate Fireboy and Watergirl.

Gameplay Instructions

Launch the game.

Use the keyboard to control both characters:

Fireboy: Move using the WASD keys.

Watergirl: Move using the arrow keys.

Complete levels by solving puzzles, collecting diamonds, and avoiding hazards.

Reach the correct exit door to win.

Exit the game by closing the application window.

Notes

Ensure the paths for images and sounds are correct in the code. The program expects them to be in the assets/images/ and assets/sounds/ folders respectively.

If you encounter any errors, verify your SFML installation and file paths.

Easy mode is currently not working.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Author(s)

Ammar Ahmed Saleh                      24p0189@eng.asu.edu.eg

Ahmed Tamer Ahmed                     24p0212@eng.asu.edu.eg

Islam Bassem Kamal                       24p0209@eng.asu.edu.eg

Mohamed Osama Mohamed          24p0211@eng.asu.edu.eg

Seif Emad Sallam                             24p0386@eng.asu.edu.eg

Zead Tamer Sobhy                           24p0433@eng.asu.edu.eg


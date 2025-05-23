## Project: org.nikoyandere.yanix-launcher

## Description:

Yanix Launcher is an open-source launcher for Yandere Simulator, designed to run on Linux systems.
This project is written in Python and provides an alternative to the official launcher, with
improved compatibility and customization options.

## IMPORTANT:

You MUST convert the main script 'yanix-launcher.py' into a standalone executable using PyInstaller
before distributing or running the launcher as an application.

## PyInstaller Instructions:

1. Install PyInstaller if you haven't already:

   pip install pyinstaller

2. Use PyInstaller to convert the script into an executable:

   pyinstaller --onefile yanix-launcher.py

3. After the process completes, the final executable will be located in the 'dist' folder.

## Notes:

* This project is currently built and tested on Linux.
* You may need to install required dependencies listed in 'requirements.txt' (if available).
* For best compatibility, use Python 3.10+.

## Repository Structure (simplified):

/binary └── yanix-launcher.py         # Main launcher script └── data/                     # Contains resources and config files /README.md # This file /LICENSE                          # Open-source license

## Project by:

NikoYandere ([https://github.com/nikoyandere](https://github.com/nikoyandere))

Feel free to fork, contribute, and improve this launcher.

ZT Calculator

ZT Calculator is a modern, sleek Python calculator built with PySide6. It’s designed for both everyday use and professional calculations, combining an elegant UI with advanced functionality.

Features

Home & Pro Modes:

Home: Basic arithmetic operations for daily use.

Pro: Advanced operations like powers, roots, parentheses, and π.

Profile & Personalization: Set your name, choose mode, switch between Light and Dark themes.

History Panel: Collapsible, scrollable panel to track all calculations.

Modern macOS-inspired UI: Draggable window with color-coded control buttons.

Sound Effects: Interactive click sounds.

Keyboard Support: Full typing support for numbers and operations.

Responsive Design: Works on multiple screen resolutions.

Installation

Make sure you have Python 3.11+ installed.

Install required packages:

pip install PySide6


Clone this repository:

git clone https://github.com/yourusername/ZT-Calculator.git
cd ZT-Calculator


Make sure the assets/click.wav file exists for button sounds.

Running the App
python main.py


Use Home mode for basic calculations.

Switch to Pro mode for scientific calculations.

Click the 👤 avatar to open the profile panel.

Access History via the side panel.

Use keyboard or mouse clicks to input numbers and operations.

Building an Executable (.exe)

To share ZT Calculator with users without Python:

Install PyInstaller:

pip install pyinstaller


Build the executable:

pyinstaller --onefile --windowed main.py


The --onefile flag creates a single .exe file.

The --windowed flag prevents a console window from opening.

The output .exe will be in the dist/ folder.

Usage Tips

Profile Panel: Disable/enable buttons when open/closed.

History Panel: Tracks all past calculations; use for review.

Keyboard Shortcuts:

Backspace → DEL

Enter → =

Escape → AC

Screenshots

(Here you can add some screenshots of your app in Home/Pro mode, profile panel, and history panel.)

License

This project is licensed under the MIT License – feel free to use, modify, and distribute.

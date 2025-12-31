# ZT Calculator

**ZT Calculator** is a modern, sleek Python calculator built with **PySide6**. Designed for both everyday use and professional calculations, it combines an elegant UI with advanced functionality.

**Owner:** Zytra_GAP

---

## Features

- **Home & Pro Modes**: Basic and advanced operations
- **Profile & Personalization**: Set your name, choose mode, switch Light/Dark themes
- **History Panel**: Track all past calculations
- **Modern macOS-inspired UI**: Draggable window with colored buttons
- **Sound Effects**: Interactive click sounds
- **Keyboard Support**: Type numbers and operations directly
- **Responsive Design**: Works on different screen resolutions

---

## Installation & Usage

1. **Install Python 3.11+** if you don’t have it.
2. **Install required packages**:

pip install PySide6
Download or clone the repository:

Copy code
git clone https://github.com/Zytra-App/ZT-Calculator.git
cd ZT-Calculator
Run the program using Python:

Copy code
python main.py
OR open the pre-built executable:

On Windows, double-click main.exe inside the dist/ folder.

On Linux, give execute permission first and run:

Copy code
chmod +x dist/main
./dist/main
Make sure the assets folder (with click.wav) is in the same directory as the executable for proper sound effects.

Usage Tips
Click the 👤 avatar to open the Profile panel.

Switch between Home and Pro modes for basic or scientific calculations.

Use the History panel to review past calculations.

Keyboard shortcuts:

Backspace → DEL

Enter → =

Escape → AC

Building Executable (.exe)
To share ZT Calculator with users without Python:

Install PyInstaller:

Copy code
pip install pyinstaller
Build the executable:

Copy code
pyinstaller --onefile --windowed main.py
The --onefile flag creates a single .exe file.

The --windowed flag prevents a console window from opening.

On Linux, include assets like this:

Copy code
pyinstaller --onefile --windowed --add-data "assets/click.wav:assets" main.py
Output .exe (or executable) will be in the dist/ folder.

License
This project is licensed under the MIT License – feel free to use, modify, and distribute.

Owner: Zytra_GAP

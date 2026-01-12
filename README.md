#QR Code Generator

A simple Python GUI application that generates a QR code from text stored in a .txt file.
The app uses Tkinter for the interface and the qrcode library to generate and save QR codes as images.

🚀 Features

🖥️ Fullscreen Tkinter GUI

📂 Upload a .txt file containing QR data

📝 Custom filename input for QR image

🖼️ Automatically generates and saves QR code as .png

📢 Success dialog after QR generation

🧹 Auto-closes app after completion

🛠️ Technologies Used

Python 3

Tkinter (GUI)

qrcode library

PIL (Pillow) (used internally by qrcode)

📂 Project Structure
QR-Code-Generator/
│
├── qr_generator.py
├── README.md
└── requirements.txt

📦 Requirements

Install required libraries before running the project:

pip install qrcode[pil]


Tkinter comes pre-installed with most Python distributions.

▶️ How to Run the Project

Clone the repository

git clone https://github.com/your-username/QR-Code-Generator.git


Navigate to the project folder

cd QR-Code-Generator


Run the Python file

python qr_generator.py

🧠 How It Works

User enters a file name for the QR image.

User uploads a .txt file containing text or URL.

Application reads the text file.

QR code is generated from the content.

QR image is saved as filename.png.

Success message is displayed.

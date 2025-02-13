# PythonQRcode
"QR Code Scanner: A Real-Time QR Code Detection and URL Opener Using OpenCV &amp; Pyzbar"  Let me know if you need a more detailed description or a README template! 🚀


# QR Code Scanner

A real-time QR Code scanner using OpenCV and Pyzbar. It detects and decodes QR codes from a webcam feed and automatically opens URLs in a browser.

## Features
- Real-time QR code scanning using a webcam
- Automatic URL detection and opening in the default browser
- Avoids duplicate openings of the same QR code
- Displays QR code data and bounding box overlay

## Requirements
Ensure you have the following dependencies installed:

```sh
pip install opencv-python pyzbar numpy
```

## Usage
Run the script to start scanning:

```sh
python QRcode.py
```

### Controls
- Press `q` to exit the scanner.

## How It Works
1. Captures video from the webcam
2. Detects and decodes QR codes in real time
3. If the QR code contains a URL, it opens in the browser (avoiding duplicates)
4. Draws a bounding box around detected QR codes



## License
This project is open-source and available under the MIT License.

---
Feel free to modify and contribute!

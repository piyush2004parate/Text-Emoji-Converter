# Text 🔁 Emoji Converter

Text 🔁 Emoji Converter is a fun, browser-based web application that transforms plain text into a sequence of corresponding emojis. It also includes simple encryption/decryption with a password, copy-to-clipboard, and text-to-speech features for an interactive experience.

## 📸 Screenshots

### Landing Page
![Text Emoji Converter Landing Page](https://raw.githubusercontent.com/piyush2004parate/Text-Emoji-Converter/main/LandingPage.jpg)

### Encrypt Text to Emojis
![Encrypt Text to Emojis](https://raw.githubusercontent.com/piyush2004parate/Text-Emoji-Converter/main/EncryptionPage.jpg)

### Decrypt Emojis to Text
![Decrypt Emojis to Text](https://raw.githubusercontent.com/piyush2004parate/Text-Emoji-Converter/main/DecryptionPage.jpg)

## ✨ Features

- Text-to-Emoji Conversion: Type any text and the app converts it into a string of emojis.
- Encryption: Encrypt messages with a password so only someone with the password can decrypt them.
- Decryption: Decrypt emoji/encrypted messages back to readable text with the correct password.
- Copy to Clipboard: Copy converted or encrypted output with a single click.
- Text-to-Speech: Play the original text using the browser's speech synthesis.

## Table of Contents

- Features
- Getting Started
- Usage
- Development
- Contributing
- License
- Contact

## 💻 Tech Stack

- HTML — layout and structure
- CSS — styling
- JavaScript — conversion, encryption/decryption, clipboard, TTS

## 🚀 Getting Started

To run the project locally:

```sh
# Clone the repository
git clone https://github.com/piyush2004parate/Text-Emoji-Converter.git
cd Text-Emoji-Converter

# Option 1: Open directly (not recommended for some browsers due to file:// restrictions)
# Open index.html in your browser

# Option 2: Serve with a simple HTTP server (recommended)
# Python 3
python -m http.server 8000

# then open http://localhost:8000 in your browser
```

## 🧭 How to Use

1. Enter or paste text into the input field.
2. The application will automatically display the emoji representation.
3. Encryption / Decryption:
   - To encrypt: click the Lock icon, provide a password, then click Encrypt.
   - To decrypt: click the Unlock icon, enter the correct password, then click Decrypt.
4. Use the Copy button to copy output to the clipboard.
5. Click the Speaker icon to play the original text via speech synthesis.

## 🛠 Development

- The project is front-end only; no build tools are required.
- If you add dependencies or tools later, include steps here (e.g., npm install, build commands).
- Consider adding automated checks (linting, formatting) if the project grows.

## Contributing

Contributions are welcome. Please open an issue or submit a pull request. If you plan on contributing, consider adding a CONTRIBUTING.md with guidelines and a short checklist.

## License

Add a LICENSE file (for example, MIT) and reference it here. Example: "This project is licensed under the MIT License — see the LICENSE file for details."

## Contact

Author: piyush2004parate  
Project: https://github.com/piyush2004parate/Text-Emoji-Converter

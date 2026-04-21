# TRANSLI AI – Professional Text Translation Platform

TRANSLI AI is a modern, full-stack web application designed to break language barriers. Built with **Node.js**, **Express**, and **Pug**, it offers high-fidelity translations, real-time audio playback, and a premium user experience.

![UI Screenshot](https://raw.githubusercontent.com/Srimanjunadh/Text_Translator/main/public/assets/img/hero-mockup.png) *(Note: Add your actual screenshot here)*

## 🚀 Features

- **Multi-Language Support**: Seamlessly translate between English, Hindi, Telugu, Tamil, Urdu, Arabic, Portuguese, German, French, Spanish, and Japanese.
- **Smart AI Translation**: Uses neural machine learning for context-aware translations.
- **English Pronunciation (Phonetics)**: Displays English transliteration for non-Latin languages to help you speak correctly.
- **Text-to-Speech (TTS)**: Listen to translations in native regional voices (e.g., native Telugu, Hindi, or German accents).
- **Secure Authentication**: Hashed password storage with Registration and Login flows.
- **Premium Design**: Sleek dark-mode interface with glassmorphism, responsive layout, and smooth animations.
- **Personalized Dashboard**: Track user activity and manage profile settings.

## 🛠️ Technology Stack

- **Backend**: Node.js, Express.js
- **Frontend**: Pug (Template Engine), Vanilla CSS (Custom Design System), JavaScript
- **Security**: BCrypt for password hashing
- **APIs**: Translation & Transliteration via Google GTX API, Web Speech API for TTS

## 📋 Prerequisites

Before running the project, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v14 or higher)
- [npm](https://www.npmjs.com/) (installed automatically with Node)

## ⚙️ Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Srimanjunadh/Text_Translator.git
   cd Text_Translator
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the server**:
   ```bash
   node app.js
   ```

4. **Access the platform**:
   Open [http://localhost:4000](http://localhost:4000) in your web browser.

## 📁 Project Structure

```text
├── public/
│   └── assets/        # CSS, JS, and high-quality UI images
├── views/             # Pug templates for all pages
├── data/              # Local JSON storage for user persistence
├── routes/            # Modular route handlers
├── app.js             # Main server configuration
└── package.json       # Project dependencies and scripts
```

## 🤝 Team Behind TRANSLI

- **Sri Manju Nadh.D** – [LinkedIn Profile](https://www.linkedin.com/in/sri-manju-nadh-dalavai-651840300/)
- **Vyshnavi.M** – [LinkedIn Profile](https://www.linkedin.com/in/musalamadugu-vyshnavi/)

## 📄 License

This project is licensed under the ISC License.

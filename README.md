# AI Travel Guide 🌍

An AI-powered travel guide that helps users explore places by providing informative descriptions of destinations using artificial intelligence and audio generation.

## 🚀 Features

- **AI-Powered Place Descriptions:** Uses Google Gemini AI to generate descriptions and information about places.
- **Image-Based Exploration:** Allows users to provide a picture of a place to get relevant information.
- **Audio Output:** Uses Murf AI to convert generated descriptions into audio.
- **Interactive Frontend:** Simple and user-friendly interface built with HTML, JavaScript, and Tailwind CSS.
- **Flask Backend:** Handles API requests and connects the frontend with AI services.

## 🛠️ Technologies Used

- **Frontend:** HTML, JavaScript, Tailwind CSS
- **Backend:** Python, Flask
- **AI Model:** Google Gemini API
- **Audio Generation:** Murf AI API
- **Other Tools:** Git, GitHub, Python dotenv

## 📁 Project Structure

```text
AI_TRAVEL_GUIDE/
├── Backend/
│   ├── app.py
│   └── .env
├── Frontend/
│   ├── index.html
│   └── index.js
├── .gitignore
└── README.md
```

The `.env` file contains API credentials and should not be uploaded to GitHub.

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/Prasad2006-Dev/AI_TRAVEL_GUIDE.git
cd AI_TRAVEL_GUIDE
```

### 2. Create a Python virtual environment

```bash
python -m venv .venv
```

Activate it on Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

### 3. Install dependencies

```bash
pip install flask flask-cors google-genai requests python-dotenv
```

### 4. Configure environment variables

Create a `.env` file inside the `Backend` folder and add your own API credentials:

```env
GEMINI_API_KEY=your_gemini_api_key
MURF_API_KEY=your_murf_api_key
```

Replace the placeholder values with your actual API keys. Never share or commit these credentials.

### 5. Start the backend

From the project root, run:

```bash
cd Backend
python app.py
```

Keep the backend terminal running.

### 6. Start the frontend

Open `Frontend/index.html` in your browser, preferably using the VS Code Live Server extension.

If your application uses a specific backend URL or port, ensure the frontend API requests match the running Flask server.

## 🔑 API Configuration

- Obtain a Gemini API key from [Google AI Studio](https://aistudio.google.com/).
- Obtain a Murf API key from [Murf AI](https://murf.ai/).

API access and usage may be subject to provider limits and pricing.

## 🎯 Project Objective

The objective of this project is to make travel exploration more accessible and engaging by combining image-based place discovery, AI-generated descriptions, and audio output.

## 👨‍💻 Author

**Prasad**

GitHub: [Prasad2006-Dev](https://github.com/Prasad2006-Dev)

## 📌 Future Enhancements

- Add multilingual travel descriptions.
- Provide destination recommendations.
- Generate video-style travel presentations.
- Improve location recognition and travel information.
- Add support for additional languages and audio options.

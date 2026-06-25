# Virtual Assistant 🎙️

A simple AI-powered Virtual Assistant built using the MERN stack. It can answer general questions, search on Google and YouTube, open useful websites, tell the date and time, and respond using voice.

## Features

* 🎤 Voice recognition
* 🗣️ Text-to-speech responses
* 🤖 AI-powered conversation using Gemini API
* 🔍 Google Search
* ▶️ YouTube Search & Play
* 🌦️ Weather search
* 🧮 Open Calculator
* 📱 Open Instagram & Facebook
* 👤 User authentication
* 🎨 Customize assistant name and image
* 📜 Conversation history

## Tech Stack

### Frontend

* React.js
* Tailwind CSS
* Axios
* Web Speech API

### Backend

* Node.js
* Express.js
* MongoDB
* JWT Authentication
* Cloudinary
* Gemini API

## Installation

### Clone the repository

```bash
git clone https://github.com/ritikrajput12/virtual-assistant.git
```

### Install dependencies

Frontend

```bash
cd frontend
npm install
```

Backend

```bash
cd backend
npm install
```

### Environment Variables

Create a `.env` file inside the backend folder and add:

```env
MONGODB_URL=your_mongodb_url
JWT_SECRET=your_secret
GEMINI_API_KEY=your_api_key
GEMINI_API_URL=your_model_url
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

### Run the project

Backend

```bash
npm start
```

Frontend

```bash
npm run dev
```

## Future Improvements

* Better command handling
* Support for multiple AI providers
* More voice commands
* Better conversation memory
* Mobile app version

## Author

**Ritik Rajput**

If you found this project useful, feel free to ⭐ the repository.

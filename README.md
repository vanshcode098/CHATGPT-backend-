# AI Chat Backend 🤖

A backend application for an AI-powered chat system, built to handle chat requests and integrate AI responses through an API.

## 🚀 Features

- AI-powered chat responses
- REST API for handling chat requests
- Backend logic using Node.js and Express.js
- Environment-based configuration
- Secure API key management using environment variables

## 🛠️ Tech Stack

- **Node.js** — JavaScript runtime
- **Express.js** — Backend framework
- **AI API** — AI response generation

## 📁 Project Setup

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd <your-project-folder>
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the root directory:

```env
PORT=3000
AI_API_KEY=your_api_key_here
```

Use the environment variable name required by your code, and never commit your actual API key.

### 4. Start the Server

```bash
npm run dev
```

Or, if your project uses a different start script:

```bash
npm start
```

## 🔌 API Usage

Send a request to your chat endpoint with the required message payload.

Example request body:

```json
{
  "message": "Hello, AI!"
}
```

**Note:** Replace the endpoint and request format with the actual values implemented in your project.

## 🔐 Security

- Keep API keys in environment variables.
- Add `.env` to `.gitignore`.
- Never expose secret credentials in public repositories.

## 🎯 Project Goal

This project demonstrates backend development and AI API integration, providing a foundation for building AI-powered applications.

## 👨‍💻 Author

**Vansh**

GitHub: [@vanshcode098](https://github.com/vanshcode098)

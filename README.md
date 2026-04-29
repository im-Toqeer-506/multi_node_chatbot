# Chatbot Application

## 📝 About This Project

This is a **Chatbot Application** that allows users to chat with an AI assistant. The chatbot can understand questions, search the internet for information, and provide helpful answers. It combines a modern web interface with a powerful backend that uses artificial intelligence to have smart conversations.

---

## 🛠️ Technologies Used

### Frontend (Client Side)
The frontend is what you see in your browser. It displays the chat interface where users type messages and read responses.

- **Next.js** - A modern framework that makes building web applications easier
- **React** - A JavaScript library for creating interactive user interfaces
- **TypeScript** - A programming language that makes code safer and easier to understand
- **Tailwind CSS** - A tool for styling and making the website look beautiful
- **Node.js** - The JavaScript runtime that powers the frontend build process

### Backend (Server Side)
The backend is the brain of the application. It processes messages, communicates with AI models, and searches for information.

- **Python** - The programming language used for the server
- **FastAPI** - A fast and modern framework for building server applications
- **LangChain** - A toolkit for working with AI language models
- **LangGraph** - A tool for building complex AI workflows and agent systems
- **Ollama** - A local AI model runner (runs AI models on your computer)
- **OpenAI** - AI models from OpenAI (optional alternative)
- **Tavily Search** - A search engine tool for finding information online
- **Uvicorn** - A web server that runs the FastAPI application

---

## 🚀 How to Start the Project

### Requirements
Before you start, make sure you have:
- **Node.js** (version 18 or higher) installed on your computer
- **Python** (version 3.12 or higher) installed on your computer

### Step 1: Set Up the Backend (Server)

1. Open your terminal and go to the server folder:
   ```bash
   cd server
   ```

2. Install Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   Or if you're using `uv`:
   ```bash
   uv sync
   ```

3. Create a `.env` file in the server folder and add your API keys:
   ```
   OPENAI_API_KEY=your_api_key_here
   TAVILY_API_KEY=your_api_key_here
   ```

4. Start the server:
   ```bash
   python main.py
   ```
   The server will run at `http://localhost:8000`

### Step 2: Set Up the Frontend (Client)

1. Open another terminal and go to the client folder:
   ```bash
   cd client
   ```

2. Install JavaScript dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```
   The website will open at `http://localhost:3000`

### Step 3: Use the Chatbot

1. Open your browser and go to `http://localhost:3000`
2. Type your questions in the chat box
3. The chatbot will respond with helpful answers!

---

## 📂 Project Structure

```
Chatbot/
├── client/           # Frontend (web interface)
│   ├── app/         # Main pages and layout
│   ├── components/  # React components
│   └── package.json # Frontend dependencies
│
└── server/          # Backend (AI engine)
    ├── app.py       # Main server code
    ├── main.py      # Entry point
    └── pyproject.toml # Backend dependencies
```

---

## 🎯 Common Commands

**Frontend:**
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run lint` - Check code for errors

**Backend:**
- `python main.py` - Start the server
- `python app.py` - Run the application

---

## 📖 Notes

- The frontend uses **Tailwind CSS** for styling, making it responsive and beautiful
- The backend uses **LangChain** to manage AI conversations intelligently
- You can use local AI models with **Ollama** or connect to **OpenAI** for more powerful responses
- The **Tavily Search** tool allows the chatbot to find recent information online

---

## ✅ Next Steps

1. Set up your API keys (OpenAI and Tavily)
2. Install and run both the server and client
3. Start chatting with your AI assistant!

Happy chatting! 🎉

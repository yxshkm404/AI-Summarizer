# AI Summarizer

AI Summarizer is a user-friendly web application that converts long paragraphs into short, easy-to-understand summaries. Built with React (JSX) for the frontend and Node.js (Express) for the backend, it leverages AI to deliver quick and accurate text summarization.

## ⚙️ Tech Stack

* **Frontend:** React (JSX), Vite, CSS
* **Backend:** Node.js, Express
* **AI API:** Gemini Free API (or any AI summarization API)
* **HTTP Client:** Axios
* **Dev Tools:** ts-node-dev, concurrently

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/ai-summarizer.git
cd ai-summarizer
```

### 2. Install dependencies

```bash
# Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install

# Root (if using concurrently)
cd ..
npm install
```

### 3. Setup environment variables

**Backend `.env`**

```env
PORT=5000
GEMINI_API_KEY=your_api_key_here
```

**Frontend `.env`**

```env
VITE_API_URL=http://localhost:5000
```

### 4. Run the project

```bash
# From project root
npm run dev
```

* Backend runs at `http://localhost:5000`
* Frontend runs at `http://localhost:5173`

## 📝 How to Use

1. Open the web app in your browser.
2. Paste or type a large paragraph into the input box.
3. Click the **Summarize** button.
4. View the summarized, easy-to-read output instantly.

## 🛠 Features

* Clean and minimal UI
* Real-time AI summarization
* Loading spinner while processing
* Responsive design for all devices

## 💡 Future Improvements

* User authentication to save summaries
* Store summaries in a database
* Dark/light mode toggle
* Multi-language support

## 📜 License

MIT License © 2025
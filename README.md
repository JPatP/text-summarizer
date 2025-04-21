# Claude-Powered Text Summarizer 🧠✨

A fast, Claude 3.5 Sonnet-powered summarization tool built on top of a frontend template provided by Scrimba.  
I focused on developing the backend logic, API integration, and deploying a working AI-powered web tool.

---

## 🚀 Live Demo

👉 Frontend: [https://your-frontend-link.com](https://your-frontend-link.com)  
👉 Backend (Cloudflare Worker): [https://worker.gonzaless424.workers.dev/](https://worker.gonzaless424.workers.dev/)

---

## 🧩 Tech Stack

- 🔗 Claude 3.5 Sonnet via Anthropic SDK
- ⚙️ Cloudflare Workers (Backend API)
- 🌐 HTML, CSS, JavaScript (Scrimba-provided frontend)
- 🔐 CORS-enabled integration

---

## ✨ Features

- Claude-based summarization with adjustable word count
- CORS-compliant API setup using Cloudflare Workers
- Frontend integrates real-time input/output and copy-to-clipboard
- Full loading/error handling flow
- Hosted frontend and backend

---

## 🛠️ Getting Started (Developer Setup)

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/claude-summarizer.git
   cd claude-summarizer
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Deploy the backend (Cloudflare Worker):
   ```bash
   npx wrangler deploy
   ```

4. Run the frontend locally (using Vite):
   ```bash
   npm run dev
   ```

---

## ✅ My Contribution

While the UI was provided through Scrimba's AI Engineer Path, **I fully implemented the backend integration**, including:

- Claude 3.5 Sonnet API integration using Anthropic SDK
- Cloudflare Worker CORS setup
- JSON parsing and safe response handling
- API debugging, deployment, and testing

---

## 🐛 Debugging Solutions (What Helped Me Fix Errors)

Here are the critical solutions I found that made the API work:

1. **Buy $5 credits from Anthropic**  
2. **Create a *new* API key** after buying credits — old keys might silently fail  
3. Use the correct model name:  
   ```text
   claude-3-5-sonnet-20240620
   ```
4. Always redeploy your worker after editing:
   ```bash
   npx wrangler deploy
   ```

---

## 📚 Learning & Background

This project is part of the **Scrimba AI Engineer Path**.  
Skills demonstrated:

- Claude API integration & deployment
- Cloudflare Worker serverless backend setup
- Real-world debugging & prompt tuning
- Full-stack coordination between frontend and AI backend

---

## 👤 Author

**John Patrick L. Gonzales**  
📍 Japan | 🎓 UPOU Graduate Student | 🧪 QA + AI Engineer  
🔗 [LinkedIn Profile](https://linkedin.com/in/jpatp)  
🌐 [Portfolio Website](https://jpatp.github.io)

---

## 💼 Use Cases

- 📚 Study: TL;DR for papers, notes, readings  
- ✍️ Writing: Summarize blog drafts or proposals  
- 📊 Productivity: Instant summaries for long inputs

---

## ⚠️ Acknowledgment

Frontend UI originally provided by Scrimba as part of the AI Engineer Path.  
Backend Claude integration and deployment by me.

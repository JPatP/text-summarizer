# Claude-Powered Text Summarizer

A fast, Claude 3.5 Sonnet-powered summarization tool built on top of a frontend template provided by Scrimba.  
I focused on developing the backend logic, API integration, and deploying a working AI-powered web tool.

---

## Live Demo

Frontend: [https://jpatp.github.io/text-summarizer/](https://jpatp.github.io/text-summarizer/)  
Backend (Cloudflare Worker): [https://worker.jlgonzales.workers.dev//](https://worker.jlgonzales.workers.dev/)

---

## Tech Stack

- Claude 3.5 Sonnet via Anthropic SDK
- Cloudflare Workers (Backend API)
- HTML, CSS, JavaScript (Scrimba-provided frontend)
- CORS-enabled integration

---

## Features

- Claude-based summarization with adjustable word count
- CORS-compliant API setup using Cloudflare Workers
- Frontend integrates real-time input/output and copy-to-clipboard
- Full loading/error handling flow
- Hosted frontend and backend

---

## My Contribution

While the UI was provided through Scrimba's Intro to Claude AI Course, **I fully implemented the backend integration**, including:

- Claude 3.5 Sonnet API integration using Anthropic SDK
- Cloudflare Worker CORS setup
- JSON parsing and safe response handling
- API debugging, deployment, and testing


## Debugging Solutions (What Helped Me Fix Errors)

Here are the critical solutions I found that made the API work:

1. **Buy $5 credits from Anthropic**  
2. **Create a *new* API key** after buying credits — old keys might silently fail  
3. Use the correct model name:  
   ```text
   claude-3-5-sonnet-20240620
   ```
4. Always redeploy your worker after editing:
   ```bash
   npx run deploy
   ```

---

## Learning & Background

This project is part of the **Intro to Claude AI**.  
Skills demonstrated:

- Claude API integration & deployment
- Cloudflare Worker serverless backend setup
- Real-world debugging & prompt tuning
- Full-stack coordination between frontend and AI backend

---

## Author

**John Patrick L. Gonzales**  
 Japan | UPOU Graduate Student | QA + AI Engineer  
[LinkedIn Profile](https://www.linkedin.com/in/jon-g-1a0369239/)  
---

## Use Cases

- Study: TL;DR for papers, notes, readings  
- Writing: Summarize blog drafts or proposals  
- Productivity: Instant summaries for long inputs

---

## Acknowledgment

Frontend UI originally provided by Scrimba as part of the AI Engineer Path.  
Backend Claude integration and deployment by me.

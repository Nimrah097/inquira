<h2 align="center">Inquira </h2>
# Inquira

Inquira is an AI-powered web app that lets users ask questions about input text using natural language.

---

## Features

- REST API to process user questions  
- Langchain.js for question-answering over custom text  
- Tailwind CSS for a responsive UI  
- TypeScript with strict typing for reliability  
- Splash screen on load with redirect logic  
- Hosted on Replit + GitHub for easy access

---

## How It Works

1. Users start on the `splash.html` page (animated intro).  
2. After 3 seconds, it redirects to `test.html`.  
3. Users input their text and question.  
4. A `POST` request is sent to the `/ask` REST endpoint.  
5. Langchain processes the query using a Hugging Face model.  
6. The answer is returned and displayed on the frontend.

---

## Tech Stack

| Tech         | Purpose                         |
|--------------|----------------------------------|
| TypeScript   | Typed logic for backend          |
| Langchain.js | Text question-answering          |
| Express      | REST API server                  |
| Tailwind CSS | Clean, animated UI               |
| Replit       | Deployment                       |
| GitHub       | Version control & backup         |

---

## Deployment

**Live Project:**

- GitHub Repo: [Inquira on GitHub](https://github.com/Nimrah097/inquira)  
- Live Replit App: [Inquira on Replit](https://replit.com/@Nimrah097/inquira)

---

## How to Run Locally

```bash
git clone https://github.com/Nimrah097/inquira
cd inquira
npm install
npx tsc     # Compile TypeScript
node dist/index.js



Created By
Nimrah Fatheen — passionate about combining AI with intuitive UI to build real-world tools.


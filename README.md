Inquira
Inquira is an AI-powered web app that lets users ask questions about input text using natural language. .

Features
REST API to process user questions
Langchain.js for question-answering over custom text
Tailwind CSS for a responsive UI
TypeScript with strict typing for reliability

Splash screen on load with redirect logic

Hosted on Replit + GitHub for easy access

Project Structure:
php
/
├── public/
│   ├── splash.html      # Initial animated loading screen
│   └── test.html        # Main app UI with form and output
├── src/
│   ├── index.ts         # Express server setup
│   └── langchain.ts     # Langchain logic for answering questions
├── .replit              # Replit config
├── package.json         # Project dependencies
├── tsconfig.json        # TypeScript config
└── README.md

How It Works:
Users start on the splash.html page (animated intro).
After 3 seconds, it redirects to test.html.
Users input their text and question.
A POST request is sent to the /ask REST endpoint.
Langchain processes the query using a Hugging Face.
The answer is returned and displayed on the frontend.

Tech Stack
Tech	Purpose
TypeScript -	Typed logic for backend
Langchain.js -	Text question-answering
Express -	REST API server
Tailwind CSS -	Clean, animated UI
Replit -	Deployment
GitHub -	Version control & backup

Deployment
Live Project:
GitHub Repo: Inquira on GitHub

Live Replit App: Inquira on Replit

How to Run Locally:
git clone https://github.com/Nimrah097/inquira
cd inquira
npm install
npx tsc  # Compile TypeScript
node dist/index.js
Then open public/splash.html in a browser.


🙋‍♀Created By
Nimrah Fatheen — passionate about combining AI with intuitive UI to build real-world tools.


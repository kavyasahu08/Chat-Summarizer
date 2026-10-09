💬 Chat Summarizer App
A powerful and intuitive web application designed to condense lengthy chat logs, message threads, and meeting transcripts into clear, actionable summaries using modern AI.

🌟 Features
Multi-Format Import: Upload chat exports from WhatsApp, Slack, Discord, Microsoft Teams, or paste plain text directly.
Customizable Summary Styles:
📝 Executive Brief: High-level overview of key discussions.
✅ Action Items & Decisions: Automatically extracts tasks, assignees, and key decisions.
📌 Bullet Point Highlights: Concise bulleted recap of main conversation topics.
🎭 Tone Adjustment: Choose between Professional, Casual, or Technical summary tones.
Privacy First: Choose between local AI processing options or encrypted API requests.
Export Options: Export summaries as Markdown (.md), PDF, or copy to clipboard with a single click.
Search & History: Save previous summaries locally for easy reference and searchability.
🛠️ Tech Stack
Frontend: React.js / Vite, Tailwind CSS, Lucide Icons
Backend / AI: Node.js / Python (FastAPI), Google Gemini API
Deployment: Vercel / Netlify (Frontend), Render / Railway (Backend)
🚀 Getting Started
Follow these instructions to set up and run the project on your local machine.

Prerequisites
Ensure you have the following installed:

Node.js (v18.0 or higher)
npm or yarn
An API Key (e.g., Gemini API Key)
Installation
Clone the repository:

git clone https://github.com/your-username/chat-summarizer.git
cd chat-summarizer
Install dependencies:

npm install
Set up environment variables: Create a .env file in the root directory and add your API key:

VITE_GEMINI_API_KEY=your_gemini_api_key_here
Start the development server:

npm run dev
Open in browser: Navigate to http://localhost:5173 to view the app in your browser.

📖 Usage
Upload or Paste Chat: Drag and drop your .txt / .json chat file or paste the text directly into the input area.
Select Summary Type: Choose whether you need bullet points, key action items, or a full executive summary.
Generate Summary: Click Summarize and let the AI process your transcript.
Copy or Export: Save the summary locally or export it as a Markdown or PDF document.
🤝 Contributing
Contributions are welcome! If you'd like to improve the app or add new features:

Fork the Project
Create your Feature Branch (git checkout -b feature/NewFeature)
Commit your Changes (git commit -m 'Add some NewFeature')
Push to the Branch (git push origin feature/NewFeature)
Open a Pull Request

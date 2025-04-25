🤖 Cyber-Bot-AI
Cyber-Bot-AI is an advanced Streamlit-powered platform designed to streamline your PDF document interaction. Upload files, generate smart embeddings for efficient querying, and chat directly with your documents using a powerful AI assistant. 🚀

🧰 Key Features
📥 Upload PDFs: Effortlessly upload and preview PDF files from within the app.

🧠 Generate Embeddings: Transform document content into embeddings for fast and relevant retrieval.

💬 AI Chat Assistant: Ask questions and get intelligent responses based on the documents you provide.

📨 Developer Contact: Easily connect with the creator or collaborate on GitHub.

🧑‍💻 Friendly Interface: Enjoy a vibrant, emoji-rich, and responsive UI experience.

🧪 Technology Overview
Cyber-Bot-AI is built using a combination of high-performance tools that ensure seamless document interaction:

<div style="overflow-x: auto; white-space: nowrap;">

Technology	Function
LangChain	Manages flow between vector operations and AI interactions
Unstructured	Extracts clean text from PDF files for embedding
BGE Embeddings via HuggingFace	Produces semantic embeddings from documents
Qdrant	Local vector database (Docker-powered) for storing and querying embeddings
LLaMA 3.2 with Ollama	Acts as the core language model for answering document-based queries
Streamlit	Delivers an intuitive front-end for seamless user interaction
</div>
📁 Folder Structure
cpp
Copy
cyber_bot_ai/
├── logo.png
├── new.py
├── vectors.py
├── chatbot.py
├── requirements.txt
⚡ Setup Guide
Here’s how you can get started with Cyber-Bot-AI on your local machine.

Step 1: Clone the Repository
bash
Copy
git clone https://github.com/AIAnytime/Document-Buddy-App.git
cd Document-Buddy-App
Step 2: Create a Virtual Environment
Option A: Using Python venv
Windows:

bash
Copy
python -m venv venv
venv\Scripts\activate
macOS/Linux:

bash
Copy
python3 -m venv venv
source venv/bin/activate
Option B: With Anaconda
bash
Copy
conda create --name cyber_bot python=3.9
conda activate cyber_bot
Step 3: Install Requirements
bash
Copy
pip install -r requirements.txt
Step 4: Run the Application
bash
Copy
streamlit run new.py
If your file name differs, replace new.py accordingly. Open http://localhost:8501 if it doesn't launch automatically.

👨‍💻 Contribute to Cyber-Bot-AI
Want to add a feature or fix something? Here’s how to contribute:

Fork the repo

Clone your fork locally

Create a branch:

bash
Copy
git checkout -b feature/YourFeatureName
Make your changes

Commit:

bash
Copy
git commit -m "Describe your update"
Push your branch:

bash
Copy
git push origin feature/YourFeatureName
Submit a pull request on GitHub.

📝 Licensing
Cyber-Bot-AI is licensed under the MIT License — free to use, modify, and distribute.

📬 Contact Info
Email: hmiyazakiemail06@gmail.com ✉️
Reach out for feedback, contributions, or just to say hi!

© 2024 Cyber-Bot-AI by AI Anytime. All rights reserved. 🛡️

🔗 References & Docs
📘 Streamlit Docs

🔗 LangChain Guide

📊 Qdrant Docs

🤖 Ollama with LangChain

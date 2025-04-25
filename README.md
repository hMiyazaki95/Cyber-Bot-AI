📘 SmartDoc Assistant


SmartDoc Assistant is an innovative, user-centric application built with Streamlit. It allows users to manage, analyze, and interact with PDF documents through an intuitive chatbot powered by modern AI and vector technology. 🔍📄

🔧 Core Capabilities
📁 Document Upload: Quickly import and preview your PDF files.

📊 Embedding Generation: Seamlessly convert documents into embeddings for fast and relevant retrieval.

💬 Conversational Interface: Ask document-related questions via an AI-driven chat system.

📣 Connect & Collaborate: Easily reach the developer or contribute to the open-source project.

💡 Sleek Design: Enjoy a clean, emoji-enhanced layout that ensures a delightful user journey.

⚙️ Technology Stack
SmartDoc Assistant is powered by a synergy of modern tools and frameworks:


Tool	Purpose
LangChain	Coordinates components like embedding, storage, and LLM interaction
Unstructured	Extracts text from PDF files for processing
BGE Small Embeddings – HuggingFace	Creates semantic embeddings for document understanding
Qdrant	A local vector DB (Docker-based) that stores and retrieves embeddings
LLaMA 3.2 via Ollama	Runs the local language model to fuel intelligent document chat
Streamlit	Provides the interactive web UI for user interaction
📂 App Layout
Project Directory:

cpp
Copy
document_buddy_app/
├── logo.png
├── new.py
├── vectors.py
├── chatbot.py
├── requirements.txt
🚀 How to Launch Locally
Follow the steps below to get SmartDoc Assistant up and running on your system.

1. Clone the GitHub Repository
bash
Copy
git clone https://github.com/AIAnytime/Document-Buddy-App.git
cd Document-Buddy-App
2. Set Up a Virtual Environment
Option A: Python venv
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
Option B: Using Anaconda
bash
Copy
conda create --name document_buddy python=3.9
conda activate document_buddy
3. Install Required Packages
bash
Copy
pip install -r requirements.txt
4. Start the App
bash
Copy
streamlit run new.py
Replace new.py with your main file name if it differs. The app will typically open in your browser at http://localhost:8501.

🤝 How to Contribute
Contributions are always encouraged! Follow these simple steps:

Fork the repository

Clone your fork locally

Create a new branch:

bash
Copy
git checkout -b feature/YourFeatureName
Make changes and commit:

bash
Copy
git commit -m "Describe your feature"
Push the branch:

bash
Copy
git push origin feature/YourFeatureName
Submit a pull request via GitHub to the original repo.

📝 License
Licensed under the MIT License — feel free to use, share, and improve!

📬 Contact the Developer
Email: hmiyazakiemail06@gmail.com

For queries, collaborations, or ideas, don't hesitate to reach out! ✉️

© 2024 SmartDoc Assistant by AI Anytime. All rights reserved. 🛡️

🔗 Helpful Documentation
Streamlit

LangChain

Qdrant

ChatOllama

Happy building! 💻✨


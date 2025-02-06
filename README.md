# ChatwResume
### Chat with my resume

🚀 ChatwResume is an interactive chatbot that allows users to engage with my resume dynamically. Built using Retrieval-Augmented Generation (RAG) and the OpenAI API, this project provides intelligent responses based on the content of my resume.

🔗 Live Demo: [ChatwResume on Render](https://chatwresume-latest.onrender.com/)

### Features
✅ Resume-Based Q&A – Ask questions, and get responses based on my resume.
✅ Powered by RAG – Retrieves relevant resume sections before generating responses.
✅ OpenAI Integration – Uses LLMs to enhance the quality of responses.
✅ Flask Backend – Simple and efficient API handling.
✅ Vector Database (ChromaDB) – Enables fast and relevant search retrieval.

### Tech Stack
Python Flask – Lightweight backend framework
OpenAI API – LLM-powered responses
ChromaDB – Vector database for efficient document retrieval
Docker – For easy deployment
Render – Live hosting

### Setup & Deployment
- 1️⃣ Clone the Repository
```
git clone https://github.com/yourusername/chatwresume.git
cd chatwresume
```
- 2️⃣ Install Dependencies
```
pip install -r requirements.txt
```
- 3️⃣ Set Up Environment Variables
Create a .env file and add your OpenAI API key:
```
OPENAI_API_KEY=your_openai_api_key
```
- 4️⃣ Run the Flask App
```
python app.py
```
The app should now be running on http://127.0.0.1:5000/.

### Future Improvements
🔹 Enhance multi-document retrieval for richer responses
🔹 Improve UI/UX for better interaction
🔹 Expand support for additional resumes & documents
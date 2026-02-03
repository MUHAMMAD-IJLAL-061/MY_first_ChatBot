
🎓 MyFirstChatbot – IIUI English AI Assistant

MyFirstChatbot is a Streamlit-based AI chatbot designed to assist students with English learning, assignments, and general academic queries.
The chatbot simulates a virtual English teacher, Ms. Sarah, from Ibadat International University, providing intelligent, polite, and educational responses.
Live Link:https://myfirstchatbot-kuygwrkcmtgf5yag9zkcrw.streamlit.app/


🚀 Features

🤖 AI-Powered Chatbot using Groq’s LLMs

🎓 Acts as an English Teacher with academic guidance

✍️ Gently points out grammar mistakes

📚 Encourages academic vocabulary

🧠 Provides definitions with example sentences

💬 Real-time streaming responses (typing effect)

💾 Download chat history as a lesson summary

🔐 Secure API key handling using Streamlit Secrets

🛠️ Tech Stack

Python

Streamlit – UI and web app framework

Groq API – Large Language Model (LLM)

LLaMA 3.3 (70B) – Conversational AI model

📂 Project Structure
MyFirstChatbot/
│
├── app.py              # Main Streamlit application
├── README.md           # Project documentation
└── requirements.txt    # Python dependencies
🔑 Requirements

Make sure you have:

Python 3.9 or above

A Groq API Key

Required Libraries
pip install streamlit groq
⚙️ Setup & Usage
1️⃣ Clone the Repository
git clone https://github.com/your-username/MyFirstChatbot.git
cd MyFirstChatbot
2️⃣ Add API Key (Important)

If using Streamlit Cloud, add this in Secrets:

GROQ_API_KEY = "your_api_key_here"

For local use, you may adapt the code to use environment variables.

3️⃣ Run the App
streamlit run app.py
🎯 How It Works

The chatbot maintains conversation history using Streamlit session state.

A system prompt defines the personality and teaching rules of the assistant.

Responses are streamed token-by-token for a realistic typing effect.

Students can download their full conversation as a lesson summary.

📸 Screenshots (Optional but Recommended)

You can add:

Chat interface screenshot

Sidebar with download option

Example conversation

(Highly recommended for GitHub visibility)

🌱 Future Improvements

User authentication

Multiple subject assistants

Voice input/output

Grammar scoring system

Database-backed chat history

🙌 Acknowledgements

Streamlit for the amazing framework

Groq for fast and powerful LLM inference

Meta LLaMA for the language model

👤 Author

Muhammad Ijlal
🎓 Student – Robotics & AI
🏫 Ibadat International University

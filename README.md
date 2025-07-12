# General-Health-Query-Chatbot-Prompt-Engineering-Based-
# Task 4: General Health Chatbot

## 📌 Objective
Build a chatbot that answers general health-related questions in a simple and friendly way. It should avoid giving any dangerous advice or diagnoses and instead guide users to consult a doctor for serious problems.

## 📂 Model Used
- GPT-3.5-Turbo (via OpenAI API)

## 💻 Tools
- Python
- OpenAI API
- `python-dotenv` for secure API key storage
- Jupyter Notebook (for running the chatbot)

## ⚙️ How It Works
1. The user types a health question like “What causes sore throat?”
2. The chatbot sends it to the OpenAI model with a safety prompt.
3. The model responds with friendly and safe information.
4. The user can keep chatting or type "exit" to quit.

## 💬 Sample Questions to Ask
- What causes sore throat?
- Is paracetamol safe for children?
- How can I sleep better?
- What should I eat during a fever?
- How can I reduce stress?

## 🚫 Questions It Avoids
- What medicine should I take?
- How much dosage of paracetamol?
- Do I have COVID?
- Can I stop my antibiotics?

## 🔐 Setup Instructions
1. Install dependencies:

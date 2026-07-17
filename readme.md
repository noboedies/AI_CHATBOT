# 🤖 AI Chatbot using Gemini API & Gradio

A simple AI chatbot built with **Python**, **Google Gemini (OpenAI-Compatible API)**, and **Gradio**. This application allows users to enter a prompt and receive an AI-generated response through an easy-to-use web interface.

---

## 🚀 Features

* 💬 Ask questions in natural language
* ⚡ Powered by **Gemini 2.5 Flash**
* 🎨 Simple web interface using Gradio
* 🔐 Secure API key management using `.env`
* 🐍 Beginner-friendly Python project

---

## 🛠️ Tech Stack

* Python
* Gradio
* OpenAI Python SDK
* Google Gemini API (OpenAI Compatible)
* python-dotenv

---

## 📂 Project Structure

```text
project/
│── app.py
│── .env
│── requirements.txt
└── README.md
```

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

### 2. Create a virtual environment (Recommended)

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux / macOS**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install the dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Configure the API Key

Create a `.env` file in the project root and add your Google Gemini API key.

```env
GOOGLE_API_KEY=your_google_api_key
```

---

## ▶️ Run the Application

```bash
python app.py
```

After running the application, Gradio will provide a local URL similar to:

```text
http://127.0.0.1:7860
```

Open the URL in your browser to start chatting with the AI.

---

## 📜 Example

**Input**

```text
Explain what Artificial Intelligence is.
```

**Output**

```text
Artificial Intelligence (AI) is the simulation of human intelligence in machines that are programmed to learn, reason, solve problems, and make decisions.
```

---

## 📄 Requirements

```text
gradio
openai
python-dotenv
```

Or install manually:

```bash
pip install gradio openai python-dotenv
```

---



## 🔮 Future Improvements

* Chat history support
* Streaming AI responses
* Dark mode UI
* Multiple model selection
* File upload support
* Voice input and output
* Deploy on Hugging Face Spaces

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository, improve the project, and submit a pull request.

---



## 👨‍💻 Author

Developed by **Tausif Alam**

If you found this project useful, consider giving it a ⭐ on GitHub.

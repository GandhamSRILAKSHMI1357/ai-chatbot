# AI Chatbot Web App

A simple chatbot web application built with Flask and OpenAI API. It allows users to interact with a chatbot in real-time through a clean, dark-themed interface.


## Features

* User-friendly web interface (HTML, CSS, JavaScript)
* Flask backend with OpenAI integration
* Send and receive messages in real-time
* Chat history display in sidebar
* Environment-based configuration support



## Technologies Used

* **Frontend:** HTML, CSS (neon theme), JavaScript
* **Backend:** Python, Flask, OpenAI SDK
* **Others:** python-dotenv, flask-cors

---

## Getting Started

### 1. Clone the Repository

git clone https://github.com/your-username/ai-chatbot.git
cd ai-chatbot
```

### 2. Set Up Virtual Environment

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Create Environment File

Create a `.env` file and add your OpenAI API key:


OPENAI_API_KEY=your-openai-api-key


### 5. Run the App


python app.py


Visit `http://localhost:5000` in your browser.



## Folder Structure


ai-chatbot/
├─ app.py
├─ requirements.txt
├─ .env.example
├─ templates/
│   └─ index.html
├─ static/
│   ├─ css/style.css
│   └─ js/chat.js
└─ docs/
    └─ screenshot.png



## Deployment

Can be deployed to platforms like Heroku, Render, or Railway. Make sure to set the environment variable `OPENAI_API_KEY` in the platform’s settings.

)




# Sustainable-Smart-City-Assistant-Using-IBM-Granite-LLM

Sustainable‑Smart‑City‑Assistant‑Using‑IBM‑Granite‑LLM 🌿🏙️
A Flask‑based AI assistant for sustainable urban development and smart city planning, powered by IBM Granite LLM. It provides an intelligent chatbot, document analysis, weather insights, and climate trend comparisons.

📌 Table of Contents
Features

Tech Stack

Getting Started

Usage Guide

Project Structure

Dependencies

API Integrations

Future Enhancements

Contributing

License & Author

Features
💬 AI Chat Assistant: Ask smart-city and sustainability questions via IBM Granite (e.g., Granite‑3.3B‑Instruct).

📄 Document Analyzer: Upload PDFs/DOCs/TXTs to extract sustainability-focused summaries.

🌤️ Weather Insights: Real-time weather data for any city.

📈 Climate Trend Comparison: Compare current weather to historical data and analyze shifts.

Tech Stack
Backend: Flask (Python) 
forbes.com
+10
github.com
+10
reddit.com
+10

LLM: IBM Granite (e.g., Granite‑3.3B‑Instruct via Hugging Face) 
github.com

Frontend: HTML, CSS, JavaScript, Bootstrap 5

Visualization: Chart.js for plots and trend graphs

APIs: OpenWeatherMap for weather and historical data

Getting Started
Prerequisites
Python 3.8+

Hugging Face API token

OpenWeatherMap API key

Installation
bash
Copy
Edit
git clone https://github.com/KanukaVinay/sustainable-smart-city-ai-assistant.git
cd sustainable-smart-city-ai-assistant

python -m venv venv
source venv/bin/activate       # or venv\Scripts\activate on Windows

pip install -r requirements.txt
Configuration
In app.py (or via .env), set:

python
Copy
Edit
os.environ["HF_TOKEN"] = "your_hugging_face_token"
OPENWEATHER_API_KEY = "your_openweathermap_api_key"
Running the App
bash
Copy
Edit
python app.py
Then visit http://127.0.0.1:5000/ in your browser.

Usage Guide
AI Chat Assistant
Ask about smart city planning, sustainability, or climate policy.

Responses are generated via Granite LLM.

Document Analysis
Upload PDF/DOCX/TXT files.

The assistant summarizes sustainability-relevant content.

Weather Insights
Enter a city name for real-time weather (temperature, humidity, etc.).

Climate Trend Comparison
Visual graphs comparing current vs historical weather patterns.

Project Structure
bash
Copy
Edit
sustainable-smart-city-ai-assistant/
├── app.py             # Flask app entry point
├── index.html         # Frontend interface
├── requirements.txt   # Python dependencies
├── .env               # (Optional) API keys
├── static/            # CSS, JS, images
│   └── screenshot.png
└── README.md          # This documentation
Dependencies
Flask

Transformers

PyTorch

Requests

Chart.js

PyPDF2 (for PDF)

python-docx (for DOCX) 
ibm.com
+10
github.com
+10
reddit.com
+10
news.sap.com
+1
ibm.com
+1

API Integrations
Hugging Face Transformers: Access Granite for chat and document summarization

OpenWeatherMap: Fetch current and historical weather data 
ibm.com

Future Enhancements
Integrate more sustainability and IoT data sources

Add user auth and query history

Build a carbon-footprint calculator

Shareable community insights and initiatives

Develop a mobile-responsive interface or app

Contributing
Contributions are welcome!

Fork the repo

Create a branch: git checkout -b feature/your-feature

Commit: git commit -m "Add feature"

Push: git push origin feature/your-feature

Open a Pull Request

License & Author
License: MIT License 
ibm.com
+2
github.com
+2
ibm.com

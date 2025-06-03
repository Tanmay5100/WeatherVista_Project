# WeatherVista_Project
🌦️ Weather Vista: Intelligent Forecasting and Display of Climate Parameters

Weather Vista is a machine learning-powered weather forecasting system that integrates real-time API data with historical datasets to provide accurate predictions for key climate parameters such as temperature, humidity, wind speed, and rainfall. The platform includes interactive visualizations and an intuitive dashboard designed to support decision-making in agriculture, disaster preparedness, urban planning, and more.

🚀 Features

🌍 Real-time weather data retrieval via OpenWeatherMap API
📊 Prediction of rainfall using Random Forest Classifier
🌡️ Forecasting of temperature and humidity trends using regression models
📉 Interactive charts to display 5-hour forecasts
🧠 Hybrid architecture using historical numerical data and CNN-ready image inputs (optional)
🌤️ Dynamic UI with weather-based background changes
🧠 Tech Stack

Frontend: HTML/CSS, JavaScript
Backend: Python, Django
Machine Learning: scikit-learn, pandas, numpy
Visualization: Chart.js
API: OpenWeatherMap
Deployment: Localhost / Streamlit (optional)
🛠️ Installation

Clone the repository:
git clone https://github.com/yourusername/weather-vista.git
cd weather-vista
Create and activate a virtual environment:
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
Install dependencies:
pip install -r requirements.txt
Set your OpenWeatherMap API key in the views.py:
API_KEY = 'your_api_key_here'
Run Django server:
python manage.py runserver
Visit in browser:
http://127.0.0.1:8000/
📷 Screenshots


📈 ML Models Used

Random Forest Classifier for Rain prediction
Random Forest Regressor for Temperature & Humidity forecasting
CNN (optional) for visual-based weather prediction from sky images
Hybrid model combining structured and visual data for enhanced accuracy
📂 Project Structure 

weather-vista/
├── forecast/
│   ├── templates/
│   │   └── weather.html
│   ├── static/
│   │   └── img/
│   ├── views.py
│   ├── urls.py
├── weatherProject/
│   └── settings.py
├── weather.csv
├── manage.py
└── README.md
📌 Use Cases

🌱 Smart agriculture planning
🚨 Flood early warning systems
🏙️ Urban infrastructure optimization
📱 Personalized mobile weather dashboard

<img width="1104" alt="Screenshot 2025-05-02 at 12 24 55 PM" src="https://github.com/user-attachments/assets/46932f88-1ae8-483d-8815-926df25faa32" /><img width="1142" alt="Screenshot 2025-05-02 at 12 08 58 PM" src="https://github.com/user-attachments/assets/7ec1bc9c-601c-4f0f-a8a5-f913eb621fda" /># WeatherVista_Project
Weather Vista is a smart weather forecasting web application that combines real-time weather data with machine learning models to predict climate parameters like temperature, humidity, and rainfall. It also visualizes future trends using interactive graphs.

📌 Key Features

🌍 Fetches real-time weather data via OpenWeatherMap API
🤖 Uses ML models (Random Forest) for:
Rain prediction (classification)
Temperature & humidity forecasting (regression)
📈 5-hour future prediction visualization using charts
🖼️ Dynamic backgrounds based on current weather conditions
🌐 Built using Django + HTML/CSS/JS (Chart.js)
🛠️ Technologies Used

Frontend: HTML, CSS, JavaScript
Backend: Python (Django)
Machine Learning: scikit-learn, pandas, numpy
Visualization: Chart.js
API: OpenWeatherMap
📦 How to Run Locally

Clone the repository
git clone https://github.com/your-username/weather-vista.git
cd weather-vista
Create a virtual environment and activate it
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
Install the required packages
pip install -r requirements.txt
Add your OpenWeatherMap API key in views.py
API_KEY = 'your_api_key_here'
Run the Django development server
python manage.py runserver
Open your browser and go to
http://127.0.0.1:8000/

📷 Screenshot

![Uploading Screenshot 2025-05-02 at 12.08.58 PM.png…]()


Home page with weather display
Prediction chart view
Dynamic backgrounds (e.g., rain, cloudy, clear)



## 🌆 City Pulse: Your Smart Window into Urban Life

**City Pulse** is a sleek, real-time dashboard built with **Streamlit** that delivers instant insights about any city. Whether you're a traveler, data enthusiast, or urban analyst, this app gives you live weather, air quality, crime updates, tourist hotspots, trending topics, and even a smart chatbot that answers city-specific questions using Google Search.

---

### 🚀 Key Features

#### 🧠 Real-Time City Intelligence
- **Live Weather Conditions**: Temperature, humidity, and forecasts via OpenWeatherMap.
- **Climate Trends**: Monthly averages for temperature, rainfall, and humidity.
- **Air Quality Monitoring**: AQI breakdown with pollutant-level analysis.

#### 🌍 Urban Exploration
- **Tourist Recommendations**: Top-rated attractions using Google Places API.
- **Crime Alerts**: Latest city-specific crime headlines via News API.

#### 📊 Trend Analysis
- **Google Trends Integration**: Visualize global interest in your city over time.

#### 🤖 CityBot – Your AI-Powered Local Assistant
- Ask natural questions like:
  - “Best rooftop cafes near downtown”
  - “Free concerts this weekend”
  - “Where’s the nightlife buzzing tonight?”
- Powered by Google Search for accurate, up-to-date answers.

---

### 🛠️ Tech Stack

| Layer        | Tools Used |
|--------------|------------|
| **Frontend** | Streamlit |
| **APIs**     | OpenWeatherMap, Google Places, News API, Pytrends |
| **Chatbot**  | Custom integration with Google Search |
| **Libraries**| Pandas, Requests, HTML/CSS via Streamlit components |

---

### 📦 Installation & Setup

```bash
# Clone the repo
git clone https://github.com/your-username/city-pulse.git
cd city-pulse

# Install dependencies
pip install -r requirements.txt

# Create a .env file to store your API keys securely
touch .env
```

#### 🗝️ .env File Format
Add your API keys like this:
```env
OPENWEATHER_API_KEY=your_openweather_api_key
GOOGLE_PLACES_API_KEY=your_google_places_api_key
NEWS_API_KEY=your_news_api_key
```

> Make sure to load these keys in your app using `python-dotenv` or `os.environ`.

```python
from dotenv import load_dotenv
import os

load_dotenv()
weather_key = os.getenv("OPENWEATHER_API_KEY")
```

---

### 🚀 Run the App
```bash
streamlit run app.py
```

---

Want help adding user authentication, optimizing performance, or deploying this to the cloud? I’ve got your back.


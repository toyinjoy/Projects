# 📊 Netflix Content Analysis

Analyze trends in Netflix's movie and TV show offerings using a public dataset.

## 📁 Dataset
- Source: [Netflix Movies and TV Shows on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- File: `netflix_titles.csv.zip`

## 📌 Features
- Load and clean Netflix content data
- Analyze number of shows/movies added per year
- Identify top genres
- Visualize top countries contributing to Netflix

## 📈 Visualizations
- Bar plot of Movies vs. TV Shows
- Time series of new titles added over the years
- Top genres and countries (horizontal bar charts)

## 🔧 Setup
1. Download the dataset from Kaggle and upload it to `/content/netflix_titles.csv.zip`
2. Open the `netflix_analysis.ipynb` notebook
3. Run all cells to see analysis and visualizations

## 🧠 Insights
- Netflix has more movies than TV shows
- Dramatic rise in content post-2016
- Dominant genres: Drama, International
- Top countries: USA, India, UK

---

# 🌦️ Weather CLI App

Simple CLI tool to fetch real-time weather using OpenWeatherMap API.

## 🛠 Features
- Accepts city name as input
- Fetches current weather using `requests`
- Displays:
  - 🌡️ Temperature (°C)
  - 🌤️ Weather condition
  - 💧 Humidity
  - 💨 Wind speed

## 🚀 Usage (Terminal Version)
```bash
python weather_app.py "London"
```

## 🔐 .env File Format
```
OPENWEATHER_API_KEY=your_api_key_here
```

## 🧪 Example Output
```
🌍 Weather in London, GB
🌡️ Temperature: 14°C
🌤️ Condition: Broken Clouds
💧 Humidity: 77%
💨 Wind Speed: 3.6 m/s
```

## 📦 Requirements
- `requests`
- `python-dotenv`

Install with:
```bash
pip install requests python-dotenv
```

## 🌐 Get API Key
Sign up at [https://openweathermap.org/api](https://openweathermap.org/api) and generate a free API key.

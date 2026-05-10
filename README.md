# 🌦️ AI Weather App

> A modern AI-powered Weather Application built with **Streamlit**, **LangChain**, and **Groq API** that delivers real-time weather data with intelligent natural language explanations for any city in the world.

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logo=groq&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**[🚀 Live Demo](https://weather-app-saarthak1911.streamlit.app/) · [🐛 Report Bug](https://github.com/saarthak1911/Weather-App/issues) · [💡 Request Feature](https://github.com/saarthak1911/Weather-App/issues)**

</div>

---

## 📸 Preview

<!-- Replace with your actual screenshot -->
![Weather App Preview](https://github.com/user-attachments/assets/0666f878-a886-4e62-ba91-41196d9ab079)


---

## ✨ Features

- 🌍 **City Search** — Get live weather for any city worldwide
- 🌡️ **Temperature** — Current temp in Celsius / Fahrenheit
- 💧 **Humidity** — Real-time humidity percentage
- 💨 **Wind Speed** — Current wind speed and direction
- ☁️ **Weather Condition** — Clear, cloudy, rainy, and more
- 🤖 **AI Explanation** — Natural language weather summary powered by LangChain + Groq
- ⚡ **Fast UI** — Interactive and responsive Streamlit interface

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend / UI | Streamlit |
| AI / LLM | LangChain + Groq API (llama3) |
| Weather Data | OpenWeatherMap API (Requests) |
| Language | Python 3.10+ |
| Deployment | Streamlit Cloud |

---

## 📂 Project Structure

```
Weather-App/
│
├── weather.py          # Main application file
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation
```

---

## ⚙️ Local Setup

### 1. Clone the repository

```bash
git clone https://github.com/saarthak1911/Weather-App.git
cd Weather-App
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Add your API keys

Create a `.streamlit/secrets.toml` file:

```toml
OPENAI_API_KEY = "your_openai_or_groq_api_key"
WEATHER_API_KEY = "your_openweathermap_api_key"
```


### 4. Run the app

```bash
streamlit run weather.py
```

Open your browser at `http://localhost:8501`

---

## 🔑 API Keys Required

| API | Where to get it | Free tier |
|---|---|---|
| Groq API | [console.groq.com](https://console.groq.com) | ✅ Yes |
| OpenWeatherMap | [openweathermap.org/api](https://openweathermap.org/api) | ✅ Yes |

---

## 🌐 Deployment

This project is live on **Streamlit Cloud**.

To deploy your own copy:
1. Fork this repository
2. Go to [streamlit.io/cloud](https://streamlit.io/cloud) and sign in with GitHub
3. Click **New App** → select your forked repo → set main file as `weather.py`
4. Add your secrets under **App Settings → Secrets**
5. Click **Deploy** 🚀

---

## 📄 License

This project is open-source under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**Sarthak Mane**

[![GitHub](https://img.shields.io/badge/GitHub-saarthak1911-181717?style=flat&logo=github)](https://github.com/saarthak1911)


---

<div align="center">
  <sub>Built with ❤️ by Sarthak Mane</sub>
</div>

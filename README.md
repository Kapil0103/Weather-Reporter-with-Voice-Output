# Weather-Reporter-with-Voice-Output

### 📋 Short Description

> A Python script that fetches the current weather of any city using WeatherAPI and announces it using text-to-speech (TTS).

---

### 📄 Folder Structure

```
/weather-reporter/
├── weather.py
├── README.md
```

---

### 📄 README.md

````markdown
# 🌦️ Weather Reporter with Voice Output

This Python project fetches the current temperature of a given city from the WeatherAPI and uses text-to-speech (TTS) to announce the weather aloud.

---

## 🚀 Features
✅ Fetches real-time weather (temperature in °C) of any city  
✅ Uses WeatherAPI for accurate weather data  
✅ Speaks the result using pyttsx3 TTS engine  
✅ Command-line interface

---

## 📋 How to Run

### 1️⃣ Install dependencies
Make sure you have Python 3 installed, then install the required libraries:
```bash
pip install requests pyttsx3
````

### 2️⃣ Get your API key

* Create a free account at [weatherapi.com](https://www.weatherapi.com/).
* Replace the `key` parameter in the script (`adf28b5da7f940a9849183534250806`) with your own API key.

### 3️⃣ Run the script

```bash
python weather.py
```

* Enter the city name when prompted.
* The script will print and announce the current temperature in °C.

---

## 📄 Sample Output

```
enter the name of the city:
Mumbai
The current weather in Mumbai is 30 degrees
```

---

## 🧰 Technologies Used

* Python 3.x
* [WeatherAPI](https://www.weatherapi.com/) (for weather data)
* `requests` (HTTP requests)
* `pyttsx3` (text-to-speech)

---

## 📚 Notes

⚡ Ensure you have an internet connection.
⚡ Replace the API key in the URL with your personal key for reliability.
⚡ TTS works offline and supports Windows, Mac, and Linux.

---

## 🙏 Acknowledgements

Inspired by combining Python API requests with offline text-to-speech capabilities for a fun and useful CLI project.

```



# 🧭 Travel Guide Generator

A simple Python script that creates a 3-day travel guide for any city using OpenAI GPT and online travel sources.

---

## 📌 What It Does

- Takes a city name as input
- Collects information from:
  - **Wikipedia** – for general background
  - **Wikivoyage** – for travel-specific content
  - **TripAdvisor** – provides a link to popular attractions
- Sends the combined info to **OpenAI GPT** to generate:
  - City introduction
  - Must-see attractions
  - What to eat
  - 3-day itinerary
  - Practical tips

---

## ⚙️ Requirements

- Python 3.7+
- Required packages:
  - `openai`
  - `requests`
  - `beautifulsoup4`
  - `python-dotenv`

Install them using:


`pip install openai requests beautifulsoup4 python-dotenv`

## 🔑 Setup

- Create a .env file in your project directory.
- Add your OpenAI API key like this:
OPENAI_API_KEY=your_api_key_here

## 🚀 How to Use

- Run the script in your terminal or in a notebook (e.g., Google Colab):
python travel_guide.py
-When prompted, enter a city name (e.g., Paris or Tokyo).
-The script will fetch online data and generate a full travel guide in English.

## 🧠 Powered By

-OpenAI GPT
-Wikipedia
-Wikivoyage
-TripAdvisor


## 📕 Türkçe çıktısı da .ipynb dosyası içinde mevcuttur. 



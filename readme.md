# Decoupled Weather App

This is a full-stack decoupled weather application built as part of a pre-screening assessment. It features:

- A **Next.js** frontend with TypeScript, Tailwind CSS, and RippleUI components
- A **Laravel** backend serving as an API for weather data
- Integration with **OpenWeatherMap API** for current and forecasted weather

## 🌐 Tech Stack

- **Frontend**: Next.js, TypeScript, Tailwind CSS (RippleUI), Fetch API
- **Backend**: Laravel (latest version)
- **Weather Data**: OpenWeatherMap API

## 📁 Project Structure

weather-app/ ├── frontend/ # Next.js + Tailwind + RippleUI ├── backend/ # Laravel API backend


## 🚀 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/isiji/weather-app.git
cd weather-app

#set up each part


---

### ✅ `frontend/README.md`

```markdown
# Frontend - Weather App (Next.js)

This is the frontend of the weather app built with:

- **Next.js**
- **TypeScript**
- **Tailwind CSS** with RippleUI
- **Fetch API** for AJAX

## 📦 Installation

```bash
cd frontend
npm install

NEXT_PUBLIC_OPENWEATHER_API_KEY=your_api_key_here

npm run dev

Features
City search with geocoding

Auto-location weather detection

Temperature unit switch (Celsius/Fahrenheit)

3-day forecast

Wind & humidity info

Animated and responsive UI using RippleUI




---

### ✅ `backend/README.md`

```markdown
# Backend - Weather API (Laravel)

This is the Laravel API backend that powers the weather app.

## ⚙️ Requirements

- PHP >= 8.1
- Composer
- Laravel (latest)
- OpenWeatherMap API key

## 📦 Installation

```bash
cd backend
composer install
cp .env.example .env



OPENWEATHER_API_KEY=your_api_key_here

php artisan serve

The API will be available at http://127.0.0.1:8000/api.
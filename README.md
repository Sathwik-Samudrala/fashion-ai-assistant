# Fashion AI Assistant 👗🤖

## Overview

Fashion AI Assistant is an AI-powered outfit recommendation system that helps users discover personalized fashion suggestions based on their preferences, occasion, gender, and budget.

The application combines a curated fashion dataset with Google's Gemini AI to provide intelligent outfit recommendations and conversational fashion guidance.

---

## Features

* AI-powered fashion assistant using Gemini AI
* Personalized outfit recommendations
* Occasion-based outfit selection
* Gender-specific recommendations
* Budget-aware outfit matching
* Product catalog browsing
* Outfit explanation generation
* Interactive chat interface
* Product image support
* REST API backend using FastAPI
* Modern React frontend

---

## Tech Stack

### Frontend

* React.js
* Vite
* JavaScript
* CSS

### Backend

* FastAPI
* Python
* Pandas

### AI Integration

* Google Gemini API
* google-genai SDK

### Dataset

* Curated fashion products dataset
* Curated outfit combinations dataset

---

## Project Structure

fashion-ai-assistant/

├── backend/

│ ├── app/

│ │ ├── routes/

│ │ ├── services/

│ │ ├── models/

│ │ ├── data/

│ │ └── main.py

│ └── requirements.txt

│

├── frontend/

│ ├── src/

│ ├── public/

│ └── package.json

│

└── README.md

---

## API Endpoints

### Recommendation API

POST /api/recommend

Generates outfit recommendations based on user preferences.

### Chat API

POST /api/chat

Provides conversational fashion assistance.

### Products API

GET /api/products

Returns product catalog information.

### Outfit API

GET /api/outfits/{outfit_id}

Returns outfit details.

### Health Check

GET /api/health

Returns backend health status.

---

## Dataset Statistics

* Products Loaded: 68
* Curated Outfits: 25
* Multiple Fashion Categories
* Multiple Fashion Brands

---

## Installation

### Backend

cd backend/app

pip install -r ../requirements.txt

uvicorn app.main:app --reload --port 8000

### Frontend

cd frontend

npm install

npm run dev

---

## Screenshots

### Home Page

home-page.png

### Outfit Recommendation

outfit-recommendation - Copy.png

### Browse Items

/browse-products.png

---

## Future Improvements

* User authentication
* Wishlist support
* Fashion trend analysis
* Image-based outfit search
* Advanced recommendation engine
* Deployment on cloud platforms

---

## Author

Sathwik Samudrala

GitHub:
https://github.com/Sathwik-Samudrala

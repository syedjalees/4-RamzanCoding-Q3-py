# FastAPI Simple API - Side Hustles & Money Quotes

## 🚀 About the Project
This FastAPI-based project provides two simple GET endpoints that return either a random side hustle idea or an inspiring money quote. It's a great starting point to understand API development using FastAPI.

## 📌 Features
- Get a random side hustle idea to start your journey towards financial independence.
- Get an inspiring money-related quote to stay motivated.
- Secure API with a simple key-based authentication.

## 📡 API Endpoints

### 1️⃣ Get a Random Side Hustle
**Endpoint:** `/side_hustles`  
**Method:** `GET`  
**Query Parameter:** `apiKey` (Required)  
**Example Request:**
```bash
curl -X 'GET' 'http://127.0.0.1:8000/side_hustles?apiKey=1234567890' -H 'accept: application/json'
```
**Example Response:**
```json
{
  "side_hustle": "Freelancing - Start offering your skills online!"
}
```

### 2️⃣ Get a Random Money Quote
**Endpoint:** `/money_quotes`  
**Method:** `GET`  
**Query Parameter:** `apiKey` (Required)  
**Example Request:**
```bash
curl -X 'GET' 'http://127.0.0.1:8000/money_quotes?apiKey=1234567890' -H 'accept: application/json'
```
**Example Response:**
```json
{
  "money_quote": "Money is a terrible master but an excellent servant. – P.T. Barnum"
}
```

## 🛠 Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/syedjalees/fastapi-simple-api.git
cd fastapi-simple-api
```

### 2️⃣ Initialize UV Virtual Environment
```bash
uv init simple-api
cd simple-api
```

### 3️⃣ Install Dependencies
```bash
uv add fastapi[standard]
```

### 4️⃣ Activate the Virtual Environment (Windows)
```bash
.venv\Scripts\activate
```

### 5️⃣ Run the API
```bash
fastapi dev main.py
```

### 6️⃣ Access the API Documentation
Once the API is running, open your browser and visit:  
[http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)

## 🎯 Built With
- Python 🐍
- FastAPI ⚡
- Random Library 🎲

## 👨‍💻 Author
Built with ❤️ by [SAYYED JALEES](https://github.com/syedjalees)


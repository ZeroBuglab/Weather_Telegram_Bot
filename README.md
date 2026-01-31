# Hello! 👋  
This is a Telegram bot that provides weather information when a user sends a city name.    
The bot uses a weather API to fetch real-time data and responds directly in Telegram    
*********************
## ✨ Features  
* Get weather by city name  
* Real-time weather data  
* Telegram bot interaction  
* Fast API requests
******************
## 🧠 How It Works
1. The user writes the command /weather and the bot asks for the city name  
2. The bot sends a request to a weather API  
3. The API returns weather data in JSON format  
4. The bot formats the result and replies to the user  
*******************
## 🛠 Tech Stack  
* Python  
* requests — API requests  
* json — parsing weather data  
* telebot — Telegram bot API  
* Weather API service  
* Bot token (Telegram)  
******************
# 🔐 API & Tokens Security  
⚠️ Important:  
Bot tokens and API keys are not included in this repository for security reasons.  
You must add your own credentials in the code.  

#### Example:  
BOT_TOKEN = "YOUR_TELEGRAM_BOT_TOKEN"  
WEATHER_API_KEY = "YOUR_API_KEY"  

## Example Usage   
You:/start  
Bot:привет имя/фамилия  я бот который выдает погоду по команде /weather  
You:/weather  
Bot: Напиши название города:
You:Canada
Bot:Сейчас погода: 9.07 °C   
********************************

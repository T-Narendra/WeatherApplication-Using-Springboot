# 🌤 Weather Application (Spring Boot)

A simple Spring Boot application that fetches real-time weather information for a given city using an external weather API.  

---

## 🚀 Features
- Fetch current weather details by city name.  
- REST API built with *Spring Boot*.  
- External API integration (e.g., OpenWeatherMap).  
- Configurable API key via application.properties. 

---

## 🛠 Tech Stack
- *Java 17+*  
- *Spring Boot 3.x*  
- *Spring Web*  
- *Spring Boot Starter Validation*  
- *Maven*  
- *External Weather API* (e.g., OpenWeatherMap)

## 🌍 API Endpoints

Get Weather by City

# Request

GET /api/weather?city={cityName}

# Example

GET http://localhost:8080/api/weather?city=London

# Response (JSON Example)

{
  "city": "London",
  "temperature": "18°C",
  "description": "clear sky",
  "humidity": 65
}

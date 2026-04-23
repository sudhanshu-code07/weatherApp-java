# 🌦️ Weather Web App

A dynamic weather application that fetches real-time weather data using the **OpenWeather API** and displays it using a Java-based backend (Servlet + JSP).

---

## 🚀 Features

* 🌍 Search weather by city name
* 🌡️ Displays temperature (°C)
* 💧 Shows humidity levels
* 🌬️ Wind speed details
* ☁️ Weather condition (Clear, Rain, Clouds, etc.)
* 📅 Displays date & time

---

## 🛠️ Technologies Used

* Frontend: HTML, CSS, JavaScript
* Backend: Java Servlet, JSP
* API: OpenWeather API
* JSON Parsing: Gson Library

---

## 📂 Project Structure

```
WeatherApp/
│── index.html
│── index.jsp
│── MyServlet.java
│── gson.jar
│── style.css
│── images/
```

---

## ⚙️ How It Works

1. User enters a city name on the homepage 
2. Request is sent to the Servlet
3. Servlet calls OpenWeather API
4. Data is parsed using Gson 
5. Results are forwarded to JSP for display

---

## 🔑 Setup Instructions

1. Clone the repository

```
git clone https://github.com/your-username/weather-app.git
```

2. Add your OpenWeather API key in:

```
MyServlet.java
```

Replace:

```
String apiKey = "Apni-Api-Key Dalo";
```

3. Add required libraries:

* gson.jar
* Servlet API

4. Deploy on Apache Tomcat server

5. Run the project:

```
http://localhost:8080/WeatherApp
```

---

## 📸 Screenshots

(Add your UI screenshots here)

---

## 🙌 Contribution

Feel free to fork this repo and improve the project.

---

## 📜 License

This project is open-source and available under the MIT License.

# 🌤️ Weather Search & History web Application

A simple and interactive web application that allows users to **search current weather** conditions for any city using the **OpenWeather API**. The app also stores and displays the **search history**, making it easier for users to revisit previously searched cities.



## 🔍 Features

- 🔎 Search weather by city name
- 🌡️ Display current temperature, weather description, humidity, and wind speed
- 🕑 Real-time data using **OpenWeather API**
- 📜 Search history saved using browser's **localStorage**
- 💡 Responsive and clean UI



## 🛠️ Technologies Used

- **HTML**
- **CSS**
- **JavaScript**
- **OpenWeather API**



## 🧪 How It Works

1. User enters a city name and submits the form.
2. A `fetch()` request is made to the OpenWeather API.
3. The response data is parsed and displayed on the page.
4. The city name is saved in the localStorage and shown in the search history.
5. Clicking on a history item re-triggers the weather fetch for that city.



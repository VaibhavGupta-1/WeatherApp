# 🌦️ WeatherApp

An elegant and minimal Android application built with **Kotlin** and **Jetpack Compose** that provides real-time weather updates for any city using a clean and intuitive user interface.

---

## ✨ Features

- 🔍 Search weather by city name
- ☀️ Displays current temperature, condition, humidity, and wind speed
- 🌍 Supports multiple locations
- 📱 Modern UI using Jetpack Compose
- ⚡ Fast and responsive
- 🔄 Loading state and error handling

---

## 🛠️ Built With

- **Kotlin**
- **Jetpack Compose**
- **Retrofit** – For API calls
- **MVVM Architecture**
- **Coroutines** – For asynchronous operations
- **LiveData / State management**
- **[WeatherAPI.com](https://www.weatherapi.com/)** – For fetching weather data

---

## 📸 Screenshots

| Home Screen | Search City | Weather Details |
|-------------|-------------|-----------------|
| ![Home](https://github.com/user-attachments/assets/940a4e52-cc2b-49b5-a78c-bf9d8e6cc19b) | ![Search](https://github.com/user-attachments/assets/c1123ce9-08ac-4166-a835-5cc69997638f) | ![Details](https://github.com/user-attachments/assets/64d0613e-179f-46ca-baf4-cff9c82391c7)
|

---

## 🚀 Getting Started

### ✅ Prerequisites

- Android Studio Hedgehog or later
- Gradle 8+
- API key from [WeatherAPI.com](https://www.weatherapi.com/)

### 📥 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/VaibhavGupta-1/WeatherApp.git
Open the project in Android Studio

Add your WeatherAPI key in the appropriate file (e.g., Constants.kt):

const val API_KEY = "your_api_key_here"
Run the app on an emulator or physical device

📂 Project Structure
WeatherApp/
├── app/
│ ├── manifests/
│ │ └── AndroidManifest.xml
│ ├── kotlin+java/
│ │ └── com.example.weatherapp/
│ │ ├── api/
│ │ │ ├── Condition.kt
│ │ │ ├── Constant.kt
│ │ │ ├── Current.kt
│ │ │ ├── Location.kt
│ │ │ ├── NetworkResponse.kt
│ │ │ ├── RetrofitInstance.kt
│ │ │ ├── WeatherApi.kt
│ │ │ └── WeatherModel.kt
│ │ ├── ui.theme/
│ │ ├── MainActivity.kt
│ │ ├── WeatherPage.kt
│ │ └── WeatherViewModel.kt
├── res/
├── build.gradle.kts (Project)
├── build.gradle.kts (Module: app)
├── proguard-rules.pro
├── gradle.properties
├── gradle-wrapper.properties
├── libs.versions.toml
├── local.properties
└── settings.gradle.kts

🤝 Contributing
Contributions are welcome!
Please fork the repo and submit a pull request for any improvements.

📄 License
This project is licensed under the MIT License – see the LICENSE file for details.

🙋‍♂️ Author
Vaibhav Gupta
📧 LinkedIn:https://www.linkedin.com/in/vaibhavgupta-01
📦 GitHub:https://github.com/VaibhavGupta-1

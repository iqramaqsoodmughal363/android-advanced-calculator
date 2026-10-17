# 🧮 Advanced Calculator & Unit Converter

<p align="center">
  <b>A powerful, all-in-one Android application for math and unit conversions.</b>
</p>

<p align="center">
  <em>"Switch seamlessly between a scientific calculator and a multi-category unit converter."</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F-red" alt="Made with Love">
  <img src="https://img.shields.io/badge/Platform-Android-green" alt="Platform">
  <img src="https://img.shields.io/badge/Language-Java-orange" alt="Language">
  <img src="https://img.shields.io/badge/UI-Material%20Design-blue" alt="UI">
  <img src="https://img.shields.io/badge/Status-Complete-success" alt="Status">
</p>

---

## 📋 Overview

**Advanced Calculator** is a feature-rich Android application designed to handle both basic arithmetic and complex unit conversions. Built using modern Android development practices, it utilizes **Java**, **Fragments**, and **ViewPager2** to provide a smooth, swipeable, and intuitive user experience. Whether you need to solve math problems or convert measurements on the go, this app has you covered.

---

## ✨ Key Features

### 🧮 Scientific Calculator
* **Basic & Advanced Math:** Addition, subtraction, multiplication, division.
* **Scientific Functions:** Square root (√), powers (X², X³, X^y), trigonometry (SIN, COS, TAN), and logarithms (LOG).
* **Memory Functions:** MC (Memory Clear), MR (Memory Recall), M+, M-.
* **Smart Input:** AC (All Clear), CE (Clear Entry), and backspace support.
* **Responsive Design:** Dark theme optimized for eye comfort.

### 🔄 All-in-One Unit Converter
* **7 Conversion Categories:** Length, Weight, Temperature, Area, Volume, Time, and Speed.
* **Dynamic Spinners:** Units update automatically based on the selected category.
* **Comprehensive Units:** From standard (Meter, Kilogram) to specialized (Acre, Knot).
* **Smart Formatting:** Results are formatted cleanly (removes trailing zeros).
* **Error Handling:** Alerts users on invalid or empty inputs.

---

## 🛠️ Tech Stack

| Category | Tools / Technologies |
|---|---|
| **Language** | Java |
| **IDE** | Android Studio |
| **Architecture** | Fragment-based with ViewPager2 |
| **UI/UX** | XML Layouts, Material Design, Dark Theme |
| **Navigation** | Swipeable Tabs (ViewPagerAdapter) |
| **Core Logic** | Custom Mathematical & Conversion Algorithms |

---

## 📂 Project Structure

```text
android-advanced-calculator/
│
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/advancedcalculator/
│   │   │   │   ├── MainActivity.java        # Hosts the ViewPager2
│   │   │   │   ├── ViewPagerAdapter.java    # Manages Calculator & Converter fragments
│   │   │   │   ├── CalculatorFragment.java  # Scientific math logic & UI
│   │   │   │   └── ConverterFragment.java   # Unit conversion logic & UI
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   │   ├── activity_main.xml
│   │   │   │   │   ├── fragment_calculator.xml
│   │   │   │   │   └── fragment_converter.xml
│   │   │   │   ├── values/                  # Colors, Strings, Themes (Dark Mode)
│   │   │   │   └── xml/                     # Backup rules
│   │   │   └── AndroidManifest.xml
│   │   ├── test/                            # Unit tests
│   │   └── androidTest/                     # Instrumented tests
│   ├── build.gradle
│   └── proguard-rules.pro
├── build.gradle
├── settings.gradle
└── README.md

---

## 🚀 How to Build and Run

### Prerequisites
* **Android Studio** (Latest Version)
* **JDK 11** or higher
* **Android SDK** (API 24+)

### Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/iqramaaqsoodmughal363/android-advanced-calculator.git
   ```
2. **Open in Android Studio**
   Open Android Studio → **File** → **Open** → Select the project folder.
3. **Sync Gradle**
   Wait for Gradle to sync. Click **"Sync Now"** if prompted.
4. **Build the APK**
   Go to **Build** → **Build Bundle(s) / APK(s)** → **Build APK(s)**.
5. **Run the App**
   Connect your Android device or start an emulator, then click the **Run** button (green play icon).

---

## 💡 How It Works (Behind the Scenes)

### 1. Navigation (ViewPager2)
The app uses `ViewPager2` with a custom `ViewPagerAdapter` to allow users to seamlessly swipe between the **Calculator** and **Converter** screens without reloading the app.

### 2. Calculator Logic
The `CalculatorFragment` handles complex user inputs. It parses mathematical expressions, handles memory operations (MC, MR, M+, M-), and computes scientific functions (Trigonometry, Logarithms, Powers).

### 3. Converter Engine
The `ConverterFragment` dynamically populates `Spinner` widgets based on the selected category. Under the hood, the `getConversionFactor()` method uses a base-unit strategy to convert values accurately across different measurement systems.

---

## 🎯 Key Takeaways

* **Modular Architecture:** Separating the Calculator and Converter into Fragments makes the codebase clean and scalable.
* **Dynamic UI:** Spinners automatically adapt to user selections, preventing invalid conversions.
* **Accuracy:** The conversion engine uses precise formulas (e.g., standard base units) to ensure accurate results.
* **User Experience:** A built-in dark theme and clean layout make the app comfortable for prolonged use.

---

## 👩‍💻 Author

**Iqra Maqsood Mughal**

*Software Engineer · Full-Stack Developer · Code Craftsman · Android App Developer · Problem Solver 🚀*

```javascript
const codeIsLife = "Code is life";
while (true) { 
    learn(); 
    build(); 
    innovate(); 
}
```

---

## 📅 Date

October 18, 2026

---

## 📄 License

This project is intended for educational and personal use purposes.
```

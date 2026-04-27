# 🌍 Air Quality Index (AQI) Visualization Dashboard

A modern, interactive **frontend dashboard** for visualizing real-time and simulated air quality data using a colorful, futuristic UI.
This project processes pollutant concentrations (PM2.5, PM10, NO₂), computes AQI, and presents insights through charts, cards, and comparisons.

---

## 🚀 Features

* 📊 **Real-time AQI Simulation**
* 🧪 **Pollutant Monitoring**

  * PM2.5
  * PM10
  * NO₂
* 🧮 **AQI Calculation Logic**
* 📈 **Interactive Charts**

  * Bar Chart (Pollutants)
  * Line Chart (AQI Trends)
  * Doughnut Chart (Composition)
* 🏙 **City-wise Comparison**
* 💡 **Health Recommendations based on AQI**
* 🌈 **Modern UI**

  * Glassmorphism design
  * Neon gradients
  * Smooth hover animations
* 🔄 **Refresh Button for Live Updates**

---

## 🖥️ Demo Preview

A futuristic dashboard displaying:

* AQI score and status (Good, Moderate, Poor, Severe)
* Weather information
* Pollutant levels
* Dynamic charts
* City comparison cards

---

## 🧠 How It Works

### 1. Pollutant Data Processing

The system generates or fetches pollutant values:

* PM2.5
* PM10
* NO₂

### 2. AQI Calculation

AQI is computed using a simplified weighted formula:

```
AQI = (PM2.5 × 0.5) + (PM10 × 0.3) + (NO₂ × 0.2)
```

### 3. Status Classification

| AQI Range | Status   |
| --------- | -------- |
| 0–50      | Good     |
| 51–100    | Moderate |
| 101–150   | Poor     |
| 151+      | Severe   |

### 4. Visualization

* Charts rendered using **Chart.js**
* UI updates dynamically on refresh

---

## 🛠️ Tech Stack

* **HTML5**
* **CSS3** (Glassmorphism + Gradients)
* **JavaScript (Vanilla JS)**
* **Chart.js** (for data visualization)

---

## 📂 Project Structure

```
AQI-Dashboard/
│── index.html   # Main file (HTML + CSS + JS)
│── README.md    # Documentation
```

---

## ▶️ How to Run

1. Download or clone this repository:

   ```
   git clone https://github.com/your-username/aqi-dashboard.git
   ```

2. Open the project folder

3. Run the app:

   * Double-click `index.html`
     OR
   * Open with Live Server (VS Code recommended)

---

## 🔮 Future Enhancements

* 🌍 Integrate real-time APIs (OpenAQ / WAQI)
* 🗺 Add interactive maps (Leaflet / Google Maps)
* 🔍 Enable city search functionality
* 🌙 Dark/Light theme toggle
* 📡 Live updates with WebSockets
* 📱 Fully responsive mobile UI
* 📊 Historical data storage & analytics

---

## ⚠️ Disclaimer

This project currently uses **simulated/random data** for demonstration purposes.
For real-world usage, integrate with live AQI APIs.

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a new branch
3. Make changes
4. Submit a Pull Request

---

## 📜 License

This project is open-source and available under the **MIT License**.

---

## 👨‍💻 Author

Developed by **Shubham Kumar**

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!

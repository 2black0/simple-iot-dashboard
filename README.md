# 🌐 Simple IoT Dashboard Template

A lightweight and responsive **web-based dashboard** designed for **Internet of Things (IoT)** projects, this template is ideal for displaying **real-time sensor data** (such as turbidity) using HTML, CSS (Bootstrap), and JavaScript (Chart.js). Built for simplicity and clarity, it allows easy integration with platforms like **ESP32**, **MQTT**, or cloud services.

![Dashboard Screenshot](Project/img/1.jpg)

---

## 🚀 Features

* 📊 Real-time chart visualization using [Chart.js](https://www.chartjs.org/)
* 📋 Responsive data table for recent sensor readings
* 🧭 Built with [Bootstrap 4](https://getbootstrap.com/) for responsive design
* 🌐 Clean and modular HTML structure (Home and About pages)
* 🧠 Ready for integration with MQTT, HTTP, or WebSocket data sources
* 👨‍💻 Suitable for beginners in IoT or frontend development

---

## 🏗️ Project Structure

```
.
├── Project
│   ├── index.html           # Main dashboard page with chart and data table
│   ├── about.html           # About section for credits and description
│   ├── css/                 # Bootstrap CSS files
│   ├── js/                  # JavaScript (Chart.js, Bootstrap, jQuery, etc.)
│   └── img/                 # Sample images and user branding
├── LICENSE
└── README.md
```

---

## 📸 Dashboard Preview

### 📈 Live Chart

Displays turbidity sensor data in a line chart:

```
Time     | Turbidity | Status
---------|-----------|--------
13:00    | 4         | Aman
13:05    | 65        | Sedang
13:10    | 55        | Sedang
13:15    | 99        | Tinggi
13:20    | 0         | Aman
13:25    | 22        | Aman
```

### 📑 Data Table

Synchronized with the chart, showing timestamped sensor values and status levels (`Aman`, `Sedang`, `Tinggi`).

---

## ⚙️ How to Use

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/simple-iot-dashboard.git
   ```

2. Open `index.html` in your web browser.

3. Integrate with your IoT device (e.g., ESP32) using:

   * REST API (send JSON to the dashboard)
   * MQTT + JavaScript bridge
   * WebSocket (optional real-time extension)

> Example: For ESP32, send turbidity data via HTTP POST and inject into the DOM using JavaScript.

---

## 📄 Customization Tips

* Replace `Chart.js` logic in `index.html` with dynamic JS for real-time updates.
* Link to a real backend or use localStorage/database for persistent storage.
* Add login/authentication for production dashboards.

---

## 👤 About

This dashboard was created by **[2black0@gmail.com](mailto:2black0@gmail.com)** as part of an educational IoT prototype, aiming to help beginners quickly deploy and visualize sensor data.

See `about.html` for more.

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more information.

---
---

![简体中文README](https://github.com/HuizhouCityCollageEV/AquaGuardian/blob/main/README_CN.md)  

# AquaGuardian  
## Open Source Smart Water Quality Monitoring System for Aquariums, Pools & Aquaculture

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)  
![License](https://img.shields.io/github/license/yourname/AquaGuardian)  

> 🌊 **AquaGuardian** is an open-source smart water quality monitoring system based on ESP32, designed for aquariums, swimming pools, and aquaculture environments. It integrates TDS, pH, turbidity, temperature, and humidity sensors to provide real-time water data with automated alerts, cloud connectivity, and mobile app support.

---

## 📌 Features

- ✅ **Multi-parameter Sensor Support**: TDS, pH, Turbidity, Temperature, Humidity
- ✅ **ESP32-based Core System**: Low cost, Wi-Fi + Bluetooth dual-mode communication
- ✅ **Real-time Data Monitoring**: View water status anytime via mobile app or web dashboard
- ✅ **Smart Alert System**: Local buzzer + Push notification to your phone
- ✅ **Automated Response Actions**:
  - For **Aquaculture**: Auto-oxygenation, water replacement, alert nearby experts
  - For **Home Users**: Auto-filtering, auto-water change, oxygen pump activation
- ✅ **Visual Scripting (Block Programming)**: Customize automation logic without coding
- ✅ **Cloud Integration & API**: Store and share data via private or public cloud platforms
- ✅ **Modular Design**: Easy to expand or customize for different use cases

---

## 🧠 Target Scenarios

| Use Case        | Description |
|------------------|-------------|
| **Aquariums**     | Real-time monitoring for fish tanks and marine exhibits |
| **Swimming Pools** | Monitor chlorine levels, pH, and clarity automatically |
| **Aquaculture Farms** | Early warning system for fish/shrimp farms |
| **Home Fish Tanks** | Automated maintenance for hobbyists |

---

## 🔧 Hardware Components

| Component           | Description |
|---------------------|-------------|
| ESP32 Dev Board     | Main controller with Wi-Fi/Bluetooth |
| TDS Sensor          | Measures total dissolved solids in water |
| pH Sensor           | Detects acidity/alkalinity level |
| Turbidity Sensor    | Measures water clarity |
| DHT22 / SHT30       | Environmental temperature and humidity |
| Relay Module        | Controls pumps, filters, oxygenators |
| Power Supply        | USB or battery-powered operation |

---

## 📱 Mobile App

We've developed a custom mobile application that allows users to:

- 📊 View live sensor data
- 🚨 Set custom thresholds for alerts
- 🔄 Trigger automated actions (e.g., filter startup)
- 🧩 Create automation logic using visual block programming
- ☁️ Sync data with cloud services

> The app is available for both Android and iOS platforms. Source code can be found in the `/mobile-app` directory.

---

## 🛠️ Development Setup

### Prerequisites

- ESP-IDF or Arduino IDE
- PlatformIO (optional)
- Git
- Python 3.x (for scripts)

### Installation Steps

1. Clone the repo:

```bash
git clone https://github.com/HuizhouCityCollageEV/AquaGuardian.git
```

2. Navigate into the project folder:

```bash
cd AquaGuardian
```

3. Install dependencies and upload firmware:

```bash
# Follow the instructions in the README inside the firmware folder
```

4. Connect your ESP32 device and flash the firmware.

5. Launch the mobile app or connect to the local server for data visualization.

---

## 📦 Roadmap

| Feature                          | Status |
|----------------------------------|--------|
| Basic Sensor Integration         | ✅ Done |
| Cloud Data Upload                | ✅ Done |
| Mobile App UI                    | ✅ Done |
| Automation Logic Engine          | ✅ Done |
| Visual Block Programming Editor  | ✅ Done |
| AI-based Water Quality Prediction| 🚧 In Progress |
| Multi-language Support           | 🚧 In Progress |
| Community Forum & Wiki           | 🚀 Planned |

---

## 🤝 Contributing

Contributions are welcome! Whether you're fixing bugs, adding new features, translating content, or improving documentation — every help counts.

Please read our [Contributing Guide](CONTRIBUTING.md) before submitting a PR.

---

## 📜 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## 💬 Get in Touch

- 📧 Email: yourmail@example.com
- 🌐 Website: [yusirx.top] *(optional)*

---

> 🙌 Join us in building smarter, safer, and more sustainable water ecosystems!

---
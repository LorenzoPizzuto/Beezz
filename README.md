# Beezzz 🐝

<div align="center">

![PreviewBeezzzGithub](https://github.com/user-attachments/assets/abe26c4d-54c0-40db-91b8-e82313879e75)

**Smart Hive Monitoring through Sound Analysis**

[![Swift](https://img.shields.io/badge/Swift-6.0-orange?style=flat-square&logo=swift)](https://swift.org)
[![iOS](https://img.shields.io/badge/iOS-18.0+-blue?style=flat-square&logo=apple)](https://developer.apple.com/ios/)
[![SwiftUI](https://img.shields.io/badge/SwiftUI-6.0-purple?style=flat-square&logo=swift)](https://developer.apple.com/xcode/swiftui/)
[![SwiftData](https://img.shields.io/badge/SwiftData-Enabled-green?style=flat-square)](https://developer.apple.com/xcode/swiftdata/)
[![Hardware](https://img.shields.io/badge/Hardware-Microphone%20Device-yellow?style=flat-square)]()
[![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square)](LICENSE)

*Beezzz helps beekeepers monitor hive conditions through intelligent sound analysis, real-time alerts, and a simple mobile experience.*

[Features](#-features) • [Installation](#-installation) • [Usage](#-usage) • [Architecture](#-architecture) • [Contributing](#-contributing)

</div>

---

## 🐝 Project Overview

Beezzz is an intelligent hive monitoring system that analyzes sound frequencies produced by bees to provide real-time insights into hive conditions. Using a hardware device equipped with a microphone and an iOS app developed in Swift, the system automatically identifies different hive states and sends timely notifications to beekeepers.

### 🎯 What Makes Beezzz Special

- **🎧 Sound-Based Monitoring**: Detect hive activity through bee sound frequencies
- **📲 Real-Time Alerts**: Receive immediate notifications for important hive events
- **📊 Clear Dashboard**: Visualize hive conditions with intuitive cards and graphs
- **🏡 Multi-Hive Management**: Keep track of several hives in one place
- **📈 Historical Insights**: Analyze past trends to support better decisions

---

## ✨ Features

### 🎧 Sound Analysis
- **Advanced Frequency Analysis** — Detect changes in bee sound patterns
- **Swarming Alerts** — Identify signals associated with possible swarming behavior
- **Anomaly Detection** — Highlight unexpected hive activity that may require attention

### 📱 Beekeeper Experience
- **Intuitive Dashboard** — Quick overview of hive health and recent activity
- **Status Indicators** — Easy-to-read visual feedback for each hive
- **Real-Time Notifications** — Timely alerts when critical conditions are detected

### 📊 Data & Monitoring
- **Historical Data** — Review hive activity over time
- **Trend Analysis** — Identify recurring patterns and changes in hive behavior
- **Hive Management** — Add, edit, and organize multiple hives in one app

### ⚙️ Customization
- **Custom Alert Thresholds** — Personalize notifications based on your needs
- **Monitoring Preferences** — Adjust how and when you receive updates
- **Scalable Setup** — Suitable for both small and growing apiaries

---

## 📱 Screenshots

<div align="center">

### iPhone App

<img width="300px" height="678px" alt="Beezzz" src="https://github.com/user-attachments/assets/dc117221-9c36-45f6-aa98-3e7878687833" />
![Beezzz3](https://github.com/user-attachments/assets/d4f3bf5b-9e59-4f37-a58d-eb4b0fcd4751)
![Beezzz2](https://github.com/user-attachments/assets/4e5aee4c-cb8a-4965-a15c-2fb30e845b18)

</div>

---

## 🚀 Installation

### Prerequisites
- **Xcode 16.0+**
- **iOS 18.0+**
- **Hardware microphone device** for full monitoring features
- Apple Developer Account recommended for physical device testing

### Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/LorenzoPizzuto/Beezzz.git
   cd Beezzz
   ```

2. **Open in Xcode**
   ```bash
   open Beezzz.xcodeproj
   ```

3. **Connect the Hardware**
   - Use the dedicated microphone device if available
   - Or run the app in simulator mode for UI testing

4. **Build and Run**
   - Select an iPhone or simulator
   - Build and run the project (⌘+R)

---

## 🎮 Usage

### Getting Started

1. Open the app on your iPhone
2. Connect or pair the monitoring hardware
3. Add a hive to the system
4. Start collecting sound data
5. Monitor status updates and notifications from the dashboard

### Daily Workflow

- **Check Dashboard** — View the current state of your hives
- **Review Alerts** — Respond to swarming or anomaly notifications
- **Analyze Trends** — Use historical data to understand hive behavior over time
- **Manage Hives** — Update hive information and monitoring settings as needed

---

## 🏗️ Architecture

### Technology Stack
- **Frontend**: SwiftUI
- **Custom UI Components**: UIKit
- **Persistence**: SwiftData
- **Hardware Integration**: External microphone-based monitoring device

### Project Structure

```bash
Beezzz/
├── Components/        # Reusable UI components
├── Model/             # Hive, sound analysis, and notification models
├── View/              # Dashboard, hive details, settings, and main flows
├── Assets/            # Images, icons, and sound references
└── Resources/         # Additional project resources
```

### Core Modules

#### 🧩 Components
Reusable interface elements such as hive cards, status indicators, and graph views.

#### 🧠 Model
Data structures representing hive information, sound patterns, alerts, and monitoring states.

#### 🖥️ View
Main user-facing screens including dashboard, hive detail pages, and settings.

#### 🎛️ Assets
Visual resources and sound-related files used by the app.

---

## 🔮 Future Improvements

- Integration with additional IoT sensors for richer hive monitoring
- Enhanced AI-powered sound analysis for more accurate hive health detection
- Cloud storage and multi-device synchronization
- Expanded analytics and seasonal insights
- Apple Watch companion features for quick monitoring

---

## 🤝 Contributing

Contributions and suggestions are welcome.

1. Fork the repository
2. Create a branch for your feature
3. Make your changes with clear commits
4. Submit a pull request with a detailed description

### Suggested Contribution Areas
- UI improvements
- Better sound analysis models
- Data visualization enhancements
- Notification tuning
- Hardware integration support

---

## 📄 License

This project is distributed under the MIT License. See the `LICENSE` file for more details.

---

## 🌱 Vision

Beezzz aims to revolutionize beekeeping by combining advanced technology with practical beekeeping knowledge. The goal is to make hive monitoring more accessible, proactive, and effective for beekeepers of all experience levels.

---

<div align="center">

**Made with ❤️ for smarter and more accessible beekeeping**

⭐ **Star this repo if you found it interesting!** ⭐

</div>
```

## Adattamenti

Se vuoi renderlo ancora più forte per GitHub, io aggiungerei solo tre cose: screenshot reali dell’app, un piccolo diagramma dell’architettura hardware-app, e una sezione “Demo” con GIF o video breve.

Sources

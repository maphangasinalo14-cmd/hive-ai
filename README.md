# 🛡️ Hive Engine Dashboard

> **The Frontend Interface for the Hive Enterprise Security Response Platform.**
> *Real-time threat monitoring, AI model visualization, and autonomous response telemetry.*

![Version](https://img.shields.io/badge/version-2.0-blue) ![Status](https://img.shields.io/badge/Status-Live-success) ![Tech](https://img.shields.io/badge/Tech-HTML5_|_JS_|_Chart.js-yellow)

## 📖 Overview
The **Hive Engine Dashboard** is a responsive, high-performance SOC (Security Operations Center) interface designed to visualize the activities of the Project Titan ecosystem. It provides real-time telemetry on threat detection, AI decision-making pathways (LSTM/HMM), and system self-healing events.

This repository contains the standalone frontend implementation featuring a dark/light mode engine, interactive data visualization, and a command-driven navigation system.

## 🚀 Key Features

### 📊 Real-Time Analytics
* **Live Threat Timeline:** Visualizes detected vs. blocked threats over 24-hour windows using **Chart.js**.
* **System Status:** Monitors operational uptime and response latency for Threat Detection, Quarantine, and Network Blocking modules.
* **Performance Metrics:** Radar charts comparing detection rates, false positives, and speed across different AI models.

### 🧠 AI & Anomaly Visualization
* **Sequence Detection UI:** Interactive flowcharts showing system call sequences (e.g., `socket` → `connect` → `execve`) and their associated risk scores.
* **LSTM/HMM Transparency:** Visualizes the internal state of neural networks as they process system calls in real-time.
* **Baseline Monitor:** Tracks process behavior (CPU, Memory, Network) against learned baselines to flag zero-day anomalies.

### 💻 Developer Experience
* **Code Diff Viewer:** Built-in "Before vs. After" code comparison blocks to visualize critical bug fixes and hot-patches.
* **Command Palette:** Integrated `Ctrl+K` / `⌘K` quick-action menu for rapid navigation and execution.
* **Live Activity Feed:** A streaming log of system events, critical alerts, and auto-remediation actions.

### 🎨 UI/UX
* **Adaptive Theming:** Robust Dark/Light mode support with CSS variables.
* **Responsive Design:** Fully collapsible sidebar and mobile-optimized layouts.
* **Interactive Elements:** Draggable charts, filterable logs, and dynamic status indicators.

## 🛠️ Tech Stack
* **Core:** Semantic HTML5, CSS3 (Grid/Flexbox), Vanilla JavaScript (ES6+).
* **Visualization:** [Chart.js](https://www.chartjs.org/) (Loaded via CDN).
* **Styling:** Custom CSS variables for theming; no external CSS frameworks required.
* **Icons:** Native Emoji & CSS-based indicators for lightweight performance.

## ⚡ Getting Started

This dashboard is a **standalone file**. No installation, servers, or build steps are required.

1.  **Download** the repository or just the `index.html` file.
2.  **Open** `index.html` directly in any modern web browser (Chrome, Firefox, Edge).
3.  **Note:** Ensure you have an internet connection so the dashboard can load **Chart.js** from the CDN.

## ⌨️ Shortcuts & Commands

| Key Combination | Action |
| :--- | :--- |
| **`Ctrl` + `K`** / **`⌘` + `K`** | Open Command Palette |
| **`Esc`** | Close Modals / Command Palette |
| **`Alt` + `1-9`** | Quick Navigate Sections |

## 📂 Project Structure
```text
.
├── index.html          # The complete dashboard (HTML/CSS/JS)
├── .gitignore          # Git configuration
└── README.md           # Documentation

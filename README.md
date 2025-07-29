# 📡 Smart Network Speed Analyzer

**Smart Network Speed Analyzer** is a Python-based desktop app that measures your internet performance in real-time. It captures **ping**, **download**, and **upload** speeds, calculates an **Internet Health Score**, logs data automatically, and visualizes performance trends using beautiful dark-themed graphs.

---

## 🧾 Description

A Python desktop app that tests internet speed (ping, download, upload), calculates an Internet Health Score, logs results, and displays performance trends using graphs. Useful for real-time monitoring and Computer Networks mini-projects.

---

## 🚀 Features

- ✅ One-click internet speed test
- 📶 Shows ping, download, and upload in real-time
- 📈 Multiple graphs for trends and insights
- 🌙 Dark mode GUI using Tkinter
- 🧠 Smart Internet Health Score (0–10)
- 🕓 Auto logging to `logs.csv` with timestamps
- 📊 Bar chart of latest results
- 📉 Line graphs of historical performance and health

---

## 🖥️ Tech Stack

| Component         | Technology        |
|------------------|-------------------|
| Language          | Python 3.x        |
| GUI Framework     | Tkinter           |
| Speed Test Module | speedtest-cli     |
| Charts/Graphs     | matplotlib        |
| Data Logging      | CSV               |

---

## ⚙️ How It Works

1. **Ping**: Measures latency to the test server (in ms)
2. **Download**: Speed to receive data from the server (in Mbps)
3. **Upload**: Speed to send data to the server (in Mbps)
4. **Health Score**:
score = (download / 10) + (upload / 5) - (ping / 50)
score = min(10, max(0, round(score, 2)))
Higher score = better network

5. **Graphs**:
- Download/Upload/Ping over time
- Internet Health Score trend
- Latest test result as bar chart

---
📚 License
This project is licensed under the MIT License.
You are free to use, modify, and distribute this software, but the author takes no responsibility for misuse.

__Made With__

- Python
- Jupyter Notebook

__About Me__

Name: Sanjanaa S

Course: B.Tech Artificial Intelligence and Data Science

College: Rajalakshmi Institute of Technology

Year: 3rd Year

Email: sanjanaasrinivasan7@gmail.com

LinkedIn: www.linkedin.com/in/sanjanaa-srinivasan-802ba5290

GitHub: https://github.com/Sanjanaa7

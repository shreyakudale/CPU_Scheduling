# 🖥️ CPU Scheduling Visualizer  
![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-black?logo=flask)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-purple?logo=bootstrap)
![Chart.js](https://img.shields.io/badge/Chart.js-Visualization-orange?logo=chartdotjs)
![Plotly](https://img.shields.io/badge/Plotly-Graphs-lightgrey?logo=plotly)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

> 🎯 **An Interactive Operating System Learning Tool**  
A visual simulator for CPU Scheduling Algorithms with performance metrics and graphical execution timeline.

---

## 🚀 Project Overview

The **CPU Scheduling Visualizer** is a web-based application designed to simplify complex Operating System scheduling concepts.

It simulates multiple CPU scheduling algorithms, calculates important performance metrics, and visually displays process execution using dynamic charts and Gantt diagrams.

### 🎓 This helps students:
- 📘 Understand scheduling behavior  
- 📊 Compare algorithm efficiency  
- 🧠 Learn OS concepts visually  

---

## 🎥 Demo Features
- ✨ Add custom processes (Arrival Time, Burst Time, Priority)  
- ✨ Select scheduling algorithm  
- ✨ View Gantt chart execution  
- ✨ Compare performance metrics  
- ✨ Dynamic and interactive UI  
- ✨ Easy-to-use educational interface  

---

## ⚙️ Scheduling Algorithms Implemented
- 🔵 **First Come First Serve (FCFS)**
- 🟢 **Shortest Job First (SJF) – Non Preemptive**
- 🟡 **Shortest Remaining Time First (SRTF)**
- 🔴 **Priority Scheduling (Preemptive / Non-Preemptive)**
- 🟣 **Round Robin (RR)**

---

## 📊 Performance Metrics Calculated
- ⏱️ Turnaround Time (TAT)  
- ⏳ Waiting Time (WT)  
- ⚡ Response Time (RT)  
- 📈 Throughput  
- 💻 CPU Utilization  
- 📊 Average Metrics Comparison  

---

## 🛠️ Tech Stack

### 👨‍💻 Backend
- 🐍 Python 3.x  
- 🌶 Flask  

### 🎨 Frontend
- 🌐 HTML5  
- 🎨 CSS3  
- 💎 Bootstrap 5  
- 🧩 Jinja2 Templates  

### 📊 Visualization
- 📈 Chart.js  
- 📉 Plotly  

### 📦 Other Tools
- 🧮 NumPy  
- 🧾 Pandas  

---

## 📂 Project Structure
```bash
CPU_Scheduling/
│
├── app.py
├── requirements.txt
├── templates/
│   ├── index.html
│   └── response.html
│
├── static/
│   ├── css/
│   └── js/
│
├── README.md
└── REPORT.md

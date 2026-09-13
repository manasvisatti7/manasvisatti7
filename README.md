# Hi there, I'm Manasvi Satti 👋

### 🤖 AI Builder • Full-Stack Developer • Startup Explorer • Hackathon Enthusiast

I’m a **Computer Science Engineering student** passionate about building AI-powered products, intelligent systems, and practical solutions for real-world problems.

My interests lie at the intersection of **Artificial Intelligence, Full-Stack Development, IoT/Edge AI, UI/UX, and Entrepreneurship**. I enjoy taking an idea from concept to prototype and turning technology into products that can create measurable impact.

I’m constantly learning, building, experimenting with new technologies, participating in hackathons, and exploring opportunities to create products that people genuinely find useful.

---

## 🚀 About Me

* 🎓 Computer Science Engineering student at **VRSEC / Siddhartha Academy of Higher Education**
* 🤖 Interested in **Artificial Intelligence & Machine Learning**
* 💻 Exploring **Full-Stack Web Development**
* 🎨 Interested in **UI/UX and product design**
* 🌐 Building practical AI and IoT solutions for real-world problems
* 🏭 Working on **AirGuard AI**, an MSME-focused smart manufacturing project
* 🏆 Active **hackathon participant and project builder**
* 💡 Passionate about **startups, entrepreneurship, and innovation**
* 🌱 Continuously learning and improving my technical skills
* 🎯 Goal: Build technology that creates meaningful real-world impact

---

# 🏭 Featured Project — AirGuard AI

## **AirGuard AI: Smart Compressed Air System Health Monitoring & Energy Optimization Platform**

**AirGuard AI** is an **Industry 4.0/5.0 IoT and cloud analytics platform** designed to help manufacturing MSMEs continuously monitor compressed-air systems, identify abnormal operating conditions, and understand potential energy inefficiencies.

The project is being developed as an **MSME Idea Hackathon 6.0 proposal**, with a proposed project budget of **₹15 Lakhs**.

### 🎯 Problem

Compressed-air systems are widely used in manufacturing industries, but issues such as leakage, abnormal pressure, inefficient operation, excessive power consumption, and poor maintenance can lead to significant operational and energy losses.

AirGuard AI aims to provide MSMEs with an accessible monitoring and decision-support system without requiring a complete replacement of their existing infrastructure.

### 💡 Proposed Solution

AirGuard AI combines:

* 📡 Non-invasive industrial sensing
* ⚙️ ESP32-based edge telemetry
* 🌐 IoT communication
* ☁️ Cloud-based analytics
* 📊 Real-time monitoring dashboards
* 🧠 Machine-specific baselining
* 🚨 Condition-based alerts
* 💰 Energy-loss estimation in **₹/hour**
* 🔄 Optional actuator/relay-based response

### 📊 Parameters Monitored

The proposed system monitors **9 operational parameters**:

1. Line Pressure
2. Flow Rate
3. Compressor Casing Temperature
4. Voltage
5. Current
6. Active Power
7. Machine Runtime
8. Line Moisture
9. Ambient Humidity

### 🧠 Key Engineering Contributions

#### 1. Multi-Parameter Edge Telemetry

Designed a sensor architecture around an **ESP32 edge node** for collecting real-time operational data from compressed-air systems.

#### 2. Edge Data Validation

Proposed a two-level validation mechanism:

* Physical range-bound validation
* Rolling-window stuck-sensor detection

This helps reduce noisy or invalid readings before they reach the cloud analytics layer.

#### 3. Energy & Financial Analytics

Designed an analytics approach that compares live operating conditions against machine-specific baseline behavior to estimate potential energy inefficiency and translate it into an understandable **₹/hour loss indicator**.

#### 4. Machine Health Monitoring

Designed a **0–100 machine health score** together with diagnostic alerts to help operators understand equipment conditions quickly.

### ⚙️ Architecture

```text
┌─────────────────────┐
│  Industrial Sensors │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│    ESP32 Edge Node  │
│                     │
│ • Data Acquisition  │
│ • Range Validation  │
│ • Sensor Validation │
└──────────┬──────────┘
           │
           │ MQTT / WebSocket
           ▼
┌─────────────────────┐
│ Cloud / Backend     │
│ Analytics Engine    │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Decision Engine     │
│                     │
│ • Baseline Analysis │
│ • Health Score      │
│ • Waste Estimation  │
│ • Alerts            │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Monitoring Dashboard│
│                     │
│ • Live Telemetry    │
│ • Machine Health    │
│ • ₹/hr Loss         │
│ • Diagnostics       │
└──────────┬──────────┘
           │
           ▼
     Optional Relay /
     Actuator Feedback
```

### 🔄 Closed-Loop Workflow

**Sense → Validate → Stream → Analyze → Decide → Alert → Act**

1. **Sense** — Industrial sensors capture operating parameters.
2. **Validate** — Edge logic filters invalid and suspicious readings.
3. **Stream** — Telemetry is transmitted to the backend.
4. **Analyze** — Live measurements are compared with baseline behavior.
5. **Decide** — The system calculates health and efficiency indicators.
6. **Alert** — Operators receive actionable diagnostics.
7. **Act** — Optional relay/actuator mechanisms can support corrective actions.

### 🧰 Technology Stack

**Embedded & Hardware**

* ESP32
* Industrial Pressure Transducers
* Compressed-Air Flowmeters
* PZEM-004T Power Monitoring
* Opto-Isolated PCB Design

**Backend & Communication**

* Node.js
* MQTT
* WebSockets

**Frontend**

* HTML5
* CSS3
* JavaScript
* Chart.js

**Analytics**

* Range-Bound Validation
* Rolling-Window Sensor Validation
* Machine Baseline Analysis
* Efficiency Monitoring
* ₹/hour Energy-Loss Estimation

### 💰 Proposed MSME Grant Allocation

| Category                        | Proposed Allocation | Purpose                                                              |
| ------------------------------- | ------------------: | -------------------------------------------------------------------- |
| Technology Development          |           ₹10 Lakhs | Sensors, flowmeters, ESP32 nodes, PCBs, cloud engine and calibration |
| Mentorship & Technical Guidance |            ₹3 Lakhs | Firmware, pneumatic expertise and technical evaluation               |
| Travel & Field Testing          |            ₹2 Lakhs | MSME surveys, installation and pilot testing                         |
| **Total**                       |       **₹15 Lakhs** | **Complete proposed project budget**                                 |

### 📌 Development Status

**Stage:** Prototype / Development

**Proposed TRL:** TRL 4

The software analytics and monitoring architecture are under development, while hardware integration and field validation are being progressed as part of the project.

### 👥 Project Team

* **Team Lead:** Manasvi Satti
* **Team Members:** Saranya Pallapothula, Saranya Vangaveti
* **Academic Mentor:** Dr. K. L. Sailaja
  Department of CSE, VRSEC / Siddhartha Academy of Higher Education

---

# 💼 Other Featured Projects

### 🚀 DealForge AI

An AI-powered client acquisition platform designed to help freelancers discover relevant leads, connect with potential clients, and improve their client-acquisition workflow.

**Tech:** TypeScript • AI • Web Development

---

### 🛡️ Guardian AI Edge Safety

A real-time AI safety monitoring system designed to detect **fire, smoke, and falls** using computer vision and edge-oriented processing.

**Tech:** Python • YOLO • FastAPI • Computer Vision • Edge AI

---

### ❤️ SmartAid AI

An AI-powered volunteer coordination platform designed to connect volunteers with communities requiring immediate assistance.

**Tech:** AI • Web Development • Community Technology

---

### 🎵 Spotify Genre Recommendation

A machine-learning project focused on **music genre classification and song recommendation** based on user preferences and audio characteristics.

**Tech:** Python • Machine Learning • Jupyter Notebook

---

# 🛠️ Tech Stack

### Programming

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge\&logo=c\&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge\&logo=openjdk\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge\&logo=typescript\&logoColor=white)

### AI / Machine Learning

* Artificial Intelligence
* Machine Learning
* Computer Vision
* YOLO
* Edge AI
* Data Analytics

### Web Development

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge\&logo=react\&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge\&logo=nodedotjs\&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge\&logo=html5\&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge\&logo=css3\&logoColor=white)

### Tools & Platforms

* Git & GitHub
* VS Code
* Firebase
* Vercel
* Jupyter Notebook

### IoT / Embedded

* ESP32
* MQTT
* WebSockets
* Sensor Data Acquisition
* Edge Processing

---

# 🏆 Hackathons & Innovation

I actively participate in hackathons and innovation challenges to:

* 💡 Explore emerging technologies
* 🧠 Solve real-world problems
* 🤝 Collaborate with multidisciplinary teams
* 🚀 Build working prototypes
* 🏆 Compete in national and international competitions
* 🌍 Turn ideas into scalable products

---

# 🌱 Currently Building

* 🏭 **AirGuard AI** — Smart manufacturing & energy optimization
* 🤖 AI-powered applications
* 💻 Full-stack web projects
* 🧠 Computer vision and edge-AI solutions
* 🚀 New startup and product ideas
* 🏆 Hackathon prototypes

---

# 🎯 My 2026 Focus

* 🚀 Build

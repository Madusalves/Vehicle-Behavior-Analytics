# 🏎️ CVRT - Vehicle Behavior Analytics
> **Transforming vehicle telemetry in safe driving through gamification and IoT.**

**CVRT** is a Smart City platform that uses real-time telemetry data to educate drivers. The system monitors behaviors, processes complex business rules, and rewards safe and sustainable attitudes on the road.

---

## 🏗️ System Architecture
Here's the data flow from the hardware capture to the management dashboard:

<img width="770" height="590" alt="CVRT drawio" src="https://github.com/user-attachments/assets/18f55907-e10b-495f-aa2c-ced26f333fd1" />

*Caption: Data flow via MQTT, processing in .NET and geospatial persistence.*

---

## 🛠️ Technology Stack

### **Hardware & Edge**
* **ESP32:** Telemetry collection (GPS Neo-6M) and preprocessing.
* **MQTT:** Lightweight transport protocol for IoT (Broker Mosquitto/EMQX).

### **Backend & Infra (The Heart)**
* **.NET Core:** Scalable backend with Clean Architecture.
* **Redis:** High-performance caching for real-time data.
* **PostgreSQL + PostGIS:** Geospatial intelligence for geofencing and routes.
* **Docker:** Environment-wide orchestration for simplified deploy.

### **Frontend & Mobile**
* **Flutter:** Gamified interface (Badges, Leaderboards and Missions).

---

## 🚀 Engineering Differentials
* **Low Latency:** Use of MQTT and Redis to ensure sub-second updates.
* **Scalability:** Architecture ready to support thousands of simultaneous vehicles.
* **Advanced Geofencing:** Geographic calculations performed directly on the database (PostGIS) for maximum efficiency.

---
## 📞 Contact
Interested in telemetry solutions or scalable infrastructure? 
Maria Eduarda - [Linkedin](https://www.linkedin.com/in/mariaeduardaalvesduarte/)

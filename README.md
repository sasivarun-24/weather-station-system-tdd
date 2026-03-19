# weather-station-system-tdd
A Java-based weather station system developed using Test-Oriented Development (TDD), focusing on device status monitoring (W5) using error rates and device age.
# 🌦️ Weather Station System (TDD)

This project is part of the **Test-Oriented Development (TDD)** course and implements a distributed weather station system.

The focus of this implementation is **Unit W5 – Station Status Monitoring**, which evaluates the health of devices based on **error rates and device age**.

---

## 🎯 Project Objective

The system simulates a weather station that:

- Collects environmental data (temperature, rainfall, wind)
- Monitors device health
- Supports maintenance decisions
- Provides real-time system status

---

## 🧠 Focus: W5 – Station Status Monitoring

The W5 unit calculates the **overall station status**:

- 🟢 **Green** → No critical devices  
- 🟡 **Yellow** → Some critical devices  
- 🔴 **Red** → Many critical devices  

### 📌 Decision Logic:
A device is considered **critical** if:
- Error rate ≥ 3  
- OR Age > 10  

Station status is determined based on the number of critical devices.

---

## 🛠️ Tech Stack

- Java
- Test-Oriented Development (TDD)
- Unit Testing Concepts (BVA, Equivalence Partitioning)

---

## 📂 Project Structure

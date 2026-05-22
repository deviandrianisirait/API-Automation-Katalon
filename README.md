# Katalon API Automation + Kafka Integration

## 📌 Overview

This project demonstrates API automation testing using Katalon Studio, including basic REST API testing and Kafka integration for event-driven validation.

---

## 🧪 Test Cases

### 1️⃣ API Test (Katalon Only)

* POST request to create data
* GET request to retrieve data
* Validate response consistency

---

### 2️⃣ Kafka Integration Test

* POST request to create data
* Kafka publishes event message to topic `booking-topic`
* Katalon acts as Kafka consumer
* Validate message content from Kafka

---

## ⚙️ Tech Stack

* Katalon Studio
* RESTful API
* Apache Kafka
* Groovy

---

## 📂 Structure

```text
Test Cases/
Object Repository/
Keywords/
  └── kafka/
Drivers/
Profiles/
Reports/
```

---

## ▶️ How to Run

1. Start Kafka server (`localhost:9092`)
2. Ensure topic `booking-topic` exists
3. Run test cases in Katalon:
   * API Only test
   * Kafka integration test

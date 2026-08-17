# 🌫️ IoT Air Quality Prediction Pipeline – CSC8112 Coursework

This project demonstrates the design and deployment of a full IoT data processing pipeline across **Azure-based Edge and Cloud VMs** using **Docker, MQTT (EMQX), RabbitMQ**, and a time-series **machine learning predictor** for PM2.5 air quality data.

🧪 Developed as part of the **CSC8112 Internet of Things** module at Newcastle University.

---

## 📌 Features

- ✅ Docker-based MQTT Broker (EMQX)
- ✅ IoT data ingestion from Newcastle Urban Observatory
- ✅ Python-based data preprocessing operator
- ✅ RabbitMQ-based message passing to ML engine
- ✅ Daily averaging & outlier filtering
- ✅ PM2.5 trend forecasting for 15 days using Prophet
- ✅ Matplotlib-based visualizations

---

## 🛠️ Tech Stack

| Component        | Tech Used                            |
|------------------|--------------------------------------|
| Data Source       | Newcastle Urban Observatory API      |
| Data Broker (Edge)| EMQX (Docker)                        |
| Preprocessing     | Python (Paho-MQTT, Pika)             |
| Messaging (Cloud) | RabbitMQ + Docker Compose            |
| ML Engine         | Prophet + Pandas + Matplotlib        |
| Deployment        | Azure Lab (Edge + Cloud Ubuntu VMs)  |

---

## 📂 Project Structure

- `docs/`: Screenshots of setup, logs, and results
- `CSC8112-report-samuel-pillai.pdf`: Final coursework report
- `README.md`: This file

---

## 📸 Screenshots

### 🔹 Data Injector Output

![Data Injector](docs/TaskOneSS.png)

### 🔹 Data Injector Confirmation

![Data Injector Log](docs/TaskOne2.png)

### 🔹 Preprocessing Output

![Preprocessing](docs/TaskTwo.png)

### 🔹 RabbitMQ Consumer Waiting

![RabbitMQ Consumer](docs/TaskTwo2.png)

### 🔹 PM2.5 Daily Average Plot

![Averaged PM2.5](docs/TaskThree.png)

### 🔹 PM2.5 Prediction Plot

![Predicted PM2.5](docs/TaskThreePredicted.png)

---

## 📄 License

This project is published under the MIT License.

---

## 👨‍💻 Author

**Karthikeyan Karuppaiah**  
MSc Advanced Computer Science – Newcastle University  
📫 karthikeyan30cse@gmail.com
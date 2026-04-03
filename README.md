# 📊 Log Monitoring & Alert System

A scalable backend system built using **Spring Boot** and **MySQL** for centralized log ingestion, monitoring, search, and alerting based on error patterns and thresholds.

---

## 📌 Features

- 📝 Log ingestion API supporting levels: **INFO, WARN, ERROR**
- 🔍 Advanced log search with filtering by service, level, and timestamp
- 📊 Pagination support for efficient log retrieval
- 🚨 Alerting system to detect abnormal error spikes using threshold rules
- ⚡ Optimized performance using database indexing
- 🔄 Asynchronous processing for improved throughput

---

## 🛠️ Tech Stack

- Java  
- Spring Boot  
- MySQL  
- Spring Data JPA  
- REST APIs  
- Maven  

---

## 🏗️ Architecture

- Layered architecture: Controller → Service → Repository  
- RESTful API-based backend design  
- Structured log storage in MySQL  
- Indexed fields for faster query execution  
- Async processing for log ingestion and alert handling  

---

## 🔗 API Endpoints

### Log Ingestion
- POST `/api/logs` → Add a new log entry  

### Log Search & Filtering
- GET `/api/logs` → Get logs with filters (service, level, time range)  
- GET `/api/logs/paginated` → Paginated log results  

### Alerts
- GET `/api/alerts` → View triggered alerts  

---

## ⚙️ Workflow

1. Application sends logs to ingestion API  
2. Logs are stored in MySQL with structured schema  
3. System processes logs asynchronously  
4. Queries allow filtering, searching, and pagination  
5. Alert system monitors error thresholds and triggers alerts  

---

## 📈 Highlights

- Centralized log monitoring system  
- High-performance querying with indexing  
- Scalable architecture for large log volumes  
- Asynchronous processing for better performance  
- Threshold-based alert detection system  

---

## 🚀 Future Improvements

- Real-time dashboard (Grafana-style UI)  
- Kafka-based log streaming  
- Email/SMS alert notifications  
- ELK stack integration  

---

## 👨‍💻 Author

**Gungun Singhal**  
GitHub: [GungunSinghal03](https://github.com/GungunSinghal03)

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

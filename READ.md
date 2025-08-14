# 🖥️ System Monitoring with Netdata (Docker-Based)

## 📌 Objective
Install and run Netdata using Docker to visualize real-time system and application performance metrics.

---

## 🚀 Setup & Execution
 
### ✅ Step 1: Run Netdata via Docker

```bash
docker run -d --name=netdata -p 19999:19999 netdata/netdata

### ✅ Step 2:  Accessed Dashboard 
Open browser and visit: http://localhost:19999

-  Real-time metrics available:
     - CPU usage
     - Memory consumption
     - Disk I/O
     - Network traffic
     - Docker container stats

### ✅ Step 3: Explore Features

```bash
docker exec -it netdata bash
cd /var/log/netdata
ls

-  View logs like error.log, access.log, health.log

# TASK 7: Monitor System Resources Using Netdata

## 📝 Objective
Install and run **Netdata** using Docker to visualize system and application performance metrics in real time.

## 🛠️ Tools Used
- **Netdata**: Open-source, real-time performance monitoring tool.
- **Docker**: Used to run Netdata in a containerized environment.
- **Web Browser**: To access the monitoring dashboard.

## 🚀 Installation & Usage

### Step 1: Run Netdata using Docker
```bash
docker run -d --name=netdata -p 19999:19999 netdata/netdata
```

### Step 2: Access the Dashboard
Open your browser and go to:  
```
http://localhost:19999
```

## 📊 Features Explored
- Real-time monitoring of:
  - CPU usage
  - Memory usage
  - Disk activity
  - Docker container stats
- Interactive charts and alerts
- Log files under `/var/log/netdata` (inside the container)

## 📷 Deliverables
- **Screenshot** of the Netdata dashboard showing active system metrics.

> *Example screenshot:*  
> ![Netdata Dashboard](screenshot.png)

## 🎯 Outcome
Understood how to use Netdata for lightweight system monitoring and how to quickly set it up using Docker. Explored useful performance charts and alerts that can assist in diagnosing issues.

## 📁 Repository Contents
```
.
├── README.md
├── screenshot.png
├── docker-run-command.txt
└── logs/
```

## 📚 References
- [Netdata Docs](https://learn.netdata.cloud/docs/overview)
- [Docker Hub – netdata/netdata](https://hub.docker.com/r/netdata/netdata)

## 🖼️ Screenshots
- `screenshots/dashboard_metrics.png`

## 📝 Logs
- `logs/netdata_sample.log`

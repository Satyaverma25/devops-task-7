# Task 7 - Monitor System Resources Using Netdata

## 🛠 Tools Used
- **Netdata** (via Docker)

## 🧪 What I Did
- Installed Netdata using Docker
- Accessed dashboard at `http://localhost:19999`
- Monitored system metrics like CPU usage, RAM, Disk I/O
- Took screenshots of real-time performance

## 📸 Screenshot
![Screenshot 2025-05-22 131927](https://github.com/user-attachments/assets/b4c24218-c1ce-4458-9323-315c6b80340d)


## 🧠 What I Learned
- Real-time monitoring using Netdata
- How to track performance KPIs (CPU, RAM, Network)
- How to run Netdata using Docker container

## 🔗 Deployment (Optional)
- Run Netdata with:
```bash
docker run -d --name=netdata -p 19999:19999 netdata/netdata

# 🖥️ System Monitoring with Netdata

This project sets up **Netdata** using Docker to monitor system resources like CPU, memory, disk I/O, and Docker containers in real-time via a web dashboard.

---

## ✅ Objective

To install and run Netdata in Docker, and visualize system performance through interactive charts.

---

## 🛠️ Tools Used

- [Netdata](https://www.netdata.cloud/)
- Docker

---

## 🚀 How to Run

Run the following Docker command to start Netdata:

```bash
docker run -d --name=netdata -p 19999:19999 --cap-add SYS_PTRACE --security-opt apparmor=unconfined netdata/netdata


##Access the dashboard in your browser at:
  http://localhost:19999


##🔍 What You Can Monitor
     CPU Usage

RAM and Swap

Disk I/O

Network Traffic

Docker Containers

System Health Alerts


##📂 Logs
##Inside the container, logs are located at:
  /var/log/netdata


##To access them:
  docker exec -it netdata bash
  cd /var/log/netdata
  ls



---

### 📌 To Add This `README.md` File

Run these commands from the project directory:

```bash
nano README.md







##✍️ Author
##Made with ❤️ by Raunak Mali
##🔗 GitHub


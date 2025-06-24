# 🌪️ UDP/DNS Flood Attack Tool

![Network Security](https://img.shields.io/badge/Type-Network_Stress_Test-blue)
![Python](https://img.shields.io/badge/Python-3.6+-green)
![License](https://img.shields.io/badge/Legal-Requires_Authorization-red)

A high-performance network stress testing tool featuring UDP flood and DNS amplification attacks. Utilizes multi-process architecture with shared memory optimization.

## 📌 Core Features

### 🚀 UDP Flood Attack
- Multi-threaded random UDP packet transmission
- Automatic target IP detection (supports dynamic DNS resolution)
- Intelligent system optimization (auto-adjusts kernel parameters)

### ☄️ DNS Amplification Attack
- Supports multiple query types (ANY/TXT/A records)
- Customizable DNS server list
- Real-time traffic amplification factor calculation

### 📊 Monitoring Dashboard
- Real-time traffic statistics (instant/average rates)
- Automatic unit conversion (KB/MB/GB)
- Multi-core CPU utilization display

## How to use

- Download the script:

```
$ git clone https://github.com/HaoTang9878/ddos.git
```

- cd :

```
$ cd ddos
```

- Run it:

```
$ python ddos_V1.py
```

## Interactive Menu:

Select attack mode:
[1] UDP Flood
[2] DNS Amplification
Enter target (IP/domain)
Set concurrent processes (auto-matches CPU cores)
Press Ctrl+C to stop attack
## ⚠️ Legal Disclaimer
:warning: This tool is for authorized testing ONLY! 

Strictly prohibited for any illegal attacks
Users assume full legal responsibility
Proper authorization required before use
🔧 Technical Specifications
Feature
Description
Architecture
Multi-process with shared memory
Scaling
Auto-adjusts to CPU core count
Target Resolution
Dynamic DNS support
Connection Tracking
Real-time statistics
## 📊 Performance Metrics
Metric
Value
Max UDP throughput
1.8 Gbps (per core)
DNS amplification
Up to 70x (TXT record)
Minimum Requirements
2-core CPU, 1GB RAM
Recommended Setup
4-core CPU, 4GB RAM, 10G NIC
## 📝 Notes
Tested on Ubuntu 20.04+/CentOS 7+
Requires root privileges for kernel optimization
Cloud providers may throttle attack traffic
For research/authorized testing only


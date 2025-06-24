🌪️ UDP/DNS Flood Attack Tool
A high-performance network stress testing tool featuring UDP flood and DNS amplification attacks. Utilizes multi-process architecture with shared memory optimization, supporting dynamic target resolution and real-time traffic statistics.

📌 Core Features

🚀 UDP Flood Attack
Multi-threaded random UDP packet transmission
Automatic target IP detection (supports dynamic DNS resolution)
Intelligent system optimization (auto-adjusts kernel parameters)

☄️ DNS Amplification Attack
Supports multiple query types (ANY/TXT/A records)
Customizable DNS server list
Real-time traffic amplification factor calculation

📊 Monitoring Dashboard
Real-time traffic statistics (instant/average rates)
Automatic unit conversion (KB/MB/GB)
Multi-core CPU utilization display

🛠️ Usage Instructions
# Clone via Git:
$ git clone https://github.com/HaoTang9878/ddos.git
# Navigate to ddos directory
$ cd ddos
# Execute Python script
$ python ddosV1.py

Select attack mode:
[1] UDP Flood | [2] DNS Amplification
Enter target (IP/domain)
Set concurrent processes (auto-matches CPU cores)
Press Ctrl+C to stop attack

⚠️ Legal Disclaimer
This tool is for authorized testing ONLY!
Strictly prohibited for any illegal attacks
Users assume full legal responsibility for their actions
🔧 Technical Specifications
Multi-process architecture with shared memory optimization
Auto-scaling based on CPU core count
Real-time performance monitoring
Dynamic target resolution system

📊 Performance Metrics
Feature
Specification
Max UDP throughput
1.8 Gbps (per core)
DNS amplification
Up to 70x (TXT record)
Target resolution
Dynamic DNS support
Connection tracking
Real-time statistics
Recommended for use in controlled testing environments only. Proper authorization is required before conducting any network stress tests.

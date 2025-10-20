# ⚡ EAP-Project  
**Edge Node Monitoring Dashboard**

---

## 🌍 Locations

### 🛰️ KGSN-1 — *Primary Node*
> Real-time system health overview  

| Category | Metric |
|:--|:--|
| 🔋 **Battery** | <img src="https://kgsn1.hobihaus.com/api/v1/badge.svg?chart=powersupply_capacity.smb1360-battery&alarm=linux_power_supply_capacity&refresh=auto&nocache=1" height="20"/> |
| 🧠 **CPU Usage** | <img src="https://kgsn1.hobihaus.com/api/v1/badge.svg?chart=system.cpu&alarm=10min_cpu_usage&refresh=auto&nocache=1" height="20"/> |
| ⏳ **CPU I/O Wait** | <img src="https://kgsn1.hobihaus.com/api/v1/badge.svg?chart=system.cpu&alarm=10min_cpu_iowait&refresh=auto&nocache=1" height="20"/> |
| 💾 **RAM Usage** | <img src="https://kgsn1.hobihaus.com/api/v1/badge.svg?chart=system.ram&alarm=ram_in_use&refresh=auto&nocache=1" height="20"/> |
| 📡 **Network Packets (1m)** | <img src="https://kgsn1.hobihaus.com/api/v1/badge.svg?chart=net_packets.wlan0&alarm=1m_received_packets_rate&refresh=auto&nocache=1" height="20"/> |
| ⚠️ **Packet Storm (10s)** | <img src="https://kgsn1.hobihaus.com/api/v1/badge.svg?chart=net_packets.wlan0&alarm=10s_received_packets_storm&refresh=auto&nocache=1" height="20"/> |

---

### 🌐 NGDR-1 — *Secondary Node*
> Node under deployment  
🚧 *Coming Soon...*

---

### 🧩 System Notes
- Data pulled live from **Netdata API**  
- Auto-refresh badges every few seconds  
- “No cache” mode for real-time updates  
- Ideal for remote node health monitoring (EarnApp, IoT, or Cloud Tunnels)

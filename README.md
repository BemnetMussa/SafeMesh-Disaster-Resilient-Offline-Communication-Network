
# SafeMesh – Disaster-Resilient Offline Communication Network

## Project Overview

SafeMesh is a peer-to-peer mesh network built for disaster scenarios where cellular and internet infrastructure are unavailable. Using low-cost ESP32 devices and the ESP-NOW protocol, it enables off-grid messaging, multi-hop relaying, SOS alerts with GPS, and a web dashboard for monitoring nodes and messages.

Developed as part of **IETP5201 – Integrated Engineering Team Project**.

## Team Members

| Name | Role | GitHub |
|------|------|--------|
| Abenezer Abebe | Mesh Routing Algorithm | — |
| Aman Abdela | Backend Developer (Web Dashboard) | — |
| Aschalew Daraje | Frontend Developer | — |
| Tsion Wubshet | WebSocket Integration | — |
| Abubeker Assefa | Testing & Documentation | — |
| Yusuf Mohammed | ESP-NOW Firmware (Node A) | — |
| Sirajudin Seid | ESP-NOW Firmware (Node B) | — |
| Ezra Leye | Multi-hop Simulation | — |
| Jalete Kebede | Low-Power Optimization | — |
| Kirubel Asfaw | Power Circuit Design | — |
| Yididya Teklu | GPS Simulation | — |
| Bemnet Mussa | **Team Lead & Researher ** | — |

> Add GitHub profile links where available.

## Features

- Off-grid peer-to-peer messaging
- Multi-hop communication (A → B → C)
- SOS alerts with GPS location
- Real-time web dashboard
- Fully offline operation
- Simulation-first development

## Tech Stack

- **Protocol:** ESP-NOW  
- **Hardware (simulated):** ESP32 (MicroPython)  
- **Simulator:** Wokwi  
- **Backend:** Flask (Python)  
- **Frontend:** HTML, CSS, WebSockets  
- **Version Control:** Git & GitHub  

## Getting Started (Simulation)

### 2-Node Test

1. Open two ESP32 MicroPython projects in Wokwi (separate tabs)
2. Paste `sender.py` into Node A
3. Paste `receiver.py` into Node B
4. Run both simulations
5. View messages in Node B serial monitor

### 3-Node Mesh

1. Open three tabs
2. Use `broadcast_node.py` in all nodes
3. Run all simulations
4. Messages will propagate across all nodes

## Project Status

- ✅ Point-to-point communication working  
- ✅ Broadcast messaging functional  
- 🔄 Multi-hop routing in progress  
- 🔄 Web dashboard development ongoing  
- 🔄 SOS + GPS integration pending  

## Structure

```

SafeMesh/
├── README.md
├── code/
│   ├── sender.py
│   ├── receiver.py
│   ├── broadcast_node.py
│   └── web_dashboard/
│       ├── app.py
│       └── templates/
│           └── index.html
├── docs/
└── reports/

```

## Contributing

Team members contribute via pull requests. All changes are reviewed before merging.

## License

Academic use only.

---

**Team Lead:** Bemnet Mussa  
**Last Updated:** April 2026


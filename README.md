# NetGuard

### Network Port Monitor & Process Manager

> A modern Windows desktop utility for monitoring active network ports, analyzing connections, and managing processes in real time.

---

## Overview

**NetGuard** is a Flutter-based desktop application that provides visibility into system network activity by displaying active TCP and UDP ports along with the processes using them.

Designed for developers, system administrators, and cybersecurity enthusiasts, NetGuard simplifies troubleshooting, port management, and network monitoring through an intuitive graphical interface.

---

## Features

### Real-Time Port Monitoring

Monitor active:

* TCP Connections
* UDP Connections
* Listening Ports
* Established Connections

---

### Process Identification

View detailed information including:

* Port Number
* Process ID (PID)
* Process Name
* Protocol Type
* Local Address
* Remote Address
* Connection State

---

### Smart Search & Filtering

Quickly locate entries by:

* Port Number
* Process Name
* Process ID (PID)

Filter results by:

* All Protocols
* TCP
* UDP

---

### Process Management

Terminate unwanted or conflicting processes directly from the application.

Features include:

* One-click process termination
* Safety confirmation dialogs
* Immediate data refresh

---

### Auto Refresh

Keep network information updated automatically without manual intervention.

---

### System Overview Dashboard

View key metrics such as:

* Total Connections
* Listening Ports
* Active Processes

at a glance.

---

## Tech Stack

| Category     | Technology             |
| ------------ | ---------------------- |
| Framework    | Flutter                |
| Language     | Dart                   |
| Platform     | Windows Desktop        |
| Network Data | Windows Netstat        |
| Process Data | Windows Tasklist / WMI |
| UI           | Material Design        |

---

## Screenshot

![NetGuard Dashboard](assets/screenshots/dashboard.png)

---

## 📂 Project Structure

```text
netguard/
│
├── lib/
│   ├── screens/
│   ├── widgets/
│   ├── services/
│   └── main.dart
│
├── assets/
│   └── screenshots/
│
├── windows/
├── pubspec.yaml
├── README.md
└── LICENSE
```

---

## ⚙️ Requirements

### Supported Platforms

* Windows 10
* Windows 11

### Recommended

Run as Administrator for:

* Full process visibility
* System process management
* Enhanced network information access

---

## Getting Started

### Clone Repository

```bash
git clone https://github.com/<username>/netguard.git
cd netguard
```

### Install Dependencies

```bash
flutter pub get
```

### Run Application

```bash
flutter run -d windows
```

---

## Use Cases

### For Developers

* Identify port conflicts
* Troubleshoot local servers
* Monitor development environments

### For System Administrators

* Inspect active services
* Monitor open ports
* Investigate unusual activity

### For Cybersecurity Enthusiasts

* Analyze network exposure
* Detect suspicious processes
* Understand port-to-process relationships

---

## Learning Outcomes

This project demonstrates:

* Flutter Desktop Development
* Windows Process Management
* Network Monitoring Concepts
* System Programming Fundamentals
* Cybersecurity Basics
* Desktop UI Design

---

## Future Roadmap

Planned enhancements include:

* Dark Mode
* CSV Export
* Connection History
* Resource Monitoring (CPU/RAM)
* IPv6 Analytics
* Process Reputation Lookup
* Threat Intelligence Integration
* Suspicious Port Detection
* Prometheus Metrics Export

---

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

## License

This project is licensed under the **MIT License**.
See the LICENSE file for details.

---

## Support

If you find NetGuard useful, consider giving the repository a **Star ⭐**.
Your support helps improve the project and encourages future development.

---

## Author

**Darshan Suresh**
Cybersecurity Enthusiast • Cloud Security Learner • Flutter Developer
GitHub: https://github.com/DarshanSuresh

---

> **Monitor. Analyze. Control.**
>
> **NetGuard – Your Network, Under Watch.**

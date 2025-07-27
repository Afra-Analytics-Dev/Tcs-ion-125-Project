# Tcs-ion-125-Project
##  Environment Setup (Action Item 1)
- AWS EC2 (Ubuntu, 8GB)
- Docker + Docker Compose installed
- Cybersecurity Tools: Nmap, Metasploit, Hydra, John the Ripper, Traceroute
- IAM user with Admin permissions
- AWS CLI configured

##  Docker Lab Environment (Action Item 2)
- Ubuntu-based custom Docker image
- Services inside container:
  - Apache2 (Web Server)
  - MySQL (Database)
  - Python & Java environments
- Private Docker network with subnet `192.168.50.0/24`
- Static container IP: `192.168.50.10`
- Open ports: `80` (Apache), `3306` (MySQL)

##  Vulnerability & Penetration Testing (Action Item 3)
| Tool        | Target             | Outcome                                 |
|-------------|--------------------|------------------------------------------|
| Traceroute  | 192.168.50.10      | Internal routing confirmed (1 hop)       |
| Nmap        | 192.168.50.10      | Detected open ports (80)                |
| Metasploit  | 192.168.50.10      | TCP port scan completed                  |
| Hydra       | MySQL (192.168.50.10) | Login attempts failed (expected)         |

## 📹 Demo Video
- A 5-minute video walkthrough showing:
  - EC2 setup, Docker image build
  - Container running services
  - Tool-based vulnerability scans

---

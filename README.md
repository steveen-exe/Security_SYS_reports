# Securing the Perimeter – Network Architecture & Monitoring Implementation

## 🛡️ Overview
This project demonstrates a secure enterprise network design using segmentation, Zero Trust principles, and SIEM-based monitoring.

## 🧱 Key Features
- Segmented network with DMZ, internal subnet, and VPN.
- Zero Trust architecture via Enclave Gateway segmentation.
- Real-time log monitoring with ELK Stack and Filebeat.
- Vulnerability assessment and infrastructure hardening.

## 🧠 Technologies Used
- VirtualBox  
- ELK Stack (Elasticsearch, Logstash, Kibana)  
- Filebeat  
- Azure VM  
- VPN  
- Linux Networking  
- Firewall (iptables or similar)

## 📷 Screenshots
![Network Diagram](architecture-diagram.png)
*Network layout for VPN, DMZ, and Internal Segments*

## 📂 Folder Structure
- `network_config/` – Screenshots and configs of network segments
- `SIEM_Setup/` – Docker setup for ELK stack and Filebeat
- `vulnerability_assessment/` – PDF report of findings
- `logs/` – Sample logs ingested by ELK

## 🚀 How to Run
1. Clone the repo.
2. Navigate to `SIEM_Setup/` and run `docker-compose up -d`.
3. Verify Kibana on `localhost:5601`.
4. Generate logs and see real-time monitoring.

## 📑 License
MIT (or whichever license you choose)

# 🧠 Wazuh SIEM Deployment

A hands-on cybersecurity project deploying Wazuh SIEM to detect and respond to threats on a simulated network. It includes agent deployment, log collection, and custom alert rules.

---

## 💡 Objective

Set up a working Wazuh + ELK stack to:
- Collect system logs
- Detect brute-force attempts
- Create dashboards for security insights

---

## 🛠️ Tools & Technologies

- Wazuh
- Docker & Docker Compose
- Kibana
- Filebeat
- Linux VMs

---

## 🔧 Setup Instructions

### 1. Run Wazuh Stack
```bash
cd setup
docker-compose up -d
```

### 2. Add Agent
Run the script on your monitored Ubuntu machine:
```bash
bash agents/ubuntu-agent-setup.sh
```

### 3. Configure Custom Rules
Place your custom rules inside `config/custom-rules.xml` and restart the Wazuh manager container.

---


---


---

## 🙋‍♀️ Author

**Ashley Wenwa**  
[LinkedIn](https://www.linkedin.com/in/ashley-wenwa) · [GitHub](https://github.com/WENWA444)  
Cybersecurity | Cloud Security | CyberShujaa Certified

# Highly-Available-Linux-Automation-Self-Healing-Deployment-System
🎯 Objective

To simulate a real-world DevOps scenario where a freshly provisioned Linux server is:
Bootstrapped automatically,
Application deployed using containers,
Continuously monitored,
Self-healed on failure,
Backed up periodically.

🏗️ Architecture Overview

Linux Server (EC2/VM)
        ↓
setup.sh → installs dependencies
        ↓
deploy.sh → pulls & runs container
        ↓
monitor.sh → health check + restart
        ↓
backup.sh → log/data backup


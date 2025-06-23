# sahyadri-shoonya-cloud
Devops With Chat-GPT
# 🌄 Sahyadri Shoonya Cloud

Welcome to **Sahyadri Shoonya**, a spiritual-tech experiment where the silence of the Sahyadri mountains meets the power of the cloud.

## 🌐 Live Setup

- **Hosted On:** AWS EC2 (Ubuntu 24.04)
- **Web Server:** NGINX
- **Public IP:** [http://44.203.176.177](http://44.203.176.177)
- **Deployed HTML:** `index.html` — a minimalist awakening page

## 🧰 Stack & Skills Used

- 🐧 Linux (Ubuntu EC2)
- ⚙️ NGINX web server setup
- 📡 Public IP accessibility
- 🔐 SSH access via `.pem` key
- 🧠 Git + GitHub version control

## 🔁 How to Deploy

```bash
# Update system
sudo apt update

# Install nginx
sudo apt install nginx -y

# Place HTML
sudo cp index.html /var/www/html/index.html

# Start nginx
sudo systemctl start nginx

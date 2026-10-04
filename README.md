<div align="center">

# ZEFAN

### Network Engineer · Infrastructure · Software

Building networks, infrastructure & software that solve real problems.

<br>

[![GitHub](https://img.shields.io/badge/GitHub-devjeje-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/devjeje)

</div>

---

## 👋 About

I'm an **Informatics student and Network Engineer** focused on building practical systems across networking, infrastructure, automation, and software.

I enjoy working close to the infrastructure — from **MikroTik, VLAN, VPN, and network monitoring** to **Linux, Docker, Proxmox, APIs, and web applications**.

Currently building and experimenting with infrastructure management, network monitoring, automation, and self-hosted systems.

---

## 🛠️ Tech Stack

### 🌐 Networking

<div align="center">

<img src="https://img.shields.io/badge/MikroTik-293133?style=for-the-badge&logo=mikrotik&logoColor=white" />
<img src="https://img.shields.io/badge/UniFi-293133?style=for-the-badge&logo=ubiquiti&logoColor=white" />
<img src="https://img.shields.io/badge/TCP%2FIP-293133?style=for-the-badge" />
<img src="https://img.shields.io/badge/VLAN-293133?style=for-the-badge" />
<img src="https://img.shields.io/badge/VPN-293133?style=for-the-badge" />
<img src="https://img.shields.io/badge/PPPoE-293133?style=for-the-badge" />

</div>

### ⚙️ Infrastructure

<div align="center">

<img src="https://img.shields.io/badge/Linux-293133?style=for-the-badge&logo=linux&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-293133?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Proxmox-293133?style=for-the-badge&logo=proxmox&logoColor=white" />
<img src="https://img.shields.io/badge/Nginx-293133?style=for-the-badge&logo=nginx&logoColor=white" />
<img src="https://img.shields.io/badge/Tailscale-293133?style=for-the-badge&logo=tailscale&logoColor=white" />
<img src="https://img.shields.io/badge/Cloudflare-293133?style=for-the-badge&logo=cloudflare&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub_Actions-293133?style=for-the-badge&logo=githubactions&logoColor=white" />

</div>

### 💻 Development

<div align="center">

<img src="https://img.shields.io/badge/Python-293133?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-293133?style=for-the-badge&logo=javascript&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-293133?style=for-the-badge&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/PHP-293133?style=for-the-badge&logo=php&logoColor=white" />
<img src="https://img.shields.io/badge/Node.js-293133?style=for-the-badge&logo=node.js&logoColor=white" />
<img src="https://img.shields.io/badge/React-293133?style=for-the-badge&logo=react&logoColor=white" />

</div>

### 🗄️ Database & Tools

<div align="center">

<img src="https://img.shields.io/badge/MySQL-293133?style=for-the-badge&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-293133?style=for-the-badge&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-293133?style=for-the-badge&logo=redis&logoColor=white" />
<img src="https://img.shields.io/badge/Git-293133?style=for-the-badge&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/Postman-293133?style=for-the-badge&logo=postman&logoColor=white" />

</div>

---

# 🚀 Featured Projects

## 🛰️ SINTAS

### Infrastructure & Network Monitoring Platform

**SINTAS** is a centralized platform for monitoring and managing network infrastructure.

The project focuses on bringing network devices, infrastructure information, monitoring, and management into a single interface.

### Core Features

- Network monitoring
- Device management
- MikroTik integration
- UniFi integration
- API-based integrations
- Infrastructure visibility
- Network information
- Automated testing
- CI/CD workflow

### Architecture

```text
                         INTERNET
                             │
                             ▼
                    ┌────────────────┐
                    │     SINTAS     │
                    │   Web Panel    │
                    └───────┬────────┘
                            │
             ┌──────────────┼──────────────┐
             │              │              │
             ▼              ▼              ▼
        ┌─────────┐    ┌─────────┐    ┌─────────┐
        │ MikroTik│    │  UniFi  │    │ Servers │
        └─────────┘    └─────────┘    └─────────┘
             │              │              │
             └──────────────┼──────────────┘
                            │
                            ▼
                    Monitoring Layer

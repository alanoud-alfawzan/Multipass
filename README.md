# 🚀 Ubuntu Multipass Instance with Docker and NGINX

This repository contains a `cloud-init.yaml` file that automates the setup of an Ubuntu virtual machine using [Multipass](https://multipass.run/). It updates the system, installs Docker, pulls the NGINX image, and verifies the setup using a `curl` request.

---

## Requirements

- [Multipass](https://multipass.run/) installed on your system

---

## What this `cloud-init.yaml` does

- Updates all system packages (`apt update && apt upgrade`)
- Installs Docker
- Pulls the official NGINX image from Docker Hub
- Runs an NGINX container
- Verifies NGINX is running using `curl http://localhost:8080`

---

## How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name

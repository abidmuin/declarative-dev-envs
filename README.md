# 🚀 Declarative Dev Environments

This repository contains declarative configurations for setting up development environments using **Docker**, **Docker Compose**, **Ansible**, and **Vagrant**.

## 📂 Repository Structure

- **`docker/`** – Dockerfiles & Compose setups for various services.
- **`ansible/`** – Ansible playbooks for automated provisioning.
- **`vagrant/`** – Vagrantfiles for managing VMs.
- **`scripts/`** – Utility scripts for automation.

## 🛠️ Getting Started

### 🐳 Using Docker

To build and run a container:

```bash
cd docker
docker build -t my-container .
docker run -d -p 8080:80 my-container
```

## Folder Structure

```plaintext
declarative-dev-envs/
│── docker/              # Docker-related files
│   ├── Dockerfile       # Example Dockerfile
│   ├── docker-compose.yml # Example Compose setup
│   ├── nginx/           # Example service folder
│   │   ├── Dockerfile
│   │   ├── nginx.conf
│── ansible/             # Ansible playbooks & roles
│   ├── playbook.yml
│   ├── roles/
│── vagrant/             # Vagrant configurations
│   ├── Vagrantfile
│── scripts/             # Helper scripts (optional)
│── .gitignore           # Ignore unnecessary files
│── README.md            # Project documentation
│── LICENSE              # Open-source license (optional)
```

# 🐳 Mastering Docker: From Basics to Advanced Workflows

> "Ship faster. Run anywhere."

Welcome to **DOCKER-LEARNING**. This repository is a comprehensive, hands-on guide documented during my deep dive into containerization. From fundamental architecture to complex networking and registry management, this repo tracks the evolution of a modern DevOps workflow.

---

## 🚀 Repository Overview
This project is structured into modular units, each focusing on a core pillar of the Docker ecosystem.

### 📂 [UNIT 1] - The Foundations
* **Core Architecture:** Understanding the Docker Engine, Images, and Containers.
* **Interactive Environments:** Mastering the `-it`, `-e`, and `-v` flags for dynamic container control.
* **Process Management:** Handling container lifecycles and resource allocation.

### 📂 [UNIT 2] - Advanced Operations & Networking
* **Custom Image Creation:** Deep dive into writing optimized Dockerfiles.
* **Docker Networking:** Understanding Bridge, Host, and Overlay networks.
* **DNS Inside Docker:** Mastering service discovery and internal name resolution.
* **Registry Mastery (GHCR):** Authenticating with GitHub Container Registry and managing access tokens.
* **History & Inspection:** Using `docker history` and `inspect` to audit image layers.

---

## ⚡ Quick Start Command Reference
Example of a multi-parameter container run mastered in this repo:

```bash
docker run -it --name my_app -e APP_ENV=production -v /app/data:/data ubuntu

🤝 Let's Connect
Author: Vansh Arora

Topic: Containerization & DevOps Strategy

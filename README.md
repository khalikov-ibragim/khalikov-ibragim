# Hi, I'm Ibragim 👋

Linux System Administrator with a focus on automation: CI/CD, Docker/Podman,
Ansible, and Bash. I build infrastructure as code and ensure pipelines turn green.

## 📬 Contact

- Telegram: `@Gerund1243`
- Email: `ibrashka155@mail.ru`
- Location: Saint Petersburg; open to remote work and relocation
---

## 📦 Projects

All projects use the same proven pipeline workflow:
`push → lint (yamllint, shellcheck, hadolint) → image build → API integration
tests → publish to Docker Hub → auto-deploy to self-hosted runner`.
Containers: Docker for home use, Podman on RedOS — I work with both.

| Project | Description | Status |
|--------|----------|--------|
| [site_the_sales](https://github.com/khalikov-ibragim/site_the_sales) | Online store: FastAPI, PostgreSQL, nginx, JWT | ![CI](https://github.com/khalikov-ibragim/site_the_sales/actions/workflows/ci.yml/badge.svg) |
| [wordbook](https://github.com/khalikov-ibragim/wordbook) | EN↔RU PWA dictionary with offline mode, TLS, Cloudflare Tunnel | ![CI](https://github.com/khalikov-ibragim/wordbook/actions/workflows/ci.yml/badge.svg) |
| [chat-messenger](https://github.com/khalikov-ibragim/chat-messenger) | Real-time chat: Socket.IO, Redis, PostgreSQL | ![CI](https://github.com/khalikov-ibragim/chat-messenger/actions/workflows/ci.yml/badge.svg) |
| [file-gallery](https://github.com/khalikov-ibragim/file-gallery) | File storage: MinIO (S3), PostgreSQL | ![CI](https://github.com/khalikov-ibragim/file-gallery/actions/workflows/ci.yml/badge.svg) |

**Integration tests** are written in Python (`requests`) and verify not only health status
but also business logic: CRUD operations, search, registration, duplicate handling,
WebSocket message delivery, and file upload/deletion. Reports are stored as run artifacts.

**Server automation** via Ansible: inventory → package installation → container startup
→ health check verification using the `uri` module. The playbook is idempotent
(re-running it results in `changed=0`). Tested on a RedOS virtual machine. ---

## 🧰 Tech Stack

**Linux:** RedOS, Debian, Rocky — systemd, LVM, permissions, package management, CLI
**Networking:** TCP/IP, OSI, VLAN, routing, DNS, DHCP, iptables, tcpdump, Nmap, network diagnostics
**Servers:** nginx, Apache, Postfix/Dovecot, Samba, DNS, KVM/virtualization
**Containers & CI/CD:** Docker, Docker Compose, Podman, GitHub Actions, self-hosted runner
**Automation:** Ansible (playbooks), Bash, PowerShell, Python
**Monitoring:** Zabbix, Prometheus, Grafana
**Windows:** Active Directory, GPO, Kaspersky Endpoint Security, Trassir
**Infrastructure as Code:** Terraform, Ansible
**InfoSec Reports:** OWASP Top 10, SQL injection, XSS, brute-force

---

## 🧭 Current Focus

- CI/CD with GitHub Actions and self-hosted runner
- Ansible: playbooks and roles
- Terraform: Yandex Cloud
- Kubernetes: k3s
- Monitoring with Prometheus and Grafana

---

## 🔐 Information Security Reports

- [Security-Reports](https://github.com/khalikov-ibragim/Security-Reports) — OWASP Juice Shop:
SQL injection (union-based, authentication bypass), XSS, HTTP header analysis
- [Security-Scripts](https://github.com/khalikov-ibragim/Security-Scripts) — network scanners,
brute-force, header validation

## 📫 Contact

- GitHub: [khalikov-ibragim](https://github.com/khalikov-ibragim)

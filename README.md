# Ansible_Project 🛠️

A hands-on **Ansible** project to automate server provisioning, configuration management, and service deployment in a clean and scalable way. Built for DevOps engineers and System Administrators looking to reduce manual work and maintain consistency across environments.

---

## 📌 Project Overview

This repository includes:

- Playbooks for installing and configuring Linux servers.
- Modular Roles to organize tasks and variables.
- Inventory and SSH setup for target hosts.
- Practical examples for managing services like Apache, Nginx, and MySQL.
- Support for multi-environment setups (e.g., staging, production).

---

## 🚀 Requirements

Before running the project, ensure you have:

- Python 3.6+
- Ansible 2.10+
- SSH access to your target servers
- A Linux system (recommended: Ubuntu or CentOS)

---

## ⚙️ Installation

1. **Clone the project:**

```bash
git clone https://github.com/MohammedOsamaHassan/Ansible_Project.git
cd Ansible_Project
```

2. **Install Ansible:**

```bash
sudo apt update
sudo apt install ansible -y
```

3. **Edit the `inventory.ini` file to match your environment.**

---

## 🧪 How to Use

To run the main playbook:

```bash
ansible-playbook -i inventory.ini site.yml
```

Feel free to explore the roles and customize them based on your setup and needs.

---

## 📁 Project Structure
```text
Ansible_Project/
│
├── inventory.ini           # Hosts inventory
├── playbook.yml            # Main playbook entry
├── roles/                  # Organized Ansible roles
│   ├── apache/             # Installs and configures Apache
│   │   └── tasks/
│   │       └── main.yaml           # Apache role tasks
│   ├── mysql/              # Installs and configures MySQL
│   │   └── tasks/
│   │       └── main.yaml           # MySQL role tasks
│   ├── php/                # Installs PHP and extensions
│   │   └── tasks/
│   │       └── main.yaml           # PHP role tasks
│   └── wordpress/          # Installs and configures WordPress
│       ├── tasks/
│       │   └── main.yaml           # WordPress role tasks
│       └── templates/              # Configuration templates for WordPress
│           ├── wordpress.confUbuntu.j2     # Apache config for Ubuntu
│           └── wordpressCentOs.conf.j2     # Apache config for CentOS
└── README.md               # Project documentation

```

---

## 👥 Contributing

Have a new idea or improvement?  
Feel free to open a pull request or issue! Contributions are always welcome 💡

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## ✨ Author

- **Mohammed Osama Hassan**  
[GitHub Profile](https://github.com/MohammedOsamaHassan)

---

## 💬 Questions?

Open an issue on GitHub or reach out for support or collaboration 🤝

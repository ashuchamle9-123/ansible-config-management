# 🚀 Ansible Configuration Management Project

## 📌 Objective

Automate server configuration using Ansible playbooks and deploy a web server without manual intervention.

---

## 🛠️ Project Overview

This project demonstrates how to use Ansible for configuration management by automating the setup of a web server on an AWS EC2 instance.

---

## ⚙️ Steps Performed

* Launched an EC2 instance (Ubuntu)
* Installed Ansible on the server
* Created an inventory file
* Wrote an Ansible playbook
* Installed Apache web server automatically
* Started and enabled Apache service
* Deployed a custom HTML page

---

## 📂 Project Structure

```
ansible-project/
│── hosts
│── playbook.yml
│── README.md
```

---

## 📜 Playbook Explanation

* Install Apache using apt module
* Start and enable Apache service
* Deploy index.html file using copy module

---

## 🌐 Output

After running the playbook, the web server displays:

👉 Hello from Ansible Project 🚀

Access using:

```
http://13.234.35.195
```

---

## 🧰 Tools & Technologies Used

* AWS EC2
* Ansible
* Linux (Ubuntu)
* Git & GitHub

---

## 💡 Key Concepts Learned

* Configuration Management
* Infrastructure Automation
* Ansible Playbooks
* Idempotency in Ansible
* Remote Server Management

---

## 🔥 Future Improvements

* Use multiple EC2 instances (real-world setup)
* Implement Ansible roles
* Deploy Node.js / PHP application
* Integrate with AWS RDS
* Use CI/CD pipeline (Jenkins/GitHub Actions)

---

## 👨‍💻 Author

ashuchamle9-123

---



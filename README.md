# 🐇 RabbitMQ Cluster Setup Using Ansible

This Ansible playbook automates the installation and configuration of a **RabbitMQ cluster** on two or more nodes. It includes optional pre-tasks to clean existing RabbitMQ and Erlang installations and sets up a clustered environment with custom user configuration.

---

## 📌 Author

**jashi111**

---

## 📦 Features

- Optional purge of existing RabbitMQ/Erlang setups
- RabbitMQ and Erlang installation via trusted APT repositories
- System cleanup (logs, config, user, etc.)
- Configuration of `/etc/hosts` for cluster node recognition
- Erlang cookie synchronization between nodes
- RabbitMQ cluster setup (`join_cluster`)
- Management plugin enablement
- Custom RabbitMQ user creation with admin privileges

---

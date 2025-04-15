# Containerization


This project demonstrates how to configure and manage container networking using Docker's default bridge network on an AWS EC2 instance. It showcases internal container communication, host-container interaction, and outbound internet access through NAT.

## 🔧 Technologies Used
- Docker
- Linux Networking Tools
- AWS EC2

## 📌 Project Overview

This setup includes:

- Deployment of multiple Docker containers on a single EC2 host.
- Configuration of the default bridge network for container-to-container communication.
- Usage of virtual Ethernet (veth) pairs to connect containers to the host network.
- NAT setup for enabling internet access from containers.
- Verification and troubleshooting using Docker CLI and Linux networking commands.

## 🚀 Features

- Internal communication between containers on the same Docker host.
- Two-way communication between containers and the host system.
- Internet access from containers through host-managed NAT.
- Secure and isolated container networking.
- Hands-on demonstration of Docker's built-in networking capabilities.

---
sidebar_position: 3
title: Technical Requirement
---

# Server Requirements and Deployment Details

#### We are excited to assist you with the deployment of our tool, Athena Guard, on your on-premises server. Below, you will find the detailed requirements and configurations necessary for a smooth and efficient setup.

## **Servers requirements based on environments**

### **UAT Server:**
* **Processor**: 4 vCPUs
* **Memory (RAM)**: At least 8 GB
* **Storage**: 256 GB (upgradable)

 **Software Requirements**
* Operating System: Ubuntu Server 24.0 LTS
* Network Configuration: Low latency and high bandwidth
* Node.js: Version 20.x or later
* npm: For managing dependencies
* PostgreSQL: Version 15 or later
* Backup Tools: Tools like pg_dump for backups
* Configuration: Ensure proper configuration in postgresql.conf for performance tuning
* Docker
* Docker Compose: For managing multiple containers
* Reverse-proxy - Nginx or Apache

### **Production Servers:**
1. **Frontend Server:**
   * **Processor**: 4 vCPUs
   * **Memory (RAM)**: 16 GB
   * **Storage**: 80 GB SSD
   * **Network**: High bandwidth to handle user traffic
   * **Operating System**: Ubuntu Server (24.0 LTS)


   **Software Requirements:**
   1. Node.js: Version 20.x or later
   1. npm or Yarn: Package managers for installing dependencies
   1. Docker
   1. Docker Compose: For managing multiple containers
   1. Reverse-Proxy - Nginx or Apache
   1. Java: Latest stable version
   
2. **Backend Server:**
   * **Processor**: 4 vCPUs
   * **Memory (RAM)**: 16 GB
   * **Storage**: 100 GB SSD (upgradable)
   * **Network**: High bandwidth to handle user traffic
   * **Operating System**: Ubuntu Server (24.0 LTS)

   **Software Requirements:**
   1. Node.js: Version 20.x or later
   1. npm or Yarn: For managing dependencies
   1. Docker
   1. Docker Compose: For managing multiple containers
   1. Reverse-Proxy - Nginx or Apache
   1. Java: Latest stable version

3. **Database Server:**
   * **Processor**: 8 vCPUs
   * **Memory (RAM)**: 32 GB
   * **Storage**: 100 GB SSD (upgradable)
   * **Network**: High bandwidth to handle database queries
   * **Additional**: Ensure fast SSD storage for better performance
   * **Operating System**: Ubuntu Server (24.0 LTS)

    **Software Requirements:**
   1. PostgreSQL: Version 15 or later
   1. pgAdmin: Optional, for database management
   1. Backup Tools: Tools like pg_dump for backups
   1. Configuration: Ensure proper configuration in postgresql.conf for performance tuning
   1. Docker
   1. Docker Compose: For managing multiple containers
   1. Java: Latest stable version

## **Deployment & Access Requirements**
* **Container Orchestration**: Docker and Docker Compose for managing multiple containers
* **Networking & Ports**:
   * Port 80, 443: For web access
   * Port 5432: PostgreSQL and Power BI
* **Admin Access**:
   * Ability to install and manage Docker containers
   * Ability to configure firewall and network settings
## **Custom Domain**
To ensure seamless access for your team, we will need to expose a custom domain. Please provide the necessary DNS configurations and any specific requirements you may have for this setup.
## **Security & Backup Recommendations**
* **Firewall Configuration**: UFW (Linux) or Windows Firewall with rules for required ports
* **Database Backup**: Scheduled backups for PostgreSQL containers
## **Additional Hardware Requirements**
We also require **two laptops** with Docker installed for publishing changes to the server. Below are the recommended configurations for these laptops:
### **Laptop Configuration:**
* **Processor**: Intel Core i7 or AMD Ryzen 7
* **Memory (RAM)**: 16 GB
* **Storage**: 512GB SSD
* **Operating System**: Ubuntu (preferred) or Windows 11
* **Additional Software**: Docker Engine (latest stable version), Docker Compose (latest version)
# MongoDB Ops Manager Course

Welcome to the **MongoDB Ops Manager Course** repository! This repository contains all the materials, tutorials, and resources for learning MongoDB Ops Manager from beginner to advanced levels.

---

## **Course Overview**

This course is divided into three main sections:

1. **Beginner**: Learn the basics of MongoDB Ops Manager, including installation, configuration, and basic deployments.
2. **Intermediate**: Dive deeper into managing deployments, monitoring, backups, and security.
3. **Advanced**: Explore advanced topics like automation, Kubernetes integration, API usage, and troubleshooting.

---

## **Table of Contents**

- [1. Beginner Section](#1-beginner-section)
  - [1.1 Introduction](#11-introduction)
  - [1.2 Installation](#12-installation)
  - [1.3 Deployments](#13-deployments)
  - [1.4 Monitoring](#14-monitoring)
- [2. Intermediate Section](#2-intermediate-section)
  - [2.1 Managing Deployments](#21-managing-deployments)
  - [2.2 Monitoring and Alerts](#22-monitoring-and-alerts)
  - [2.3 Backup and Restore](#23-backup-and-restore)
  - [2.4 Security](#24-security)
- [3. Advanced Section](#3-advanced-section)
  - [3.1 Automation](#31-automation)
  - [3.2 Advanced Security](#32-advanced-security)
  - [3.3 API Usage](#33-api-usage)
  - [3.4 Troubleshooting](#34-troubleshooting)
  - [3.5 Migrations](#35-migrations)
- [4. Examples](#4-examples)
  - [4.1 Standalone Deployment](#41-standalone-deployment)
  - [4.2 Replica Set](#42-replica-set)
  - [4.3 Sharded Cluster](#43-sharded-cluster)
- [5. Resources](#5-resources)
  - [5.1 MongoDB Documentation](#51-mongodb-documentation)
  - [5.2 Third-Party Tools](#52-third-party-tools)
  - [5.3 Cheatsheets](#53-cheatsheets)
- [Contributing](#contributing)
- [License](#license)
- [Connect with Me](#connect-with-me)

---

## **1. Beginner Section**

### **1.1 Introduction**
MongoDB Ops Manager is a management tool for MongoDB deployments. It provides automation, monitoring, backup, and scaling capabilities.

#### **Architecture**
- **Components**: Ops Manager Server, MongoDB Agents, Backing Databases.
- **How It Works**: Agents report metrics to Ops Manager, which processes and displays them.

#### **Example Deployments**
- Simple Test Deployment: A single-node setup for learning purposes.

---

### **1.2 Installation**
#### **Checklist**
- Ensure your system meets the hardware and software requirements.

#### **Hardware & Software Requirements**
- Minimum 4 CPU cores, 8 GB RAM, 10 GB disk space.

#### **Install Backing Databases**
- Install MongoDB as the backing database for Ops Manager.

#### **Install Ops Manager**
- Choose your installation method: RPM, DEB, or Archive.

#### **Configure Ops Manager**
- Set up the Ops Manager application and configure basic settings.

---

### **1.3 Deployments**
#### **Provision Servers**
- Use automation to provision servers for MongoDB deployments.

#### **Add Existing Processes**
- Add existing MongoDB processes to Ops Manager for monitoring.

#### **Deploy a Standalone Instance**
- Deploy a standalone MongoDB instance using Ops Manager.

---

### **1.4 Monitoring**
#### **View Deployment Metrics**
- Monitor replica sets and sharded clusters.

#### **Third-Party Integrations**
- Integrate Ops Manager with Slack, PagerDuty, and Microsoft Teams.

---

## **2. Intermediate Section**

### **2.1 Managing Deployments**
#### **View All Clusters**
- Monitor and manage all clusters from the Ops Manager interface.

#### **Edit Deployment**
- Modify deployment configurations as needed.

#### **Convert Standalone to Replica Set**
- Convert a standalone instance to a replica set.

#### **Add/Remove Shards**
- Scale your sharded cluster by adding or removing shards.

---

### **2.2 Monitoring and Alerts**
#### **Analyze Slow Queries**
- Identify and optimize slow queries.

#### **Improve Schema**
- Reduce $lookup, unbounded arrays, and large document sizes.

#### **Configure & Resolve Alerts**
- Set up alerts for replication lag, lost primary, and more.

---

### **2.3 Backup and Restore**
#### **Back Up**
- Create backups of your MongoDB deployments.

#### **Manage Backups**
- Edit snapshot expiration and delete snapshots.

#### **Restore**
- Restore from snapshots or point-in-time backups.

---

### **2.4 Security**
#### **Configure Firewall**
- Secure Ops Manager with firewall rules.

#### **Secure Connections**
- Enable TLS/SSL for secure communication.

---

## **3. Advanced Section**

### **3.1 Automation**
#### **Deploy Replica Set**
- Automate replica set deployments.

#### **Deploy Sharded Cluster**
- Automate sharded cluster deployments.

#### **Kubernetes Integration**
- Deploy MongoDB using Kubernetes Operator.

---

### **3.2 Advanced Security**
#### **Configure LDAP/SAML**
- Integrate Ops Manager with LDAP/SAML for authentication.

#### **Rotate Master KMIP Keys**
- Rotate encryption keys for enhanced security.

#### **Enable Auditing**
- Enable auditing for compliance and security.

---

### **3.3 API Usage**
#### **Overview of Ops Manager API**
- Learn how to use the Ops Manager API.

#### **Automating Cluster Deployment**
- Automate cluster deployments using the API.

---

### **3.4 Troubleshooting**
#### **Authentication Issues**
- Resolve common authentication problems.

#### **Backup Issues**
- Troubleshoot backup failures.

#### **Monitoring Issues**
- Diagnose and fix monitoring problems.

---

### **3.5 Migrations**
#### **Migrate to MongoDB Atlas**
- Migrate your Ops Manager deployments to MongoDB Atlas.

#### **Upgrade Ops Manager**
- Upgrade Ops Manager to the latest version.

---

## **4. Examples**

### **4.1 Standalone Deployment**
#### **Steps**
1. Provision a server.
2. Deploy a standalone MongoDB instance using Ops Manager.
3. Verify the deployment.

---

### **4.2 Replica Set**
#### **Steps**
1. Provision three servers.
2. Deploy a replica set using Ops Manager.
3. Verify the replica set.

---

### **4.3 Sharded Cluster**
#### **Steps**
1. Provision multiple servers.
2. Deploy a sharded cluster using Ops Manager.
3. Verify the sharded cluster.

---

## **5. Resources**

### **5.1 MongoDB Documentation**
- [MongoDB Ops Manager Documentation](https://docs.mongodb.com/ops-manager/)
- [MongoDB University](https://university.mongodb.com/)

---

### **5.2 Third-Party Tools**
- **Slack**: For alert notifications.
- **PagerDuty**: For incident management.
- **Prometheus**: For advanced monitoring.

---

### **5.3 Cheatsheets**
- **Ops Manager CLI Commands**
- **MongoDB Query Cheatsheet**

---

## **Contributing**

Contributions are welcome! If you'd like to improve this course or add new content, please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a pull request.

---

## **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## **Connect with Me**

- **GitHub**: [lamoregedion](https://github.com/lamoregedion)
- **LinkedIn**: [Gedion Lamore](https://linkedin.com/in/gedionalamore)
- **Email**: gedionable@gmail.com

---

Happy Learning! 🚀
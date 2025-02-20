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

- [Beginner Section](#beginner-section)
  - [Introduction](#introduction)
  - [Installation](#installation)
  - [Deployments](#deployments)
  - [Monitoring](#monitoring)
- [Intermediate Section](#intermediate-section)
  - [Managing Deployments](#managing-deployments)
  - [Monitoring and Alerts](#monitoring-and-alerts)
  - [Backup and Restore](#backup-and-restore)
  - [Security](#security)
- [Advanced Section](#advanced-section)
  - [Automation](#automation)
  - [Advanced Security](#advanced-security)
  - [API Usage](#api-usage)
  - [Troubleshooting](#troubleshooting)
  - [Migrations](#migrations)
- [Examples](#examples)
  - [Standalone Deployment](#standalone-deployment)
  - [Replica Set](#replica-set)
  - [Sharded Cluster](#sharded-cluster)
- [Resources](#resources)
  - [MongoDB Documentation](#mongodb-documentation)
  - [Third-Party Tools](#third-party-tools)
  - [Cheatsheets](#cheatsheets)
- [Contributing](#contributing)
- [License](#license)
- [Connect with Me](#connect-with-me)

---

## **Beginner Section**

### **Introduction**
MongoDB Ops Manager is a management tool for MongoDB deployments. It provides automation, monitoring, backup, and scaling capabilities.

#### **Architecture**
- **Components**: Ops Manager Server, MongoDB Agents, Backing Databases.
- **How It Works**: Agents report metrics to Ops Manager, which processes and displays them.

#### **Example Deployments**
- Simple Test Deployment: A single-node setup for learning purposes.

---

### **Installation**
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

### **Deployments**
#### **Provision Servers**
- Use automation to provision servers for MongoDB deployments.

#### **Add Existing Processes**
- Add existing MongoDB processes to Ops Manager for monitoring.

#### **Deploy a Standalone Instance**
- Deploy a standalone MongoDB instance using Ops Manager.

---

### **Monitoring**
#### **View Deployment Metrics**
- Monitor replica sets and sharded clusters.

#### **Third-Party Integrations**
- Integrate Ops Manager with Slack, PagerDuty, and Microsoft Teams.

---

## **Intermediate Section**

### **Managing Deployments**
#### **View All Clusters**
- Monitor and manage all clusters from the Ops Manager interface.

#### **Edit Deployment**
- Modify deployment configurations as needed.

#### **Convert Standalone to Replica Set**
- Convert a standalone instance to a replica set.

#### **Add/Remove Shards**
- Scale your sharded cluster by adding or removing shards.

---

### **Monitoring and Alerts**
#### **Analyze Slow Queries**
- Identify and optimize slow queries.

#### **Improve Schema**
- Reduce $lookup, unbounded arrays, and large document sizes.

#### **Configure & Resolve Alerts**
- Set up alerts for replication lag, lost primary, and more.

---

### **Backup and Restore**
#### **Back Up**
- Create backups of your MongoDB deployments.

#### **Manage Backups**
- Edit snapshot expiration and delete snapshots.

#### **Restore**
- Restore from snapshots or point-in-time backups.

---

### **Security**
#### **Configure Firewall**
- Secure Ops Manager with firewall rules.

#### **Secure Connections**
- Enable TLS/SSL for secure communication.

---

## **Advanced Section**

### **Automation**
#### **Deploy Replica Set**
- Automate replica set deployments.

#### **Deploy Sharded Cluster**
- Automate sharded cluster deployments.

#### **Kubernetes Integration**
- Deploy MongoDB using Kubernetes Operator.

---

### **Advanced Security**
#### **Configure LDAP/SAML**
- Integrate Ops Manager with LDAP/SAML for authentication.

#### **Rotate Master KMIP Keys**
- Rotate encryption keys for enhanced security.

#### **Enable Auditing**
- Enable auditing for compliance and security.

---

### **API Usage**
#### **Overview of Ops Manager API**
- Learn how to use the Ops Manager API.

#### **Automating Cluster Deployment**
- Automate cluster deployments using the API.

---

### **Troubleshooting**
#### **Authentication Issues**
- Resolve common authentication problems.

#### **Backup Issues**
- Troubleshoot backup failures.

#### **Monitoring Issues**
- Diagnose and fix monitoring problems.

---

### **Migrations**
#### **Migrate to MongoDB Atlas**
- Migrate your Ops Manager deployments to MongoDB Atlas.

#### **Upgrade Ops Manager**
- Upgrade Ops Manager to the latest version.

---

## **Examples**

### **Standalone Deployment**
#### **Steps**
1. Provision a server.
2. Deploy a standalone MongoDB instance using Ops Manager.
3. Verify the deployment.

---

### **Replica Set**
#### **Steps**
1. Provision three servers.
2. Deploy a replica set using Ops Manager.
3. Verify the replica set.

---

### **Sharded Cluster**
#### **Steps**
1. Provision multiple servers.
2. Deploy a sharded cluster using Ops Manager.
3. Verify the sharded cluster.

---

## **Resources**

### **MongoDB Documentation**
- [MongoDB Ops Manager Documentation](https://docs.mongodb.com/ops-manager/)
- [MongoDB University](https://university.mongodb.com/)

---

### **Third-Party Tools**
- **Slack**: For alert notifications.
- **PagerDuty**: For incident management.
- **Prometheus**: For advanced monitoring.

---

### **Cheatsheets**
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
# MongoDB Ops Manager

MongoDB Ops Manager can automate, monitor, and back up your MongoDB infrastructure.

---

## **Automation**

Ops Manager Automation enables you to configure and maintain MongoDB nodes and clusters. MongoDB Agents using Automation on each MongoDB host can maintain your MongoDB deployments. You can install the MongoDB Agent. Automation can add hosts and deploy and upgrade new or existing clusters.

---

## **Monitoring**

Ops Manager Monitoring provides real-time reporting, visualization, and alerting on key database and hardware indicators.

### **How Monitoring Works**

When you activate Monitoring on a MongoDB host, Monitoring collects statistics from the nodes in your MongoDB deployment. The Agent transmits database statistics back to Ops Manager to report deployment status in real time. You can set alerts on indicators you choose.

---

## **Backup**

Ops Manager Backup provides scheduled snapshots and point-in-time recovery of your MongoDB replica sets and sharded clusters.

### **How Backup Works**

When you activate Backup for a MongoDB deployment, Backup takes snapshots of data from the MongoDB processes you have specified.

> **NOTE**: Sharded clusters and replica sets are the only deployment types you can back up if your databases run MongoDB FCV 4.2 and earlier. To back up a standalone `mongod` process running MongoDB FCV 4.2 or earlier, you must convert it to a single-member replica set.

---
# Azure Setup and Governance Summary Report

## 1. Region Selection
* **Chosen Region:** US-EAST
* **Latency Optimization:** This region was selected because it is geographically closest to Nigeria, providing the lowest network latency and highest performance for deployed workloads.

## 2. Shared Responsibility Model Application
For this assignment, a **Storage Account (PaaS - Platform as a Service)** was deployed. Under the Microsoft Shared Responsibility Model:

* **Microsoft's Responsibility:** Azure manages physical security of the datacenters, hardware maintenance, operating system patching, infrastructure networking, and underlying virtualization layers.
* **My (The User's) Responsibility:** I am responsible for data classification, configuration of Access Control (IAM/RBAC), data encryption settings, network firewall rules (IP whitelisting), and securing access keys/shared access signatures (SAS).

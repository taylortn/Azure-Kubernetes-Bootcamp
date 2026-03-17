# Lab 1: Azure Fundamentals (AZ-900)

## Objective
Deploy a basic Azure environment including a Resource Group, Storage Account, and Virtual Machine.

---

## Architecture
This lab includes:
- Resource Group (rg-azure-lab01)
- Storage Account
- Virtual Machine

---

## Steps Performed
1. Created Resource Group (rg-azure-lab01) in East US region
      - A Resource Group is a logical container in Azure used to organize and manage related resources like VMs, storage, and networking. It allows you to manage lifecycle, permissions, and cost as a unit.
2. Created Storage Account (khameleonstorage01) with Standard performance and LRS redundancy
      - A Storage Account in Azure is a scalable and secure service that stores data such as blobs, files, queues, and tables. It provides a globally accessible namespace for cloud data.
3. Deployed Virtual Machine (vm-lab01) with SSH access enabled (port 22)
      - I configure inbound NSG rules to allow SSH on port 22, then connect using the VM’s public IP.
4. Connected to VM using SSH (port 22)
5. Updated Linux system packages
6. Installed and started NGINX web server
     - I deployed a Linux VM, configured SSH access, connected remotely, and installed a web server to validate external connectivity.
---

## Key Concepts
- Resource Group: Logical container for Azure resources
- Storage Account: Stores data in Azure
- Virtual Machine: Compute resource used to run applications

---

## Outcome
- Successfully deployed and verified Azure resources in the Azure Portal.
- Successfully created and verified a Resource Group in Azure to organize all lab resources.
- Provisioned a Storage Account to store cloud data with high availability and scalability.
- Successfully provisioned a Virtual Machine and adapted deployment based on available Azure subscription resources.
- Successfully connected to the VM and deployed a running web server accessible via public IP.

---

## Real-World Use Case
This setup represents the foundation of cloud infrastructure used in enterprise environments for hosting applications and storing data.

---

## Next Steps
- Add screenshots of deployed resources
- Document Azure CLI commands

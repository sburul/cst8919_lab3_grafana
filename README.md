# CST8919 - DevOps – Security and Compliance - Lab3
## LabAssignment:Grafana Installation and Dashboard Creation forUbuntu Server Performance

## Objective:

This lab guides you through the installation of Grafana on an Ubuntu machine, setting up the Azure
Monitor agent for performance metrics collection, and creating a dashboard in Grafana to visualize
the collected metrics.

## Prerequisites:

- • An Ubuntu server (version 18.04 or later)
- • An Azure account with permissions to create and manage Azure resources
- • Basic understanding of Linux command line interface




## Lab Steps:

Step-1 : A VM created for Grafana

![A VM created for Grafana](/Screenshots/creating-vm.png)


Step-2 Grafana installed and configured connecting VM via SSH

![Grafana](/Screenshots/grafana-installation.png)


Step-4 – An inbound rule (3000) added to network rules to login Grafana via browser

![network rules ](/Screenshots/vm-port.png)
 

Step-5  - VM’s managed identity Monitoring Reader Role on Azure Monitor and Reader Role on your Subscription.

![Role](/Screenshots/reader-role.png)



![Role](/Screenshots/monitor-reader-role.png)


Step-7 – Logged In Garafana 

![Logged In Garafana ](/Screenshots/login-grafana.png)


Step-8 – Enabled managed identity authentication for data sources by editing Grafana.ini

![Enabled managed identity](/Screenshots/managed_identity.png) 


Step-9- Azure-Monitor-Datasource added to Grafana

![Azure-Monitor-Datasource](/Screenshots/azure-datasource.png)

 
Step-10 – A dashboard added to Grafana to monitor VM sources

![dashboard](/Screenshots/dashboard.png)
 

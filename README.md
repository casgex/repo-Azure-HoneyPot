# Setting up a honeypot in Azure and analyzing it with Sentinel
This is an azure focused, hands-on lab of mine. Tryng to understand and be able to use azure sentinel in the future for my career. I will document how the environment in azure is set up and how information will be sent and analyzed by azure sentinel.

### Reason
Azure sentinel is a SIEM solution used and deployed by azure. This resource is often requested by clients trying to implement a SIEM in their environment. Important to know is that sentinel is not a cloud only SIEM, it may run on the cloud but its capabilities go beyond that. Making it able to analyze on-prem logs too.

### Source
Powershell script inspiration taken from Josh Madakor (https://github.com/joshmadakor1/Sentinel-Lab)

### Prerequisits for this lab
We only need an Azure Tenant and an Azure Account that has enough sufficient permissions to deploy the resources such as **Azure Sentinel**, **Virtual Machines** and **Log Analytics Workspace**.
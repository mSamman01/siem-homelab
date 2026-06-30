# siem-homelab
Project Overview

This project demonstrates the deployment of a Security Information and Event Management (SIEM) homelab using Wazuh, Sysmon, and Windows 11. The environment was built to simulate the workflow of a Security Operations Center (SOC), enabling centralized log collection, endpoint monitoring, threat detection, and security event investigation.

Unlike traditional multi-machine homelabs, this implementation monitors the physical Windows host using the Wazuh Agent while the Wazuh server runs on an Ubuntu Server virtual machine hosted in VirtualBox. This lightweight architecture provides realistic endpoint visibility while remaining suitable for personal learning and cybersecurity portfolio development.

Key capabilities include:

Centralized log collection
Windows endpoint monitoring
Sysmon event collection
MITRE ATT&CK mapped detections
Threat hunting using Wazuh Dashboard
Process creation monitoring
Security event investigation

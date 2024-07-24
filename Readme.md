# Hub and Spoke Technology implementation



## Table of Contents

-[Problem_Statement](#problem statement)
-[Introduction](#introduction)
- [Contact](#contact)

## Problem_Statement

Implement Hub and Spoke topology where Hub contains the centralized components like Azure Firewall, Application Gateway, DNS Forwarding VM, Azure Bastion etc. and one spoke has Web App and another spoke has a Storage account with no public access. 
1. Establishes a secure connection between the on-premises data center and the hub VNet and Spoke VNets.
2. Provides custom DNS on the top of Spoke VNets as DNS Forwarding VM. 
3. Resolve all the DNS quries for Azure to On Premises, Azure to Azure and On Premises to Azure.
4. All the traffic should be routed through Azure Firewall. 
5. Internet traffic will land on Application Gateway Public Fronted IP. 6. On-Premises traffic will land on Application Gateway Private Fronted IP.
7. SSL Offloading will be implemented on top of Application Gateway. 
8. Set up multiple listeners to route traffic to the backend with their respective set of configurations.


## Introduction

Please refer to the Cloud_Project document for the project

## Contact

Email- jatinyadavedu@gmail.com




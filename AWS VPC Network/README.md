# AWS VPC Network Infrastructure

## Overview
This project demonstrates how to build a secure 
Virtual Private Cloud (VPC) network on AWS from 
scratch, including subnet configuration and 
internet gateway setup.

## Architecture
- **VPC:** my VPC (10.0.0.0/16)
- **Subnet:** Public 1 (10.0.0.0/24) — 256 IPs
- **Availability Zone:** eu-north-1 (Stockholm)
- **Internet Gateway:** my-GateWay (Attached)

## What I Built

### 1. VPC Creation
Created a custom VPC with IPv4 CIDR block 
10.0.0.0/16 providing up to 65,536 IP addresses 
for the network.

![VPC Settings](vpc-settings.png)

### 2. Public Subnet
Configured a public subnet with CIDR 10.0.0.0/24 
inside the VPC, providing 256 available IP 
addresses in the eu-north-1a availability zone.

![Subnet Settings](subnet-settings.png)
![Subnet Created](subnet-created.png)

### 3. Internet Gateway
Created and attached an internet gateway 
(my-GateWay) to the VPC, enabling communication 
between the VPC and the internet.

![Gateway Creation](gateway-creation.png)
![Gateway Attach](gateway-attach.png)
![Gateway Attached](gateway-attached.png)

## Key Concepts Demonstrated
- Custom VPC creation with CIDR block planning
- Public subnet configuration
- Internet Gateway setup and VPC attachment
- AWS networking fundamentals

## Services Used
- Amazon VPC
- AWS Subnets
- Internet Gateway

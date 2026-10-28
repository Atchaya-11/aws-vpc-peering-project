AWS VPC Peering Using Amazon EC2

Project Overview

This project demonstrates secure private communication between two Amazon VPCs using a VPC Peering connection.

* Amazon VPC
* Amazon EC2
* VPC Peering
* Route Tables
* Security Groups
* Internet Gateway

 Network Configuration

* VPC-A: `10.10.0.0/16`
* VPC-B: `10.20.0.0/16`
* Bastion Host: `10.10.1.125`
* App-A: `10.10.2.60`
* App-B: `10.20.210.77`

 Implementation Steps

1. Created two VPCs with different CIDR blocks.
2. Configured public and private subnets.
3. Launched EC2 instances.
4. Established a VPC Peering connection.
5. Updated route tables and security groups.
6. Connected to the Bastion Host using SSH.
7. Verified private connectivity using ping.

Results

Successfully tested connectivity from the Bastion Host to App-A and App-B using their private IP addresses, with **0% packet loss** in both tests.

 Learning Outcomes

* Understanding AWS VPC networking.
* Configuring route tables and security groups.
* Connecting EC2 instances using SSH.
* Establishing communication between two VPCs.

Conclusion

The project successfully demonstrates private network communication between two AWS VPCs using VPC Peering.

Technologies: AWS | EC2 | VPC | Linux | SSH | Networking

Kindly check the screenshots and results of my project in the pdf which i attached "Atchaya EWB-Course-AWS-VPC-Peering-Project.pdf"
Project Done by
Atchaya S

---
title: "Week 4 Worklog"
date: 2024-01-01
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Main Objectives of Week 4:

* Distinguish between Security Groups and Network ACLs in a multi-layered security model.
* Deploy EC2 instances in subnets, test public/private connectivity, and troubleshoot access issues.
* Get familiar with EC2 Instance Connect Endpoint for more secure connections to private resources.

### Detailed Implementation Plan:
| Day | Task Description | Start Date | End Date | Reference |
| --- | --- | :---: | :---: | --- |
| 1 | Study VPC Security and Multi-VPC features, noting the roles of stateful/stateless filtering. | 08/05/2026 | 08/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 2 | Create Security Groups for EC2, restrict inbound traffic to necessary ports, and test access. | 09/05/2026 | 09/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 3 | Configure Network ACLs, comparing rule evaluation order and how NACL affects subnets. | 10/05/2026 | 10/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 4 | Launch EC2 instances in different subnets, attach security groups, and verify public/private IPs. | 11/05/2026 | 11/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 5 | Test connectivity between EC2 instances, checking routes, gateways, and security rules when a connection fails. | 12/05/2026 | 12/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 6 | Create and test NAT Gateway for outbound traffic flow from private subnets. | 13/05/2026 | 13/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 7 | Practice with EC2 Instance Connect Endpoint and document the connection process without requiring public IPs. | 14/05/2026 | 14/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |

### Assessment of Week 4 Results:

* Clearly understand how Security Groups and NACLs work together to protect network resources.
* Successfully deployed EC2 instances in a multi-layered subnet design and tested connectivity.
* Able to troubleshoot connection issues along the sequence: route tables, gateways, security groups, NACLs, and IPs.
* Gained experience connecting to private instances using more secure methods.

---
title: "Week 6 Worklog"
date: 2024-01-01
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Main Objectives of Week 6:

* Practice connecting multiple VPCs using VPC Peering.
* Understand when to use AWS Transit Gateway to consolidate multiple network connections into a single hub.
* Configure route tables, attachments, and cross-peer DNS to ensure network traffic flows correctly.

### Detailed Implementation Plan:
| Day | Task Description | Start Date | End Date | Reference |
| --- | --- | :---: | :---: | --- |
| 1 | Study VPC Peering introduction, identifying non-overlapping CIDR conditions and connectivity goals. | 22/05/2026 | 22/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 2 | Deploy infrastructure using CloudFormation, creating Security Groups and EC2 instances for the two test VPCs. | 23/05/2026 | 23/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 3 | Update NACLs, create a VPC Peering Connection, and accept the peering request. | 24/05/2026 | 24/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 4 | Configure two-way route tables and enable Cross-Peer DNS to test name resolution over peering. | 25/05/2026 | 25/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 5 | Study Transit Gateway introduction, comparing hub-and-spoke models with point-to-point peering. | 26/05/2026 | 26/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 6 | Create a Transit Gateway, VPC attachments, and Transit Gateway route tables. | 27/05/2026 | 27/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 7 | Add routes from VPC route tables back to the Transit Gateway, test connectivity, and clean up resources. | 28/05/2026 | 28/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |

### Assessment of Week 6 Results:

* Differentiate between VPC Peering for simple point-to-point links and Transit Gateway for larger multi-VPC networks.
* Know how to update route tables on both ends to ensure correct network pathing.
* Understand the importance of DNS configuration when resources interact across multiple VPCs.
* Cleaned up complex network resources after the lab, minimizing potential cost risks.

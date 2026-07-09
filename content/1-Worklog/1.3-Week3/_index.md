---
title: "Week 3 Worklog"
date: 2024-01-01
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Main Objectives of Week 3:

* Understand Amazon VPC structure and the roles of CIDR, Subnets, Route Tables, Internet Gateways, and NAT Gateways.
* Design a network with public/private subnets that can access the Internet within the correct scope.
* Practice building a VPC from scratch and verify the resource layout using the VPC Resource Map.

### Detailed Implementation Plan:
| Day | Task Description | Start Date | End Date | Reference |
| --- | --- | :---: | :---: | --- |
| 1 | Study Module 02-01 on Amazon VPC, analyzing CIDR allocation and network zones within a Region. | 01/05/2026 | 01/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 2 | Create a VPC, planning public and private subnets for each Availability Zone. | 02/05/2026 | 02/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 3 | Configure Route Tables, associate subnets, and check traffic flow in the network. | 03/05/2026 | 03/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 4 | Create an Internet Gateway, attach it to the VPC, and add outbound routes for public subnets. | 04/05/2026 | 04/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 5 | Create a NAT Gateway to allow private subnets to access the Internet without exposing resources publicly. | 05/05/2026 | 05/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 6 | Verify with the VPC Resource Map, matching the actual deployment with the initial design. | 06/05/2026 | 06/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 7 | Summarize the standard network model, documenting common errors when attaching route tables and gateways. | 07/05/2026 | 07/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |

### Assessment of Week 3 Results:

* Able to self-design a VPC with public/private subnets and appropriate Internet routes.
* Understand the differences between Internet Gateway and NAT Gateway in AWS network architecture.
* Know how to use the VPC Resource Map to quickly check the relationships between subnets, route tables, and gateways.
* Established a network foundation to deploy EC2 instances and security labs in the following week.

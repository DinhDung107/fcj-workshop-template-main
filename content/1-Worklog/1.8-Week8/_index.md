---
title: "Week 8 Worklog"
date: 2024-01-01
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Main Objectives of Week 8:

* Practice using Storage Gateway and sharing files onto AWS.
* Deploy a static website on Amazon S3, configuring controlled public access.
* Integrate CloudFront for content distribution and test the website via CDN.

### Detailed Implementation Plan:
| Day | Task Description | Start Date | End Date | Reference |
| --- | --- | :---: | :---: | --- |
| 1 | Create an S3 bucket for the Storage Gateway lab and prepare an EC2 instance as the gateway environment. | 05/06/2026 | 05/06/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 2 | Create the Storage Gateway, configure the file share, and verify data read/write capabilities. | 06/06/2026 | 06/06/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 3 | Create an S3 bucket for the static website, upload sample data, and enable static website hosting. | 07/06/2026 | 07/06/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 4 | Configure public access blocks and public object permissions within the required scope. | 08/06/2026 | 08/06/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 5 | Test the website directly from the S3 endpoint, document permission errors, and outline fixes. | 09/06/2026 | 09/06/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 6 | Configure CloudFront Distribution for the S3 origin and verify content delivery through the CDN domain. | 10/06/2026 | 10/06/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 7 | Enable bucket versioning, migrate objects, compare versions, and summarize storage takeaways. | 11/06/2026 | 11/06/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |

### Assessment of Week 8 Results:

* Understand how Storage Gateway bridges on-premises file systems with AWS storage.
* Successfully set up a static website on S3 with minimal necessary public permissions.
* Know how to configure CloudFront to distribute content via CDN.
* Grasped bucket versioning and basic object operations for data management.

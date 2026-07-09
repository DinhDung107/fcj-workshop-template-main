---
title: "Nhật ký Tuần 6"
date: 2024-01-01
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu chính của Tuần 6:

* Thực hành kết nối nhiều VPC bằng VPC Peering.
* Hiểu khi nào cần AWS Transit Gateway để gom nhiều kết nối mạng về một trung tâm.
* Cấu hình route table, attachment và DNS cross-peer để luồng mạng hoạt động đúng.

### Kế hoạch công việc chi tiết:
| Ngày | Nội dung thực hiện | Bắt đầu | Kết thúc | Nguồn tham khảo |
| --- | --- | :---: | :---: | --- |
| 1 | Học phần giới thiệu VPC Peering, xác định điều kiện CIDR không chồng lấn và mục tiêu kết nối. | 22/05/2026 | 22/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 2 | Dựng hạ tầng bằng CloudFormation, tạo Security Group và EC2 cho hai VPC thử nghiệm. | 23/05/2026 | 23/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 3 | Cập nhật NACL, tạo VPC Peering Connection và chấp nhận kết nối giữa hai VPC. | 24/05/2026 | 24/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 4 | Cấu hình route table hai chiều và bật Cross-Peer DNS để kiểm tra phân giải tên qua peering. | 25/05/2026 | 25/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 5 | Học phần giới thiệu Transit Gateway, so sánh hub-and-spoke với peering từng cặp. | 26/05/2026 | 26/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 6 | Tạo Transit Gateway, VPC attachment và Transit Gateway route table. | 27/05/2026 | 27/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 7 | Thêm route từ VPC route table về Transit Gateway, kiểm thử kết nối và dọn tài nguyên. | 28/05/2026 | 28/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |

### Đánh giá kết quả Tuần 6:

* Phân biệt được VPC Peering cho kết nối đơn giản và Transit Gateway cho mạng nhiều VPC.
* Biết cập nhật route table ở cả hai đầu để luồng mạng đi đúng hướng.
* Hiểu tầm quan trọng của DNS khi tài nguyên liên lạc qua nhiều VPC.
* Dọn được tài nguyên mạng phức tạp sau lab, giảm nguy cơ phát sinh chi phí.

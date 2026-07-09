---
title: "Nhật ký Tuần 4"
date: 2024-01-01
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu chính của Tuần 4:

* Phân biệt Security Group và Network ACL trong mô hình bảo mật nhiều lớp.
* Triển khai EC2 trong subnet, kiểm thử đường kết nối public/private và xử lý lỗi truy cập.
* Làm quen EC2 Instance Connect Endpoint để kết nối an toàn hơn vào tài nguyên private.

### Kế hoạch công việc chi tiết:
| Ngày | Nội dung thực hiện | Bắt đầu | Kết thúc | Nguồn tham khảo |
| --- | --- | :---: | :---: | --- |
| 1 | Học VPC Security và Multi-VPC features, ghi chú vai trò của stateful/stateleess filtering. | 08/05/2026 | 08/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 2 | Tạo Security Group cho EC2, giới hạn inbound theo port cần thiết và kiểm thử truy cập. | 09/05/2026 | 09/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 3 | Cấu hình Network ACL, so sánh thứ tự rule và cách NACL ảnh hưởng tới subnet. | 10/05/2026 | 10/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 4 | Khởi tạo EC2 trong các subnet, gắn security group và xác nhận public/private IP. | 11/05/2026 | 11/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 5 | Test kết nối giữa các EC2, kiểm tra route, gateway và rule bảo mật khi kết nối thất bại. | 12/05/2026 | 12/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 6 | Tạo và kiểm thử NAT Gateway cho luồng outbound từ private subnet. | 13/05/2026 | 13/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 7 | Thực hành EC2 Instance Connect Endpoint và ghi lại quy trình kết nối không cần public IP. | 14/05/2026 | 14/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |

### Đánh giá kết quả Tuần 4:

* Nắm rõ cách Security Group và NACL phối hợp bảo vệ tài nguyên mạng.
* Triển khai được EC2 trong mô hình subnet nhiều lớp và kiểm thử kết nối.
* Biết xử lý lỗi kết nối theo chuỗi: route table, gateway, security group, NACL và IP.
* Có kinh nghiệm kết nối vào private instance bằng phương án an toàn hơn.

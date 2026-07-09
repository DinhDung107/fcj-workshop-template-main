---
title: "Nhật ký Tuần 3"
date: 2024-01-01
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu chính của Tuần 3:

* Hiểu cấu trúc Amazon VPC và vai trò của CIDR, Subnet, Route Table, Internet Gateway và NAT Gateway.
* Thiết kế mạng public/private subnet có khả năng truy cập Internet đúng phạm vi.
* Thực hành dựng VPC từ đầu và kiểm tra sơ đồ tài nguyên bằng VPC Resource Map.

### Kế hoạch công việc chi tiết:
| Ngày | Nội dung thực hiện | Bắt đầu | Kết thúc | Nguồn tham khảo |
| --- | --- | :---: | :---: | --- |
| 1 | Học Module 02-01 về Amazon VPC, phân tích cách chia CIDR và vùng mạng trong một Region. | 01/05/2026 | 01/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 2 | Tạo VPC, lập kế hoạch public subnet và private subnet theo từng Availability Zone. | 02/05/2026 | 02/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 3 | Cấu hình Route Table, gắn subnet và kiểm tra đường đi của lưu lượng trong mạng. | 03/05/2026 | 03/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 4 | Tạo Internet Gateway, gắn vào VPC và mở tuyến outbound cho public subnet. | 04/05/2026 | 04/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 5 | Tạo NAT Gateway để private subnet truy cập Internet mà không public trực tiếp tài nguyên. | 05/05/2026 | 05/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 6 | Kiểm tra VPC Resource Map, đối chiếu sơ đồ thực tế với bản thiết kế ban đầu. | 06/05/2026 | 06/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 7 | Tổng kết mô hình mạng chuẩn, ghi lại lỗi thường gặp khi gắn route table và gateway. | 07/05/2026 | 07/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |

### Đánh giá kết quả Tuần 3:

* Tự thiết kế được VPC có public/private subnet và tuyến Internet phù hợp.
* Hiểu khác biệt giữa Internet Gateway và NAT Gateway trong kiến trúc mạng AWS.
* Biết dùng VPC Resource Map để kiểm tra nhanh quan hệ giữa subnet, route table và gateway.
* Có nền tảng mạng để triển khai EC2 và các lab bảo mật trong tuần tiếp theo.

---
title: "Nhật ký Tuần 5"
date: 2024-01-01
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu chính của Tuần 5:

* Hiểu mô hình Hybrid DNS với Route 53 Resolver inbound/outbound endpoint.
* Dùng CloudFormation để khởi tạo hạ tầng lặp lại, giảm thao tác thủ công.
* Kết nối RDGW, thiết lập DNS và kiểm chứng kết quả phân giải tên miền.

### Kế hoạch công việc chi tiết:
| Ngày | Nội dung thực hiện | Bắt đầu | Kết thúc | Nguồn tham khảo |
| --- | --- | :---: | :---: | --- |
| 1 | Học phần giới thiệu Hybrid DNS với Route 53 Resolver và xác định các thành phần cần triển khai. | 15/05/2026 | 15/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 2 | Tạo key pair, chuẩn bị kết nối quản trị và kiểm tra vùng triển khai tài nguyên. | 16/05/2026 | 16/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 3 | Khởi tạo CloudFormation template để dựng hạ tầng theo cấu hình có thể tái sử dụng. | 17/05/2026 | 17/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 4 | Cấu hình Security Group cho các endpoint và máy chủ liên quan tới DNS. | 18/05/2026 | 18/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 5 | Kết nối RDGW, kiểm tra khả năng truy cập vào môi trường lab và các instance nội bộ. | 19/05/2026 | 19/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 6 | Tạo Route 53 outbound endpoint, inbound endpoint và resolver rules theo yêu cầu lab. | 20/05/2026 | 20/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 7 | Kiểm thử kết quả DNS, ghi lại đường đi truy vấn và dọn tài nguyên sau khi hoàn tất. | 21/05/2026 | 21/05/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |

### Đánh giá kết quả Tuần 5:

* Hiểu vai trò của Route 53 Resolver trong mô hình hybrid cloud.
* Thực hành được inbound/outbound endpoint và resolver rule.
* Biết dùng CloudFormation để tạo hạ tầng có cấu trúc, dễ lặp lại và dễ dọn dẹp.
* Có thêm kinh nghiệm kiểm thử DNS thay vì chỉ xác nhận tài nguyên đã tạo.

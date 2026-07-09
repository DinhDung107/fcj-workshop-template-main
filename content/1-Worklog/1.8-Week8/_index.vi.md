---
title: "Nhật ký Tuần 8"
date: 2024-01-01
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu chính của Tuần 8:

* Thực hành Storage Gateway và chia sẻ file lên AWS.
* Triển khai static website trên Amazon S3, cấu hình public access có kiểm soát.
* Kết hợp CloudFront để phân phối nội dung và kiểm thử website qua CDN.

### Kế hoạch công việc chi tiết:
| Ngày | Nội dung thực hiện | Bắt đầu | Kết thúc | Nguồn tham khảo |
| --- | --- | :---: | :---: | --- |
| 1 | Tạo S3 bucket phục vụ lab Storage Gateway và chuẩn bị EC2 làm môi trường gateway. | 05/06/2026 | 05/06/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 2 | Tạo Storage Gateway, cấu hình file share và xác nhận khả năng ghi/đọc dữ liệu. | 06/06/2026 | 06/06/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 3 | Tạo S3 bucket cho static website, tải dữ liệu mẫu và bật static website hosting. | 07/06/2026 | 07/06/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 4 | Cấu hình public access block và quyền public object đúng phạm vi cần thiết. | 08/06/2026 | 08/06/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 5 | Kiểm thử website trực tiếp từ S3 endpoint, ghi lại lỗi quyền truy cập và cách sửa. | 09/06/2026 | 09/06/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 6 | Cấu hình CloudFront Distribution cho S3 origin và kiểm thử nội dung qua domain CDN. | 10/06/2026 | 10/06/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 7 | Bật bucket versioning, di chuyển object, đối chiếu phiên bản và tổng kết bài học lưu trữ. | 11/06/2026 | 11/06/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |

### Đánh giá kết quả Tuần 8:

* Hiểu cách Storage Gateway nối hệ thống file với lưu trữ AWS.
* Tạo được website tĩnh trên S3 và kiểm soát quyền public ở mức tối thiểu.
* Biết cấu hình CloudFront để phân phối nội dung qua CDN.
* Nắm bucket versioning và thao tác object cơ bản phục vụ quản trị dữ liệu.

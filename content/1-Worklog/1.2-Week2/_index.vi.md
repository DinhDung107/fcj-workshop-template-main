---
title: "Nhật ký Tuần 2"
date: 2024-01-01
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---

### Mục tiêu chính của Tuần 2:

* Thiết lập tài khoản AWS theo hướng an toàn, có MFA và tài khoản quản trị riêng.
* Thực hành IAM group, user, quyền quản trị và các bước xác thực tài khoản.
* Kiểm soát chi phí bằng AWS Budget, Cost Budget, Usage Budget, RI Budget và Savings Plans Budget.

### Kế hoạch công việc chi tiết:
| Ngày | Nội dung thực hiện | Bắt đầu | Kết thúc | Nguồn tham khảo |
| --- | --- | :---: | :---: | --- |
| 1 | Tiếp tục tìm hiểu thêm các dịch vụ của AWS | 24/04/2026 | 24/04/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 2 | Bật Virtual MFA cho root account, ghi lại quy trình khôi phục và nguyên tắc bảo vệ thiết bị xác thực. | 25/04/2026 | 25/04/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 3 | Tạo admin group, admin user và kiểm thử đăng nhập bằng IAM user thay vì root account. | 26/04/2026 | 26/04/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 4 | Rà soát account authentication support, contact, bảo mật tài khoản và các cảnh báo liên quan. | 27/04/2026 | 27/04/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 5 | Tạo Budget bằng template, đặt ngưỡng cảnh báo chi phí và xác nhận email nhận thông báo. | 28/04/2026 | 28/04/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 6 | Thực hành Cost Budget, Usage Budget, RI Budget và Savings Plans Budget để hiểu từng loại cảnh báo. | 29/04/2026 | 29/04/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |
| 7 | Dọn tài nguyên không cần thiết, tổng kết nguyên tắc least privilege và quản trị chi phí. | 30/04/2026 | 30/04/2026 | [FCAJ Playlist](https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i) |

### Đánh giá kết quả Tuần 2:

* Tài khoản AWS được bảo vệ bằng MFA và phân tách root/IAM user rõ ràng.
* Nắm được cách tạo nhóm quyền quản trị, user quản trị và xác thực truy cập.
* Biết đặt ngân sách, ngưỡng cảnh báo và đọc tín hiệu chi phí trước khi phát sinh rủi ro.
* Hình thành thói quen dọn tài nguyên sau lab để tránh chi phí ngoài ý muốn.

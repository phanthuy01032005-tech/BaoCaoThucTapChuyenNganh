---
title: "Tuần 7: Tìm hiểu IAM Roles for EC2"
menuTitle: "Worklog Tuần 7"
date: 2026-09-28
weight: 7
chapter: false
pre: " <b>1.7.</b> "
---

**Thời gian:** 28/09/2026–02/10/2026

## Mục tiêu

- Tìm hiểu mục đích sử dụng IAM Role cho ứng dụng chạy trên Amazon EC2.
- Đọc mối liên hệ giữa IAM Role, permission policy và trust policy.
- Tìm hiểu vai trò của instance profile và thông tin xác thực tạm thời.
- Hiểu nguyên tắc cấp quyền tối thiểu khi ứng dụng truy cập dịch vụ AWS.

## Nội dung học tập trong tuần

| Thứ | Nội dung học tập | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | Đọc phần giới thiệu IAM Roles for EC2; tìm hiểu nhu cầu cấp quyền cho ứng dụng trên máy chủ truy cập các dịch vụ AWS. | 28/09/2026 | 28/09/2026 | [First Cloud AI Journey](https://cloudjourney.awsfcaj.com/) |
| 3 | Tìm hiểu permission policy gắn với IAM Role; đọc các ví dụ mô tả hành động và tài nguyên mà ứng dụng được phép truy cập. | 29/09/2026 | 29/09/2026 | [First Cloud AI Journey](https://cloudjourney.awsfcaj.com/) |
| 4 | Đọc về trust policy; phân biệt chính sách xác định đối tượng được đảm nhận vai trò với chính sách xác định quyền của vai trò. | 30/09/2026 | 30/09/2026 | [First Cloud AI Journey](https://cloudjourney.awsfcaj.com/) |
| 5 | Tìm hiểu instance profile và mối liên hệ với IAM Role; đọc cách ứng dụng nhận thông tin xác thực tạm thời thông qua cơ chế dành cho EC2. | 01/10/2026 | 01/10/2026 | [First Cloud AI Journey](https://cloudjourney.awsfcaj.com/) |
| 6 | Tổng hợp sự khác nhau giữa IAM User và IAM Role trong cấp quyền cho ứng dụng; ghi chép nguyên tắc cấp quyền tối thiểu và hạn chế lưu khóa truy cập dài hạn trên máy chủ. | 02/10/2026 | 02/10/2026 | [First Cloud AI Journey](https://cloudjourney.awsfcaj.com/) |

## Tổng kết kiến thức

- Hiểu IAM Role giúp ứng dụng chạy trên EC2 nhận quyền truy cập các dịch vụ AWS.
- Phân biệt permission policy quy định quyền của vai trò với trust policy quy định đối tượng được phép đảm nhận vai trò.
- Hiểu instance profile là thành phần dùng để đưa IAM Role đến EC2 instance.
- Nắm được mục đích của thông tin xác thực tạm thời và cơ chế thay mới thông tin xác thực.
- Hiểu ứng dụng có thể sử dụng cơ chế cung cấp thông tin xác thực của AWS SDK thay vì ghi trực tiếp khóa truy cập trong mã nguồn.
- Phân biệt quyền truy cập dịch vụ AWS của ứng dụng với quyền kết nối vào hệ điều hành của máy chủ.
- Hiểu việc cấp quyền cần giới hạn theo hành động và tài nguyên cần thiết.

Qua tuần học thứ bảy, em đã hiểu rõ hơn cách IAM Role được sử dụng cho ứng dụng trên EC2. Việc đọc tài liệu giúp em liên kết kiến thức IAM với EC2, đồng thời nhận biết vai trò của instance profile và thông tin xác thực tạm thời trong quản lý truy cập.

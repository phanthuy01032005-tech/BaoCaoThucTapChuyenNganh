---
title: "Tuần 6: Tìm hiểu kiến thức máy chủ ảo với Amazon EC2"
menuTitle: "Worklog Tuần 6"
date: 2026-09-21
weight: 6
chapter: false
pre: " <b>1.6.</b> "
---

**Thời gian:** 21/09/2026–25/09/2026

## Mục tiêu

- Tìm hiểu vai trò của Amazon Elastic Compute Cloud trong cung cấp máy chủ ảo.
- Đọc các thành phần cấu hình cơ bản của EC2 instance.
- Tìm hiểu vòng đời instance và các thành phần lưu trữ liên quan.
- Nắm được vai trò của cấu hình mạng và các phương thức kết nối qua tài liệu.

## Nội dung học tập trong tuần

| Thứ | Nội dung học tập | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | Đọc phần giới thiệu Amazon EC2; tìm hiểu khái niệm instance, Amazon Machine Image và mối liên hệ giữa ảnh máy với hệ điều hành của máy chủ ảo. | 21/09/2026 | 21/09/2026 | [First Cloud AI Journey](https://cloudjourney.awsfcaj.com/) |
| 3 | Tìm hiểu instance type, vCPU và bộ nhớ; đọc cách lựa chọn cấu hình máy chủ theo nhu cầu xử lý được mô tả trong tài liệu. | 22/09/2026 | 22/09/2026 | [First Cloud AI Journey](https://cloudjourney.awsfcaj.com/) |
| 4 | Đọc về vòng đời EC2 instance; phân biệt các thao tác khởi động, dừng, khởi động lại và chấm dứt instance. | 23/09/2026 | 23/09/2026 | [First Cloud AI Journey](https://cloudjourney.awsfcaj.com/) |
| 5 | Tìm hiểu Amazon EBS, volume và snapshot; đọc vai trò của lưu trữ khối và những lưu ý về dữ liệu khi thay đổi trạng thái instance. | 24/09/2026 | 24/09/2026 | [First Cloud AI Journey](https://cloudjourney.awsfcaj.com/) |
| 6 | Đọc về key pair, Security Group và các phương thức kết nối EC2 được giới thiệu; tổng hợp mối liên hệ giữa máy chủ, lưu trữ và cấu hình mạng. | 25/09/2026 | 25/09/2026 | [First Cloud AI Journey](https://cloudjourney.awsfcaj.com/) |

## Tổng kết kiến thức

- Hiểu Amazon EC2 cung cấp khả năng sử dụng máy chủ ảo với cấu hình phù hợp nhu cầu.
- Phân biệt AMI là ảnh dùng để khởi tạo máy chủ, còn instance type xác định cấu hình tài nguyên tính toán.
- Nắm được các trạng thái và thao tác cơ bản trong vòng đời EC2 instance qua tài liệu.
- Phân biệt thao tác dừng instance với chấm dứt instance.
- Hiểu vai trò của EBS volume trong lưu trữ dữ liệu và snapshot trong sao lưu volume.
- Nhận biết việc giữ hay xóa EBS volume khi chấm dứt instance phụ thuộc vào cấu hình của volume.
- Hiểu Security Group kiểm soát lưu lượng được phép truy cập máy chủ.
- Nắm được vai trò của key pair trong những phương thức kết nối sử dụng cặp khóa.
- Hiểu việc dừng instance không đồng nghĩa với việc mọi chi phí tài nguyên liên quan đều chấm dứt.

Qua tuần học thứ sáu, em đã hệ thống hóa kiến thức cơ bản về Amazon EC2, từ cấu hình máy chủ đến vòng đời, lưu trữ và kết nối mạng. Nội dung tài liệu giúp em hiểu các thành phần cần xem xét khi đọc một cấu hình máy chủ ảo trên AWS.

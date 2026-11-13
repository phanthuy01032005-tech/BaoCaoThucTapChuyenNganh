---
title: "Tuần 5: Tìm hiểu kiến thức mạng cơ bản với Amazon VPC"
menuTitle: "Worklog Tuần 5"
date: 2026-09-14
weight: 5
chapter: false
pre: " <b>1.5.</b> "
---

**Thời gian:** 14/09/2026–18/09/2026

## Mục tiêu

- Tìm hiểu vai trò của Amazon Virtual Private Cloud trong tổ chức mạng trên AWS.
- Đọc các khái niệm về địa chỉ IP, CIDR, subnet và Availability Zone.
- Tìm hiểu cách định tuyến và kết nối Internet trong VPC.
- Phân biệt vai trò của Security Group và Network ACL.

## Nội dung học tập trong tuần

| Thứ | Nội dung học tập | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | Đọc phần giới thiệu Amazon VPC; tìm hiểu mạng riêng ảo, địa chỉ IPv4 và cách biểu diễn dải địa chỉ bằng CIDR qua các ví dụ trong tài liệu. | 14/09/2026 | 14/09/2026 | [First Cloud AI Journey](https://cloudjourney.awsfcaj.com/) |
| 3 | Tìm hiểu subnet, mối liên hệ giữa subnet với Availability Zone và cách chia dải địa chỉ của VPC thành các mạng con. | 15/09/2026 | 15/09/2026 | [First Cloud AI Journey](https://cloudjourney.awsfcaj.com/) |
| 4 | Đọc về Route Table và Internet Gateway; tìm hiểu ý nghĩa của địa chỉ đích, đích định tuyến và cách nhận biết public subnet qua bảng định tuyến. | 16/09/2026 | 16/09/2026 | [First Cloud AI Journey](https://cloudjourney.awsfcaj.com/) |
| 5 | Tìm hiểu private subnet và NAT Gateway; đọc sơ đồ mô tả cách tài nguyên trong private subnet khởi tạo kết nối ra Internet. | 17/09/2026 | 17/09/2026 | [First Cloud AI Journey](https://cloudjourney.awsfcaj.com/) |
| 6 | Đọc về Security Group và Network ACL; so sánh phạm vi áp dụng, cơ chế xử lý lưu lượng và tổng hợp mối liên hệ giữa các thành phần VPC. | 18/09/2026 | 18/09/2026 | [First Cloud AI Journey](https://cloudjourney.awsfcaj.com/) |

## Tổng kết kiến thức

- Hiểu VPC là môi trường mạng được cô lập về mặt logic để tổ chức tài nguyên AWS.
- Nắm được ý nghĩa của CIDR và cách phân chia dải địa chỉ thành các subnet qua tài liệu.
- Hiểu mỗi subnet thuộc một Availability Zone.
- Hiểu Route Table xác định hướng đi của lưu lượng mạng.
- Phân biệt public subnet có tuyến trực tiếp đến Internet Gateway với private subnet không có tuyến trực tiếp đó.
- Hiểu vai trò của NAT Gateway trong việc hỗ trợ kết nối ra ngoài từ private subnet theo mô hình được mô tả.
- Phân biệt Security Group kiểm soát lưu lượng tại các giao diện mạng được gắn với nhóm, còn Network ACL kiểm soát lưu lượng tại ranh giới subnet.
- Nhận biết Security Group có cơ chế theo dõi trạng thái kết nối, trong khi Network ACL không theo dõi trạng thái kết nối.

Qua tuần học thứ năm, em đã hệ thống hóa các thành phần mạng cơ bản của Amazon VPC. Việc đọc sơ đồ và các ví dụ trong tài liệu giúp em hiểu mối liên hệ giữa dải địa chỉ, subnet, bảng định tuyến và các lớp kiểm soát lưu lượng.

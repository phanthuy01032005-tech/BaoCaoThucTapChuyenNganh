---
title: "Tuần 9: Tìm hiểu hosting website tĩnh với Amazon S3"
menuTitle: "Worklog Tuần 9"
date: 2026-10-12
weight: 9
chapter: false
pre: " <b>1.9.</b> "
---

**Thời gian:** 12/10/2026–16/10/2026

## Mục tiêu

- Tìm hiểu các khái niệm cơ bản của Amazon S3.
- Đọc cách tổ chức các tệp của website tĩnh trong S3 bucket.
- Tìm hiểu cấu hình static website hosting qua tài liệu.
- Hiểu vai trò của quyền truy cập và cách nhận biết một số lỗi thường gặp.

## Nội dung học tập trong tuần

| Thứ | Nội dung học tập | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | Đọc phần giới thiệu Amazon S3; tìm hiểu bucket, object, object key và metadata; ghi chép cách tổ chức dữ liệu trong bucket. | 12/10/2026 | 12/10/2026 | [First Cloud AI Journey](https://cloudjourney.awsfcaj.com/) |
| 3 | Tìm hiểu website tĩnh và các thành phần HTML, CSS, JavaScript, hình ảnh; đọc cách sắp xếp tệp và xác định đường dẫn tài nguyên. | 13/10/2026 | 13/10/2026 | [First Cloud AI Journey](https://cloudjourney.awsfcaj.com/) |
| 4 | Đọc hướng dẫn static website hosting trên S3; tìm hiểu mục đích của index document, error document và website endpoint. | 14/10/2026 | 14/10/2026 | [First Cloud AI Journey](https://cloudjourney.awsfcaj.com/) |
| 5 | Tìm hiểu S3 Block Public Access và bucket policy trong mô hình website công khai; đọc cách quyền truy cập ảnh hưởng đến khả năng xem nội dung website. | 15/10/2026 | 15/10/2026 | [First Cloud AI Journey](https://cloudjourney.awsfcaj.com/) |
| 6 | Tổng hợp quy trình cấu hình được mô tả trong tài liệu; tìm hiểu các nguyên nhân có thể gây lỗi Access Denied, thiếu trang index hoặc sai đường dẫn tệp. | 16/10/2026 | 16/10/2026 | [First Cloud AI Journey](https://cloudjourney.awsfcaj.com/) |

## Tổng kết kiến thức

- Hiểu Amazon S3 lưu trữ dữ liệu dưới dạng object trong bucket.
- Phân biệt bucket là nơi chứa dữ liệu, còn object key xác định đối tượng bên trong bucket.
- Hiểu website tĩnh cung cấp các tệp nội dung cho trình duyệt và không chạy mã xử lý phía máy chủ trên S3.
- Nắm được mục đích của index document và error document qua tài liệu.
- Hiểu website endpoint là địa chỉ truy cập website tĩnh do S3 cung cấp.
- Nhận biết tên tệp và đường dẫn phải khớp với tài nguyên được tham chiếu trong trang.
- Hiểu quyền đọc object ảnh hưởng đến khả năng truy cập nội dung website.
- Phân biệt lỗi do quyền truy cập với lỗi do thiếu tệp hoặc sai đường dẫn.
- Nội dung tuần tập trung đọc tài liệu và phân tích ví dụ, không thực hiện tạo bucket hoặc triển khai website.

Qua tuần học thứ chín, em đã hệ thống hóa kiến thức về Amazon S3 và mô hình lưu trữ website tĩnh. Việc đọc tài liệu giúp em hiểu mối liên hệ giữa cấu trúc tệp, cấu hình hosting và quyền truy cập khi cung cấp nội dung website.tài liệu giúp em hiểu mối liên hệ giữa cấu trúc tệp, cấu hình hosting và quyền truy cập khi cung cấp nội dung website.

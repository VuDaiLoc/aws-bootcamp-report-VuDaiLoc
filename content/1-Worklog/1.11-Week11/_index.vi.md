---
title: "Worklog Tuần 11"
date: 2024-01-01
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---


### Mục tiêu tuần 11:

* Hoàn thiện các chức năng quản lý tài liệu trên nền tảng AWS Amplify Gen 2.
* Xây dựng giao diện quản lý tài liệu và cơ chế giới hạn upload cho người dùng.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Tiếp tục phát triển hệ thống AI-Powered Smart Document Assistant, hoàn thiện các chức năng quản lý tài liệu trên nền tảng AWS Amplify Gen 2. | 29/06/2026 | 29/06/2026 | AWS Amplify Gen 2 Documentation AWS AppSync Documentation |
| 3 | - Triển khai chức năng tải tài liệu lên Amazon S3, lưu metadata vào Amazon DynamoDB thông qua AWS AppSync GraphQL, xây dựng cơ chế kiểm tra định dạng, kích thước tệp trước khi lưu trữ. | 30/06/2026 | 30/06/2026 |  |
| 4 | - Xây dựng giao diện quản lý tài liệu, hỗ trợ hiển thị danh sách theo phân trang, xem trước, tải xuống và xóa tài liệu bằng Presigned URL của Amazon S3. | 01/07/2026 | 01/07/2026 |  |
| 5 | - Thiết lập cơ chế giới hạn số lượng tài liệu (Upload Quota) cho từng người dùng. | 02/07/2026 | 02/07/2026 |  |
| 6 | - Xây dựng giao diện responsive, hỗ trợ Dark/Light Mode; triển khai AWS Lambda được kích hoạt bởi sự kiện Amazon S3 (S3 Event Trigger) để tự động cập nhật trạng thái xử lý tài liệu và chuẩn bị pipeline cho các tác vụ AI. | 03/07/2026 | 03/07/2026 |  |


### Kết quả đạt được tuần 11:

* Triển khai thành công chức năng upload tài liệu lên Amazon S3 và lưu metadata vào DynamoDB thông qua AppSync GraphQL.
* Xây dựng thành công cơ chế kiểm tra định dạng và kích thước file trước khi upload, tránh dữ liệu không hợp lệ.
* Hoàn thiện giao diện quản lý tài liệu: danh sách phân trang, xem trước, tải xuống, xóa tài liệu bằng Presigned URL.
* Thiết lập thành công Upload Quota theo từng người dùng, kiểm soát tài nguyên hệ thống hiệu quả.
* Hoàn thiện giao diện responsive, hỗ trợ Dark/Light Mode; triển khai thành công Lambda trigger từ S3 Event để tự động cập nhật trạng thái tài liệu, sẵn sàng cho pipeline AI ở tuần tiếp theo.

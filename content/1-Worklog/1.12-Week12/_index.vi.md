---
title: "Worklog Tuần 12"
date: 2024-01-01
weight: 12
chapter: false
pre: " <b> 1.12. </b> "
---

### Mục tiêu tuần 12:

* Xây dựng hoàn chỉnh pipeline xử lý AI cho hệ thống: OCR (Textract) và tóm tắt/phân loại bằng Amazon Bedrock.
* Kiểm thử toàn bộ luồng end-to-end của hệ thống AI-Powered Smart Document Assistant.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Tiếp tục phát triển pipeline xử lý AI cho hệ thống AI-Powered Smart Document Assistant bằng các dịch vụ AI trên AWS. | 06/07/2026 | 06/07/2026 | Amazon Textract Documentation Amazon Bedrock Documentation |
| 3 | - Triển khai Amazon Textract theo cơ chế xử lý bất đồng bộ (Asynchronous Processing), tích hợp Amazon SNS và AWS Lambda để tự động nhận kết quả OCR và cập nhật trạng thái tài liệu. | 07/07/2026 | 07/07/2026 |  |
| 4 | - Thực hiện trích xuất nội dung từ các định dạng PDF, hình ảnh, DOCX và PPTX; lưu kết quả OCR vào hệ thống lưu trữ và đồng bộ metadata trên Amazon DynamoDB. | 08/07/2026 | 08/07/2026 |  |
| 5 | - Tích hợp Amazon Bedrock để tự động tóm tắt và phân loại tài liệu dựa trên nội dung đã trích xuất, cập nhật kết quả xử lý theo thời gian thực qua AWS AppSync Subscription. | 09/07/2026 | 09/07/2026 |  |
| 6 | - Kiểm thử toàn bộ quy trình từ tải tài liệu, OCR, xử lý AI, lưu kết quả đến cập nhật trạng thái; đánh giá hoạt động của hệ thống và tối ưu luồng xử lý. | 10/07/2026 | 10/07/2026 |  |


### Kết quả đạt được tuần 12:

* Triển khai thành công Amazon Textract với cơ chế xử lý bất đồng bộ, tự động nhận kết quả OCR qua SNS + Lambda.
* Trích xuất thành công nội dung từ nhiều định dạng tài liệu (PDF, hình ảnh, DOCX, PPTX) và đồng bộ metadata lên DynamoDB.
* Tích hợp thành công Amazon Bedrock để tự động tóm tắt và phân loại tài liệu dựa trên nội dung OCR.
* Cập nhật kết quả xử lý theo thời gian thực trên giao diện Angular thông qua AWS AppSync Subscription (GraphQL real-time).
* Hoàn thành kiểm thử end-to-end toàn bộ hệ thống (upload → OCR → AI xử lý → lưu kết quả → hiển thị real-time), hệ thống hoạt động ổn định và sẵn sàng cho báo cáo tốt nghiệp.

---
title: "Worklog Tuần 9"
date: 2024-01-01
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---


### Mục tiêu tuần 9:

* Xây dựng bản đặc tả và kiến trúc tổng thể cho dự án tốt nghiệp: AI-Powered Smart Document Assistant.
* Xác định rõ các dịch vụ AWS sử dụng cho từng thành phần của hệ thống và dự trù chi phí vận hành.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Xây dựng bản đặc tả dự án (Project Specification) cho ứng dụng AI-Powered Smart Document Assistant, sử dụng Angular 18+ kết hợp AWS Amplify Gen 2. | 15/06/2026 | 15/06/2026 | AWS Amplify Gen 2 Documentation Angular Documentation |
| 3 | - Lên danh sách tính năng cốt lõi: Authentication & Authorization, Document Management, User Interface. | 16/06/2026 | 16/06/2026 |  |
| 4 | - Lên danh sách nhóm tính năng AI nổi bật: OCR & Text Extraction, tóm tắt tự động, chat với tài liệu theo cơ chế RAG, phân loại tài liệu tự động, Semantic Search, tạo embedding; và nhóm tính năng nâng cao cho Phase 2 (chia sẻ link có thời hạn, versioning, tag/folder, audit log, dashboard analytics). | 17/06/2026 | 17/06/2026 |  |
| 5 | - Thiết kế kiến trúc hệ thống tổng thể: luồng xử lý từ Angular App qua Amplify Hosting (CloudFront + S3), AWS AppSync (GraphQL), Amazon Cognito, pipeline AI gồm AWS Lambda, Amazon Textract (OCR) và Amazon Bedrock (Claude 3.5 Sonnet). | 18/06/2026 | 18/06/2026 |  |
| 6 | - Xác định cụ thể dịch vụ AWS cho từng layer (Frontend, Backend Framework, Authentication, Storage, Database, API Layer, AI Processing, OCR, Vector Search, Hosting, Monitoring, Security, CI/CD) và ước tính chi phí vận hành khoảng 10–30 USD/tháng. | 19/06/2026 | 19/06/2026 |  |


### Kết quả đạt được tuần 9:

* Hoàn thành bản đặc tả dự án AI-Powered Smart Document Assistant với đầy đủ mục tiêu, phạm vi và công nghệ sử dụng (Angular 18+, AWS Amplify Gen 2).
* Xác định rõ danh sách tính năng cốt lõi và tính năng AI nổi bật, phân chia rõ Phase 1 và Phase 2.
* Thiết kế hoàn chỉnh kiến trúc hệ thống tổng thể (high-level architecture) với đầy đủ các thành phần Frontend, Backend, AI pipeline.
* Lập bảng ánh xạ dịch vụ AWS cho từng layer của hệ thống, làm cơ sở để triển khai ở các tuần tiếp theo.
* Ước tính được chi phí vận hành dự kiến (10–30 USD/tháng), giúp kiểm soát ngân sách khi phát triển và demo dự án.

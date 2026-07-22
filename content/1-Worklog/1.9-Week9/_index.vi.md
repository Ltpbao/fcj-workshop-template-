---
title: "Worklog Tuần 9"
date: 2026-07-20
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

# Worklog Tuần 9 (29/06/2026 – 05/07/2026)

#### 1. Mục tiêu công việc
- Phát triển tính năng **S3 Image Handler** cho hệ thống Backend GearStore.
- Tích hợp chức năng tải hình ảnh sản phẩm lên Amazon S3.
- Lưu đường dẫn **Public URL** của hình ảnh vào Amazon DynamoDB.

#### 2. Chi tiết công việc thực hiện trong tuần
Trong tuần này, tập trung phát triển module **S3 Image Handler** nhằm quản lý việc lưu trữ hình ảnh sản phẩm trên Amazon S3. Tiến hành tích hợp chức năng tải ảnh từ hệ thống quản trị (Admin) lên Amazon S3 thông qua AWS SDK for Java. Sau khi quá trình tải lên hoàn tất, Backend tự động tạo **Public URL** của hình ảnh và lưu đường dẫn này vào Amazon DynamoDB cùng với thông tin sản phẩm. Cuối tuần thực hiện kiểm thử tích hợp để đảm bảo quá trình upload, lưu trữ và truy xuất hình ảnh hoạt động chính xác.

#### 3. Bảng phân công & Tiến độ chi tiết

| Thứ | Nội dung công việc thực hiện | Trạng thái | Nguồn tài liệu |
| :---: | :--- | :---: | :--- |
| **Thứ 2** | Thiết kế kiến trúc module S3 Image Handler | Complete | Project Design |
| **Thứ 3** | Lập trình chức năng tải ảnh lên Amazon S3 | Complete | Project Source Code |
| **Thứ 4** | Sinh Public URL và lưu dữ liệu vào Amazon DynamoDB | Complete | AWS SDK Documentation |
| **Thứ 5** | Tích hợp chức năng upload ảnh vào Product Management API | Complete | Project Source Code |
| **Thứ 6** | Kiểm thử chức năng upload, lưu trữ và truy xuất hình ảnh | Complete | Postman / AWS Console |

#### 4. Kết quả đạt được
- **Hoàn thành**: Xây dựng thành công module **S3 Image Handler**, tích hợp chức năng tải ảnh lên Amazon S3, tự động sinh **Public URL** và lưu thông tin hình ảnh vào Amazon DynamoDB.
- **Kỹ năng tích lũy**: Nâng cao kỹ năng phát triển Backend với Java và AWS SDK, tích hợp dịch vụ lưu trữ Amazon S3 với cơ sở dữ liệu Amazon DynamoDB và xây dựng quy trình quản lý hình ảnh cho ứng dụng thực tế.
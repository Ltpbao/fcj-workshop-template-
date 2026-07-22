---
title: "Worklog Tuần 7"
date: 2026-07-20
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

# Worklog Tuần 7 (15/06/2026 – 21/06/2026)

#### 1. Mục tiêu công việc
- Tìm hiểu AWS SDK for Java và Amazon S3 Client.
- Thực hành lập trình các thao tác cơ bản với Amazon S3.
- Nghiên cứu cơ chế quản lý đối tượng và phân quyền truy cập trên Amazon S3.

#### 2. Chi tiết công việc thực hiện trong tuần
Trong tuần này, tập trung nghiên cứu AWS SDK for Java để tích hợp dịch vụ Amazon S3 vào hệ thống Backend của dự án GearStore. Tìm hiểu cách khởi tạo Amazon S3 Client, cấu hình thông tin xác thực (AWS Credentials) và thiết lập kết nối với dịch vụ lưu trữ trên AWS. Thực hành lập trình các chức năng tải tệp lên Amazon S3 bằng **PutObject**, xóa tệp bằng **DeleteObject** và cấu hình quyền đọc công khai (Public Read) để các hình ảnh có thể được truy cập từ ứng dụng. Cuối tuần tiến hành kiểm thử các chức năng nhằm đảm bảo dữ liệu được lưu trữ và quản lý chính xác.

#### 3. Bảng phân công & Tiến độ chi tiết

| Thứ | Nội dung công việc thực hiện | Trạng thái | Nguồn tài liệu |
| :---: | :--- | :---: | :--- |
| **Thứ 2** | Nghiên cứu AWS SDK for Java và Amazon S3 Client | Complete | AWS SDK Documentation |
| **Thứ 3** | Cấu hình AWS Credentials và khởi tạo Amazon S3 Client | Complete | AWS Documentation |
| **Thứ 4** | Lập trình chức năng tải tệp bằng PutObject | Complete | Project Source Code |
| **Thứ 5** | Lập trình DeleteObject và thiết lập quyền Public Read | Complete | Project Source Code |
| **Thứ 6** | Kiểm thử chức năng upload, xóa và truy cập tệp trên Amazon S3 | Complete | AWS Console / Postman |

#### 4. Kết quả đạt được
- **Hoàn thành**: Tích hợp thành công AWS SDK for Java, khởi tạo Amazon S3 Client, xây dựng chức năng tải và xóa tệp trên Amazon S3, đồng thời thiết lập quyền truy cập công khai cho các tệp được lưu trữ.
- **Kỹ năng tích lũy**: Thành thạo việc tích hợp dịch vụ Amazon S3 vào ứng dụng Java, quản lý tệp tin trên nền tảng Cloud và lập trình các thao tác lưu trữ dữ liệu thông qua AWS SDK.
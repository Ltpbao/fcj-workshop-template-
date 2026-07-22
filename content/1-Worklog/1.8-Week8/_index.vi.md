---
title: "Worklog Tuần 8"
date: 2026-07-20
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

# Worklog Tuần 8 (22/06/2026 – 28/06/2026)

#### 1. Mục tiêu công việc
- Khởi tạo Amazon S3 Bucket phục vụ dự án GearStore.
- Thiết lập CORS để Frontend có thể truy cập hình ảnh sản phẩm.
- Kiểm thử việc hiển thị hình ảnh từ Amazon S3 trên giao diện người dùng.

#### 2. Chi tiết công việc thực hiện trong tuần
Trong tuần này, tiến hành triển khai Amazon S3 Bucket chính thức để lưu trữ hình ảnh sản phẩm của dự án GearStore. Thực hiện cấu hình Bucket, tổ chức cấu trúc thư mục lưu trữ và thiết lập chính sách Cross-Origin Resource Sharing (CORS) nhằm cho phép ứng dụng Frontend truy cập tài nguyên hình ảnh từ Amazon S3 một cách an toàn. Sau khi hoàn tất cấu hình, tiến hành kiểm thử việc tải và hiển thị hình ảnh thông qua Public URL để đảm bảo quá trình tích hợp giữa Backend, Amazon S3 và Frontend hoạt động ổn định.

#### 3. Bảng phân công & Tiến độ chi tiết

| Thứ | Nội dung công việc thực hiện | Trạng thái | Nguồn tài liệu |
| :---: | :--- | :---: | :--- |
| **Thứ 2** | Khởi tạo Amazon S3 Bucket cho dự án GearStore | Complete | AWS Console |
| **Thứ 3** | Cấu hình Bucket và tổ chức thư mục lưu trữ | Complete | AWS Documentation |
| **Thứ 4** | Thiết lập chính sách Cross-Origin Resource Sharing (CORS) | Complete | AWS Documentation |
| **Thứ 5** | Kiểm thử việc hiển thị hình ảnh trên Frontend thông qua Public URL | Complete | Project Source Code |
| **Thứ 6** | Rà soát cấu hình Bucket và tối ưu hóa lưu trữ | Complete | AWS Console / Postman |

#### 4. Kết quả đạt được
- **Hoàn thành**: Khởi tạo và cấu hình thành công Amazon S3 Bucket cho GearStore, thiết lập CORS, đồng thời tích hợp thành công việc hiển thị hình ảnh sản phẩm từ Amazon S3 trên giao diện Frontend.
- **Kỹ năng tích lũy**: Nắm vững quy trình triển khai dịch vụ lưu trữ Amazon S3 trong dự án thực tế, cấu hình CORS cho ứng dụng web và tích hợp hiệu quả giữa Backend, Frontend và dịch vụ lưu trữ trên nền tảng AWS.
---
title: "Worklog Tuần 11"
date: 2026-07-20
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

# Worklog Tuần 11 (13/07/2026 – 19/07/2026)

#### 1. Mục tiêu công việc
- Xây dựng API khôi phục dữ liệu cho hệ thống GearStore.
- Tự động hóa quá trình đồng bộ và seeding dữ liệu.
- Tích hợp Amazon DynamoDB và Amazon S3 vào quy trình khởi tạo dữ liệu.

#### 2. Chi tiết công việc thực hiện trong tuần
Trong tuần này, tập trung phát triển API **`POST /products/reset-database`** nhằm tự động hóa toàn bộ quá trình khôi phục dữ liệu của hệ thống GearStore. Tiến hành xây dựng luồng xử lý bao gồm xóa dữ liệu sản phẩm hiện có trong Amazon DynamoDB, dọn dẹp toàn bộ hình ảnh lưu trữ trên Amazon S3 và tự động nhập lại dữ liệu mẫu vào hệ thống. Đồng thời tích hợp chức năng tải hình ảnh sản phẩm từ Unsplash, upload lên Amazon S3, sinh **Public URL** và cập nhật đường dẫn hình ảnh vào cơ sở dữ liệu. Cuối tuần thực hiện kiểm thử toàn bộ quy trình để đảm bảo việc khởi tạo dữ liệu chỉ cần một lần gọi API.

#### 3. Bảng phân công & Tiến độ chi tiết

| Thứ | Nội dung công việc thực hiện | Trạng thái | Nguồn tài liệu |
| :---: | :--- | :---: | :--- |
| **Thứ 2** | Thiết kế luồng xử lý API khôi phục dữ liệu | Complete | Project Design |
| **Thứ 3** | Xây dựng API `POST /products/reset-database` | Complete | Project Source Code |
| **Thứ 4** | Tích hợp chức năng dọn dẹp Amazon DynamoDB và Amazon S3 | Complete | AWS SDK Documentation |
| **Thứ 5** | Nhập dữ liệu mẫu và tải hình ảnh từ Unsplash lên Amazon S3 | Complete | Unsplash API / AWS SDK |
| **Thứ 6** | Kiểm thử toàn bộ quy trình đồng bộ và khôi phục dữ liệu | Complete | Postman / AWS Console |

#### 4. Kết quả đạt được
- **Hoàn thành**: Xây dựng thành công API **`POST /products/reset-database`**, tự động dọn dẹp dữ liệu trên Amazon DynamoDB và Amazon S3, đồng thời hoàn thiện quy trình khởi tạo lại dữ liệu và hình ảnh cho hệ thống.
- **Kỹ năng tích lũy**: Nâng cao kỹ năng thiết kế API Backend, xây dựng quy trình tự động hóa dữ liệu, tích hợp nhiều dịch vụ AWS và triển khai cơ chế đồng bộ dữ liệu phục vụ ứng dụng thực tế.
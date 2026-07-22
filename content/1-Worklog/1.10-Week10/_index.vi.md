---
title: "Worklog Tuần 10"
date: 2026-07-20
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

# Worklog Tuần 10 (06/07/2026 – 12/07/2026)

#### 1. Mục tiêu công việc
- Xây dựng cơ chế tự động dọn dẹp tài nguyên trên Amazon S3.
- Tự động xóa hình ảnh cũ khi sản phẩm được cập nhật hoặc xóa.
- Tối ưu việc quản lý tài nguyên lưu trữ trên nền tảng AWS.

#### 2. Chi tiết công việc thực hiện trong tuần
Trong tuần này, tập trung hoàn thiện quy trình quản lý hình ảnh của dự án GearStore bằng cách xây dựng cơ chế tự động dọn dẹp tài nguyên trên Amazon S3. Tiến hành phát triển logic Backend để phát hiện các trường hợp sản phẩm được cập nhật hình ảnh hoặc bị xóa khỏi hệ thống, từ đó tự động gọi API **DeleteObject** của Amazon S3 nhằm xóa các tệp không còn sử dụng. Việc triển khai cơ chế này giúp tránh phát sinh dữ liệu dư thừa, tối ưu chi phí lưu trữ và đảm bảo tính đồng nhất giữa dữ liệu sản phẩm trong Amazon DynamoDB và hình ảnh trên Amazon S3. Cuối tuần thực hiện kiểm thử nhiều kịch bản nhằm xác nhận tính chính xác của chức năng.

#### 3. Bảng phân công & Tiến độ chi tiết

| Thứ | Nội dung công việc thực hiện | Trạng thái | Nguồn tài liệu |
| :---: | :--- | :---: | :--- |
| **Thứ 2** | Phân tích quy trình quản lý vòng đời hình ảnh và yêu cầu dọn dẹp tài nguyên | Complete | Project Design |
| **Thứ 3** | Phát triển chức năng tự động xóa hình ảnh trên Amazon S3 | Complete | Project Source Code |
| **Thứ 4** | Tích hợp API DeleteObject vào Product Service | Complete | AWS SDK Documentation |
| **Thứ 5** | Kiểm thử chức năng xóa ảnh khi cập nhật hoặc xóa sản phẩm | Complete | Postman / AWS Console |
| **Thứ 6** | Tối ưu hóa logic xử lý và đánh giá tính đồng bộ dữ liệu | Complete | Self-testing |

#### 4. Kết quả đạt được
- **Hoàn thành**: Xây dựng thành công cơ chế tự động dọn dẹp tài nguyên trên Amazon S3, tích hợp API **DeleteObject** vào hệ thống Backend và đảm bảo dữ liệu hình ảnh luôn đồng bộ với thông tin sản phẩm.
- **Kỹ năng tích lũy**: Nâng cao kỹ năng phát triển Backend với AWS SDK, quản lý vòng đời tài nguyên trên Amazon S3 và xây dựng cơ chế tự động tối ưu hóa tài nguyên cho ứng dụng thực tế.
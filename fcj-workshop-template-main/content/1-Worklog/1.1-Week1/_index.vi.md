---
title: "Worklog Tuần 1"
date: 2026-04-20
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---


### Mục tiêu tuần 1:

* Tìm hiểu các kiến thức nền tảng về AWS Cloud, chính sách AWS Free Tier 2025 và các công cụ hỗ trợ quản lý chi phí trong quá trình sử dụng dịch vụ AWS.
* Nắm được cơ chế quản lý định danh, phân quyền truy cập và cấp quyền cho dịch vụ AWS thông qua AWS IAM và IAM Role.
* Làm quen với môi trường phát triển AWS Cloud9 và các dịch vụ hạ tầng cơ bản gồm Amazon VPC, Amazon EC2, Amazon S3 và Amazon RDS.
* Thực hành triển khai các tài nguyên AWS cơ bản nhằm xây dựng nền tảng cho các bài thực hành và dự án ở những tuần tiếp theo.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2   | - Xem lại chính sách AWS Free Tier 2025 và các giới hạn sử dụng dịch vụ<br>- Tạo AWS Budget và thiết lập cảnh báo chi phí<br>- Gửi yêu cầu hỗ trợ tới AWS Support để tìm hiểu cơ bản về quy trình hỗ trợ | 20/04/2026   | 20/04/2026      | <https://000001.awsstudygroup.com/vi/> <br><br> <https://000007.awsstudygroup.com/vi/> <br><br> <https://000009.awsstudygroup.com/vi/> |
| 3   | - Tìm hiểu cơ chế IAM để quản lý quyền truy cập và phân quyền cho tài nguyên AWS<br>- Tạo IAM user, IAM group và cấu hình policy cho việc phân quyền<br>- Gán IAM role cho các dịch vụ AWS và kiểm tra quyền truy cập theo vai trò | 21/04/2026   | 21/04/2026      | <https://000002.awsstudygroup.com/vi/> <br><br> <https://000048.awsstudygroup.com/vi/> |
| 4   | - Khởi tạo môi trường AWS Cloud9 để phát triển trên trình duyệt<br>- Tạo S3 bucket và cấu hình dịch vụ hosting static website<br>- Upload mã nguồn mẫu và kiểm tra endpoint website công khai | 22/04/2026   | 22/04/2026      | <https://000049.awsstudygroup.com/vi/> <br><br> <https://000057.awsstudygroup.com/vi/> |
| 5   | - Thiết kế mạng VPC tùy chỉnh với subnet công khai và riêng tư<br>- Cấu hình route table, CIDR block và internet gateway<br>- Kiểm tra kết nối mạng cơ bản trong môi trường AWS | 23/04/2026   | 23/04/2026      | <https://000003.awsstudygroup.com/vi/> |
| 6   | - Khởi tạo EC2 instance và kết nối tới máy chủ bằng SSH<br>- Tạo RDS MySQL instance và cấu hình security group phù hợp<br>- Kiểm tra kết nối giữa EC2 và RDS để sử dụng cho ứng dụng | 24/04/2026   | 24/04/2026      | <https://000004.awsstudygroup.com/vi/> <br><br> <https://000005.awsstudygroup.com/vi/> |

### Kết quả đạt được tuần 1:

#### 1. Tìm hiểu về AWS Free Tier 2025
* Hiểu được các gói sử dụng miễn phí của AWS như Always Free, 12 Months Free và Trial.
* Nắm được các giới hạn sử dụng của một số dịch vụ phổ biến trên AWS.
* Biết cách theo dõi lượng tài nguyên sử dụng để kiểm soát chi phí hiệu quả hơn.

#### 2. Quản lý chi phí với AWS Budget
* Hiểu được cách AWS Budget hỗ trợ theo dõi và kiểm soát ngân sách sử dụng dịch vụ.
* Tạo budget để giám sát mức tiêu thụ tài nguyên.
* Thiết lập email notification để nhận cảnh báo khi chi phí vượt ngưỡng đã đặt.

#### 3. Làm quen với AWS Support
* Nắm được các loại hỗ trợ mà AWS cung cấp.
* Hiểu quy trình tạo và quản lý support case.
* Phân biệt được các nhóm yêu cầu hỗ trợ như billing, technical support và service limit increase.

#### 4. Tìm hiểu về IAM
* Hiểu được vai trò của IAM user, IAM group và IAM policy trong hệ thống bảo mật AWS.
* Nắm được nguyên tắc phân quyền tối thiểu để giảm rủi ro về bảo mật.
* Có thêm kiến thức về cách kiểm soát quyền truy cập tới các tài nguyên trên AWS.

#### 5. Thực hành quản lý người dùng và phân quyền
* Tạo được IAM user và IAM group.
* Gán policy cho user và group phù hợp với từng nhu cầu sử dụng.
* Kiểm tra lại quyền truy cập sau khi cấu hình phân quyền.

#### 6. Tìm hiểu về IAM Role
* Phân biệt được IAM user và IAM role.
* Hiểu cơ chế hoạt động của trust policy và permission policy.
* Nắm được cách cấp quyền cho các dịch vụ AWS mà không cần dùng trực tiếp access key.

#### 7. Thực hành gán quyền qua IAM Role
* Tạo IAM role và liên kết với các dịch vụ AWS.
* Kiểm tra luồng truy cập thông qua role được cấp.
* Xác nhận rằng tài nguyên có thể được truy cập đúng theo quyền được phân bổ.

#### 8. Khởi đầu với AWS Cloud9
* Thiết lập được môi trường phát triển trên nền tảng đám mây.
* Sử dụng được trình soạn thảo trên trình duyệt và terminal tích hợp.
* Làm quen với các công cụ hỗ trợ phát triển cơ bản trên AWS Cloud9.

#### 9. Tìm hiểu Amazon S3 và hosting website tĩnh
* Hiểu được mô hình lưu trữ object storage của Amazon S3.
* Tạo bucket và quản lý các object đã upload.
* Cấu hình static website hosting và kiểm tra endpoint của website công khai.

#### 10. Tìm hiểu về Amazon VPC
* Hiểu được vai trò quan trọng của VPC trong việc xây dựng hạ tầng mạng trên AWS.
* Nắm được các thành phần cơ bản như CIDR block, subnet, route table và internet gateway.
* Phân biệt được sự khác nhau giữa public subnet và private subnet.

#### 11. Thực hành triển khai hạ tầng mạng
* Tạo được VPC tùy chỉnh cho môi trường lab.
* Thiết lập subnet công khai và cấu hình định tuyến mạng.
* Kiểm tra được khả năng kết nối mạng trong môi trường AWS.

#### 12. Tìm hiểu về Amazon EC2
* Hiểu được khái niệm máy chủ ảo trên AWS.
* Nắm được các thành phần như AMI, instance type, key pair và security group.
* Hiểu được quy trình khởi tạo và quản lý EC2 instance.

#### 13. Thực hành triển khai EC2
* Tạo được EC2 instance và cấu hình các thiết lập bảo mật cơ bản.
* Kết nối vào server qua SSH.
* Kiểm tra được trạng thái hoạt động của instance.

#### 14. Tìm hiểu về Amazon RDS
* Hiểu được mô hình database được quản lý trên AWS.
* Tìm hiểu các thành phần như database instance, database engine và endpoint.
* Nhận thức được tầm quan trọng của bảo mật và kiểm soát truy cập trong cơ sở dữ liệu.

#### 15. Thực hành triển khai Amazon RDS
* Tạo được RDS MySQL instance cho môi trường thực hành.
* Cấu hình các tham số cơ bản cho database.
* Thiết lập security group để cho phép kết nối đúng cách.
* Kiểm tra được kết nối giữa EC2 instance và RDS instance.



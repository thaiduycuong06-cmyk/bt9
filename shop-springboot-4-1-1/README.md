# Spring Boot + Security (Bài 9)

Project này chứa khung sườn cơ bản cho Ví dụ 3: **Shop Application (Spring Boot 4.1.1 + Spring Security 7.x + MapStruct + Thymeleaf)**.

## Cấu trúc project
- **pom.xml**: Đã cấu hình đầy đủ các dependency (Spring Boot Web, Security, Data JPA, Thymeleaf, MapStruct, Cloudinary, Lombok, SQL Server).
- **application.properties** & **.env**: Cấu hình kết nối SQL Server, Cloudinary, và Mail.
- **Entity**: Đã tạo các bảng `User`, `Role`, `Product`, và `OtpToken` với đầy đủ relationship.
- **Config**: Đã tạo `SecurityConfig` xử lý phân quyền URL, form login, logout, và session management.

## Các bước tiếp theo để hoàn thiện
Sinh viên có thể tiếp tục thêm các file DTO, Repository, Service (như trong file Hướng Dẫn) vào các package tương ứng đã được tạo sẵn (`dto`, `mapper`, `repository`, `service`, `controller`), và thêm các file giao diện HTML vào thư mục `src/main/resources/templates/`.

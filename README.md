# Employee Management System

Hệ thống quản lý nhân viên và chấm công được xây dựng bằng **Java Spring Boot** và **ReactJS**, sử dụng MySQL để lưu trữ dữ liệu.

Dự án được phát triển nhằm áp dụng kiến thức Java, Spring Boot, RESTful API, cơ sở dữ liệu và phát triển giao diện web vào một sản phẩm thực tế.

## 1. Công nghệ sử dụng

### Backend
- Java
- Spring Boot
- Spring Security
- Spring Data JPA / Hibernate
- MySQL
- Maven
- RESTful API

### Frontend
- ReactJS
- Vite
- JavaScript
- Axios
- React Router

## 2. Các chức năng chính

- Đăng nhập và phân quyền ADMIN / EMPLOYEE.
- Quản lý nhân viên: thêm, sửa, tìm kiếm và xem thông tin.
- Quản lý phòng ban.
- Quản lý tài khoản người dùng.
- Quản lý chấm công: check-in, check-out.
- Chấm công bằng mã QR.
- Tự động ghi nhận nhân viên vắng mặt theo lịch.
- Dashboard hiển thị tổng quan tình hình nhân sự.

## 3. Kiến trúc dự án

Dự án được chia thành hai phần độc lập:

| Thành phần | Công nghệ |
|---|---|
| Backend | Java Spring Boot |
| Frontend | ReactJS |
| Database | MySQL |

## 4. Source Code

### Backend – Spring Boot

[Employee Management Backend](https://github.com/nguyentuanvu-26/employee-management-backend)

### Frontend – ReactJS

[Employee Management Frontend](https://github.com/nguyentuanvu-26/employee-management-frontend)

## 5. Hướng dẫn chạy dự án

### Backend
1. Cài đặt JDK và MySQL.
2. Tạo database `employee_management`.
3. Cấu hình kết nối database trong `application.properties`.
4. Chạy ứng dụng Spring Boot.

Backend mặc định chạy tại:

`http://localhost:8080`

### Frontend
1. Cài đặt Node.js.
2. Clone repository frontend.
3. Mở terminal tại thư mục frontend.
4. Chạy các lệnh:

```bash
npm install
npm run dev
```

Frontend mặc định chạy tại:

`http://localhost:5173`

## 6. Mục tiêu dự án

Dự án giúp củng cố kiến thức lập trình Java, lập trình hướng đối tượng, xây dựng REST API, quản lý cơ sở dữ liệu, xác thực và phân quyền người dùng, đồng thời thực hành tích hợp Backend với Frontend.

## Author

**Nguyễn Tuấn Vũ**

GitHub: [nguyentuanvu-26](https://github.com/nguyentuanvu-26)

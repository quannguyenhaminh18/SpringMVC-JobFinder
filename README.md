# 🧭 JobFinder - Spring MVC Web Application

**JobFinder** là một ứng dụng web mô phỏng nền tảng tìm việc, được xây dựng bằng Java 1.8, Spring MVC và Thymeleaf. Ứng dụng hỗ trợ đăng ký, đăng nhập, quản lý người dùng và tin tuyển dụng với phân quyền người dùng.

---

## ⚙️ Công nghệ sử dụng

- Java 1.8
- Spring MVC
- Spring Data JPA
- Hibernate
- JSP / Thymeleaf (qua thư mục `webapp`)
- MySQL
- Gradle

---

## 🗂️ Cấu trúc dự án

src/main/
├── java/com/
│ ├── controller/ <-- Xử lý HTTP request
│ ├── service/ <-- Business logic
│ ├── repo/ <-- JPA repository
│ ├── entity/ <-- Entity ánh xạ CSDL
│ ├── dto/ <-- Dữ liệu trung gian giữa client/server
│ ├── config/ <-- Cấu hình Spring, bảo mật, i18n, view resolver
│ ├── exception/ <-- Xử lý ngoại lệ
│ ├── enums/ <-- Enum dùng chung
│ ├── util/ <-- Helper, tiện ích
│ └── advice/ <-- Global exception handler
│
├── resources/ <-- messages.properties, cấu hình i18n
└── webapp/
└── WEB-INF/ <-- View (JSP hoặc Thymeleaf)
├── auth/ <-- Login, register
├── admin/ <-- Quản trị viên
├── candidate/ <-- Người tìm việc
├── recruiter/ <-- Nhà tuyển dụng
└── post/ <-- Tin tuyển dụng


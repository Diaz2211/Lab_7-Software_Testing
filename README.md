# BÁO CÁO LAB 7: KIỂM THỬ API BẰNG POSTMAN

## 1. Giới thiệu về Postman
**Postman** là một trong những nền tảng (API Platform) phổ biến nhất hiện nay dành cho các lập trình viên và kiểm thử viên (QA/Tester) trong việc phát triển, kiểm thử và quản lý API (Application Programming Interface).

Postman cung cấp giao diện trực quan, dễ sử dụng, cho phép gửi các yêu cầu HTTP (như `GET`, `POST`, `PUT`, `DELETE`) đến máy chủ và nhận về kết quả phản hồi chi tiết. Bên cạnh việc kiểm thử thủ công các endpoint, Postman còn hỗ trợ viết các kịch bản kiểm thử tự động (Test Scripts) bằng JavaScript, thiết lập biến môi trường (Environment Variables) và tự động hóa quy trình chạy kiểm thử hàng loạt (Collection Runner), giúp nâng cao hiệu suất làm việc và đảm bảo chất lượng phần mềm.

---

## 2. Kết quả Thực hành Kiểm thử API

### 2.1. Yêu cầu GET (Lấy dữ liệu)
Thực hiện gửi request `GET` đến endpoint `postman-echo.com/get` để truy vấn thông tin dữ liệu từ máy chủ.

<img width="1917" alt="GET Request" src="https://github.com/user-attachments/assets/d3d5f42e-3ce1-412b-a792-5429fa540beb" />

---

### 2.2. Yêu cầu POST (Tạo/Gửi dữ liệu)
Thực hiện gửi request `POST` đến endpoint `postman-echo.com/post` kèm dữ liệu dạng JSON ở phần Body.

<img width="1920" alt="POST Request" src="https://github.com/user-attachments/assets/15d2fcb3-e35c-4bf3-816e-02d5086083eb" />

---

### 2.3. Kiểm thử tự động với Test Scripts
Sử dụng mã JavaScript trong tab **Tests** để tự động kiểm tra phản hồi từ máy chủ (Status Code 200 OK, thời gian phản hồi, định dạng JSON). Kết quả kiểm thử đạt **PASS 3/3**.

<img width="1920" alt="Test Results" src="https://github.com/user-attachments/assets/0c43425f-a4cc-43a5-80ad-eaee0e5b7e8f" />

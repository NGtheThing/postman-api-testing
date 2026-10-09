# BÁO CÁO THỰC HÀNH KIỂM THỬ API VỚI POSTMAN

## Thông tin sinh viên
* **Họ và tên**: Nguyễn Thế Thịnh
* **Mã sinh viên**: [23010497]
* **Lớp**: [Đánh giá chất lượng kiểm định]
* **Link Video Tham Khảo**: https://www.youtube.com/watch?v=MFxk5BZulVU

---

## 1. Giới thiệu
Báo cáo trình bày kết quả thực hành công cụ kiểm thử API **Postman**, bao gồm gửi các yêu cầu HTTP Request (`GET`, `POST`), tự động hóa kịch bản kiểm thử bằng Javascript (Test Scripts) và thực thi kiểm thử hàng loạt bằng **Collection Runner**.

---

## 2. Kết quả thực hiện

### 2.1. Yêu cầu GET (Lấy danh sách dữ liệu)
* **Endpoint**: `https://reqres.in/api/users?page=1`
* **Status**: `200 OK`
* **Mô tả**: Gửi yêu cầu lấy danh sách người dùng thành công và kiểm tra tự động Status Code.

<img width="975" height="519" alt="image" src="https://github.com/user-attachments/assets/0948ae11-838c-44f3-8287-c24d444aee33" />

---

### 2.2. Yêu cầu POST (Tạo dữ liệu mới)
* **Endpoint**: `https://reqres.in/api/users`
* **Status**: `201 Created`
* **Mô tả**: Tạo dữ liệu người dùng mới với thông tin truyền vào qua Body dạng JSON.

<img width="975" height="511" alt="image" src="https://github.com/user-attachments/assets/84a741d9-58e3-49da-b52d-62f681b1173a" />

---

### 2.3. Chạy tự động với Collection Runner
* Sử dụng **Collection Runner** thực thi tự động toàn bộ kịch bản kiểm thử trong Collection `My Collection`.
* **Kết quả**: Tất cả bài test đều đạt trạng thái **PASSED**.

<img width="1088" height="942" alt="image" src="https://github.com/user-attachments/assets/9112a402-acc4-4aec-a5f6-36e69161a4e6" />

---

## 3. Tổng kết
* Đã xuất và lưu trữ thành công file Collection `.json` tại Repository này.
* Thành thạo quy trình kiểm thử API cơ bản và tự động hóa với Postman.

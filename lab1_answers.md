# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Đặng Hồng Trung

**MSSV:** 1871020595

**Lớp/Nhóm:** CNTT18-01

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1:Dữ liệu điểm sinh viên (grades database)
- Asset 2:Thông tin tài khoản người dùng (username, password)
- Asset 3 (nếu có):Hệ thống quản lý điểm (server, ứng dụng)

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A -> : Lộ dữ liệu điểm → Confidentiality
- Sự cố B -> : Bị sửa điểm trái phép → Integrity
- Sự cố C ->: Hệ thống bị sập, không truy cập được → Availability

---

## 3. Phân tích sự cố B
- Threat: Hacker hoặc người dùng nội bộ cố tình thay đổi điểm
- Vulnerability: Không kiểm tra quyền truy cập chặt chẽ
                Mật khẩu yếu / không mã hóa
                Thiếu log theo dõi thay đổi dữ liệu 
- Mitigation: Áp dụng phân quyền (role-based access control)
Mã hóa mật khẩu (hashing)
Ghi log và kiểm tra lịch sử thay đổi
Xác thực 2 yếu tố (2FA)

---

## 4. Reflection
Viết 5-7 dòng.
Qua bài này, em hiểu rõ hơn về mô hình CIA gồm bảo mật, toàn vẹn và sẵn sàng của hệ thống. Trong hệ thống lưu điểm, việc đảm bảo tính toàn vẹn là rất quan trọng vì điểm số ảnh hưởng trực tiếp đến sinh viên. Ngoài ra, bảo mật thông tin cũng giúp tránh rò rỉ dữ liệu cá nhân. Em nhận ra rằng nhiều rủi ro xuất phát từ lỗ hổng hệ thống và cách quản lý chưa chặt chẽ. Vì vậy, cần áp dụng các biện pháp bảo mật như phân quyền và mã hóa. Bài học này giúp em có cái nhìn thực tế hơn về an toàn thông tin.


--- 

## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`

Flag của em: 
fit4012-lab0-cia-risk-starter-dhtr286


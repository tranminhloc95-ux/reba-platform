# REBA™ – Smart Trading Rebate Platform

REBA là nền tảng rebate (hoàn phí giao dịch) được thiết kế theo tư duy **long-term product**: rõ ràng, tối giản, có thể mở rộng mà không phá vỡ cấu trúc ban đầu.

Triết lý cốt lõi của dự án:

> Trade không cần thay đổi. Hệ thống phía sau mới là thứ cần tối ưu.

---

## 🎯 Mục tiêu của phiên bản V1.0

V1.0 **không nhằm cung cấp đầy đủ tính năng**, mà tập trung vào:

* Định hình thương hiệu (branding & positioning)
* Xây dựng nền tảng giao diện ổn định
* Tạo bộ khung để mở rộng các version tiếp theo

V1.0 đóng vai trò như **bản móng kiến trúc** cho toàn bộ hệ thống.

---

## 🧱 Phạm vi V1.0

Bao gồm:

* Landing page giới thiệu nền tảng
* Cấu trúc UI theo phong cách fintech
* Nội dung định vị: minh bạch – không chiêu trò – hướng dài hạn

Chưa bao gồm:

* Đăng nhập / đăng ký
* Dashboard người dùng
* Backend, database, API
* Tracking rebate real-time

Những phần này sẽ được phát triển ở các version sau.

---

## 🗂️ Cấu trúc thư mục (đề xuất)

```
reba-platform/
│
├── index.html        # Landing page chính (V1.0)
├── assets/
│   ├── css/          # Style tách riêng ở các version sau
│   ├── img/          # Logo, hình minh họa
│   └── fonts/        # Font custom (nếu có)
│
├── docs/
│   └── roadmap.md   # Lộ trình phát triển sản phẩm
│
└── README.md
```

---

## 🧭 Roadmap định hướng (tóm tắt)

* **V1.0** – Branding & Landing (current)
* **V1.5** – UI components + mock data
* **V2.0** – User dashboard (frontend)
* **V2.5** – Tracking & reporting logic
* **V3.0** – Backend & rebate engine

Chi tiết roadmap sẽ được cập nhật trong thư mục `/docs`.

---

## ⚠️ Tuyên bố minh bạch

REBA không giữ tiền người dùng.
Rebate được xử lý thông qua cơ chế IB / broker-side.
Nền tảng chỉ đóng vai trò theo dõi, tổng hợp và phân phối thông tin rebate.

---

## 📌 Ghi chú

Dự án được xây dựng với tư duy:

* Ưu tiên độ bền hơn tốc độ
* Ưu tiên rõ ràng hơn hào nhoáng
* Ưu tiên hệ thống hơn chiêu trò

---

© 2026 REBA™ – Built for traders who think long-term

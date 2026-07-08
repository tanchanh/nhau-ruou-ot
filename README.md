# 🪵 Công Thức Nhàu & Rượu Ớt

Ứng dụng web công cụ giúp tự động **hoà** trộn tỉ lệ nguyên liệu chính xác khi làm Nhàu ngâm đường hoặc Rượu ớt.

---

## ✨ Tính Năng Nổi Bật

* **Giao diện kép (Dual Theme):** Tự động chuyển đổi màu sắc toàn bộ giao diện theo nguyên liệu (Nâu trầm cho **Nhàu** 🪵 | Đỏ chili cho **Rượu Ớt** 🌶️).
* **Tính toán tức thì:** Kết quả cập nhật ngay lập tức theo thời gian thực (Real-time) ngay khi bạn nhập số liệu mà không cần bấm nút.
* **Chạy hoàn toàn Offline:** Chỉ gồm một file HTML duy nhất, không phụ thuộc vào bất kỳ thư viện ngoài nào, có thể lưu về máy và chạy không cần mạng.

---

## 📐 Công Thức Cốt Lõi

| Chế độ ngâm | Tỉ lệ chuẩn tích hợp | Công thức tính toán |
| --- | --- | --- |
| **Nhàu Ngâm Đường** | $18\%$ đến $20\%$ khối lượng nhàu | $\text{Đường} = \text{Nhàu} \times (0.18 \rightarrow 0.20)$ |
| **Rượu Ớt** | $200\text{g}$ ớt chỉ thiên / $1\text{L}$ rượu $40^\circ$ | $\text{Ớt (gam)} = \frac{\text{Rượu (ml)}}{5}$ |

---

## 🛠️ Hướng Dẫn Sử Dụng

* **Chọn chế độ:** Nhấp vào nút **Nhàu Ngâm Đường** hoặc **Rượu Ớt** ở đầu trang để chuyển đổi giao diện và công thức tương ứng.
* **Nhập số liệu:** Điền khối lượng nguyên liệu bạn đang có vào ô nhập liệu:
* Nhập lượng **Nhàu (gam)** ở chế độ Nhàu (Mặc định: $1000\text{g}$).
* Nhập lượng **Rượu (ml)** ở chế độ Rượu Ớt (Mặc định: $1000\text{ml}$).

* **Nhận kết quả:** Ứng dụng tự động tính và hiển thị ngay khoảng lượng **Đường (gam)** hoặc lượng **Ớt (gam)** cần chuẩn bị.
* **Xem hướng dẫn:** Thực hiện theo các bước chuẩn bị, thời gian ngâm và liều lượng dùng được liệt kê chi tiết ở khung dưới cùng.

---

## 📝 Thông Tin Phát Triển

* **Tác giả:** Dương Tấn Chánh
* **Mã nguồn:** HTML5, CSS3 (Biến CSS định hình giao diện), JavaScript Thuần (Vanilla JS)

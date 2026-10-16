# 🚀 SMART-FARM: Hệ thống IoT cho Trang Trại Lan

Hệ thống IoT thông minh giúp tự động hóa toàn diện quy trình theo dõi môi trường, tưới nước tự động, cảnh báo kịp thời và tối ưu hóa chi phí vận hành cho trang trại lan.

## Hướng dẫn cài đặt

```bash
# 1. Tải và cài đặt mã nguồn ứng dụng Smart-Farm
git clone https://github.com/smart-farm/orchid-app.git

# 2. Cài đặt các gói thư viện phụ thuộc cho Gateway
cd smart-farm-gateway && npm install

# 3. Khởi chạy hệ thống giám sát và đồng bộ dữ liệu thời gian thực
npm run start
```

---

## Tính năng chính

- [x] Đăng nhập quản lý hệ thống bảo mật thời gian thực
- [x] Giám sát thông số môi trường (Nhiệt độ, độ ẩm không khí, độ ẩm đất, ánh sáng, EC, pH)
- [x] Nhận cảnh báo tức thời khi các thông số vượt ngưỡng an toàn
- [x] Điều khiển thiết bị thủ công hoặc chuyển sang chế độ Tự động thông minh
- [x] Xem báo cáo dữ liệu lịch sử theo ngày, tuần, tháng và xuất file báo cáo

---

## Bảng thông số kỹ thuật chuẩn

| Thông số | Ngưỡng tối ưu | Trạng thái cảnh báo | Thiết Bị |
| :--- | :--- | :--- | :--- |
| **Nhiệt độ** | 25C – 30C | > 30C | Quạt thông gió |
| **Độ ẩm không khí** | 70% – 85% | < 60% (Cảnh báo) | Hệ thống phun sương |
| **Độ ẩm đất** | 65% – 80% | < 50% (Cảnh báo) | Máy bơm tưới tự động |
| **Ánh sáng** | 1000 – 1500 lux | Tùy chỉnh theo sinh trưởng | Đèn bổ sung quang hợp |


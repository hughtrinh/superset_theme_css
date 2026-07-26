# Bộ theme CSS dành cho Apache Superset

Mỗi file CSS trong thư mục là một theme hoàn chỉnh và độc lập. Không dán nối nhiều theme với nhau.


## Cách dùng

1. Mở Dashboard và chọn **Edit dashboard**.
2. Chọn menu ba chấm rồi chọn **Edit CSS**.
3. Xóa toàn bộ CSS cũ.
4. Dán nội dung của đúng một file theme.
5. Lưu dashboard và tải lại bằng `Ctrl + F5`.

## Điều chỉnh nhanh

Các màu chính được đặt ở đầu mỗi file trong `:root`. Muốn đổi màu mà không ảnh hưởng cấu trúc, chỉ sửa nhóm biến này.

- `--dash-bg`: nền dashboard.
- `--dash-header`: nền header.
- `--card-bg`: nền card.
- `--card-border`: viền card.
- `--primary`: màu tab và điểm nhấn.
- `--metric`: màu KPI.
- `--radius-card`: độ bo góc card.

Tiêu đề chart được điều chỉnh ở nhóm `.editable-title`, `.editable-title--editable` và `.header-title`.

Giá trị KPI được điều chỉnh ở `.superset-legacy-chart-big-number .header-line`; đơn vị nằm ở `.subheader-line`.
# 3. Travel Notes

Sử dụng react native và native android để xây dựng một ứng dụng cho phép người dùng ghi lại những cảnh quan, món ăn khi đi du lịch.

Yêu cầu

1. Note sẽ bao gồm ảnh và mô tả. Có thể sử dụng camera hoặc chọn ảnh từ trong thư viện. Ứng dụng tự động lấy địa điểm thông qua việc sử dụng vị trí của điện thoại, tuy nhiên người dùng có thể sửa vị trí.

2. Ứng dụng giữa các máy có thể đồng bộ dữ liệu thông qua server

### Kỹ thuật

- Sử dụng WorkManager để thực hiện upload, đồng bộ dữ liệu.

- Sử dụng Room || SQLite để lưu trữ dữ liệu trên mobile.
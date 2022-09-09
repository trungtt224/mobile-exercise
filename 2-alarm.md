# 2. Smart Alarm App
Xây dựng app báo thức sử dụng native code Android (Java)

## Yêu cầu

- Khởi tạo báo thức với nhiều loại chuông(ringstone) khác nhau
- Báo thức có thể được update
- Báo thức cũ được lưu trữ lại
- Để Tắt báo thức phải trả 1 câu hỏi bất kì(Có thể set 1 tập câu hỏi có sẵn) gồm 2 đáp án. Nếu trả lời đúng thì mới tắt được báo thức
- Báo thức lại sau 10 phút nếu người dùng chọn Dừng

### Kỹ thuật sử dụng

RingstoneManager, BroastcaseReceiver, Service, SQLite (Room Database)


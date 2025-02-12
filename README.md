# Kaleido-auto-reff
## Cài đặt

1. Sao chép kho lưu trữ:
``` bash
clone git https://github.com/anht3k52/Kaleido-auto-reff.git
cd Kaleido-auto-reff
```

2. Cài đặt phụ thuộc:
``` bash
install npm
```

## Cấu hình

### Thiết lập proxy (Tùy chọn)

Tạo tệp `proxy.txt` trong thư mục gốc của dự án với proxy của bạn ở định dạng sau:

```
http://1.2.3.4:8080
socks4://1.2.3.4:1080
socks5://1.2.3.4:1080
```

Đối với proxy có xác thực:
```
http://user:password@1.2.3.4:8080
socks4://user:password@1.2.3.4:1080
```

Nếu không tìm thấy tệp proxy hoặc tệp trống, bot sẽ sử dụng kết nối trực tiếp.
## Cách sử dụng

1. Khởi động bot:
``` bash
 npm start
```
2. Làm theo lời nhắc:
   - Nhập mã giới thiệu của bạn
   - Nhập số lượng tài khoản để đăng ký

3. Bot sẽ bắt đầu quá trình đăng ký và hiển thị tiến trình trong thời gian thực.

## Đầu ra

Đăng ký thành công được lưu vào `successful_registrations.txt` ở định dạng JSON với thông tin sau:
- Địa chỉ email
- Địa chỉ ví
- Khóa riêng
- Tên người dùng
- Dấu thời gian

## Tính năng chống phát hiện

- Tác nhân người dùng ngẫu nhiên
- Xoay tiêu đề chấp nhận
- Sự chậm trễ ngẫu nhiên giữa các yêu cầu
- Tiêu đề giống trình duyệt
- Tiêu đề DNT (Không theo dõi)
- Tiêu đề kiểm soát bộ đệm
- Tạo email và tên người dùng ngẫu nhiên

## Cài đặt độ trễ

- Độ trễ 2-5 giây trước mỗi yêu cầu
- Độ trễ 5-10 giây giữa các lần đăng ký
- Các biến thể ngẫu nhiên về độ trễ để tránh các mẫu

## Bảo vệ

- Hỗ trợ xác thực proxy
- Xử lý lỗi đối với các yêu cầu không thành công
- Tạo ví an toàn
- Không ghi dữ liệu nhạy cảm ngoại trừ trong tệp đăng ký

## Tuyên bố từ chối trách nhiệm

Bot này chỉ dành cho mục đích giáo dục. Hãy đảm bảo bạn tuân thủ các điều khoản dịch vụ của nền tảng khi sử dụng các công cụ tự động hóa.

## Giấy phép

Dự án này được cấp phép theo Giấy phép MIT - xem tệp GIẤY PHÉP để biết chi tiết.

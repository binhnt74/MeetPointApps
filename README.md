# MeetPoint Apps

Repo này dùng để phát hành file cài đặt của ứng dụng Điểm Hẹn.

Source code chính được lưu tại: https://github.com/binhnt74/MeetPoint

## Tải bản Android

Phiên bản thử mới nhất: `0.1.0`, Android `versionCode 2`.

[Tải MeetPoint.apk](https://raw.githubusercontent.com/binhnt74/MeetPointApps/main/MeetPoint.apk)

Quét mã dưới đây bằng điện thoại Android để tải file cài đặt:

![QR tải MeetPoint.apk](https://quickchart.io/qr?size=260&text=https%3A%2F%2Fraw.githubusercontent.com%2Fbinhnt74%2FMeetPointApps%2Fmain%2FMeetPoint.apk)

Nếu Android hỏi quyền cài app từ trình duyệt/file manager, bật cho phép cài đặt từ nguồn này rồi mở lại file APK.

## Ghi chú bản này

- Thêm thông báo cho tin nhắn chat mới.
- Thêm thông báo cho thư mời mới, cập nhật thư mời, xóa thư mời và pass chủ kèo.
- Cần chạy lại `supabase/schema.sql` trong Supabase SQL Editor để tạo bảng `notification_tokens` trước khi test notification đầy đủ.

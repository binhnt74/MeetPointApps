# MeetPoint Apps

Repo này dùng để phát hành file cài đặt của ứng dụng Điểm Hẹn.

Source code chính được lưu tại: https://github.com/binhnt74/MeetPoint

## Tải bản Android

Phiên bản thử mới nhất: `0.1.0`, Android `versionCode 2`.

[Tải MeetPoint.apk](https://raw.githubusercontent.com/binhnt74/MeetPointApps/main/MeetPoint.apk)

Quét mã dưới đây bằng điện thoại Android để tải file cài đặt:

![QR tải MeetPoint.apk](https://quickchart.io/qr?size=260&text=https%3A%2F%2Fraw.githubusercontent.com%2Fbinhnt74%2FMeetPointApps%2Fmain%2FMeetPoint.apk)

Nếu Android hỏi quyền cài app từ trình duyệt/file manager, bật cho phép cài đặt từ nguồn này rồi mở lại file APK.

## Bản Development

Bản development chỉ dùng khi muốn chạy app cùng dev server trên máy tính.

[Tải MeetPoint-dev.apk](https://github.com/binhnt74/MeetPointApps/releases/download/android-dev-v0.1.0-3/MeetPoint-dev.apk)

Quét mã dưới đây để tải bản development:

![QR tải MeetPoint-dev.apk](https://quickchart.io/qr?size=260&text=https%3A%2F%2Fgithub.com%2Fbinhnt74%2FMeetPointApps%2Freleases%2Fdownload%2Fandroid-dev-v0.1.0-3%2FMeetPoint-dev.apk)

Sau khi cài bản development, chạy trong repo source:

```sh
npm start -- --dev-client
```

Nếu chỉ muốn dùng app để test tính năng như người dùng thật, dùng bản `MeetPoint.apk` ở trên.

## Ghi chú bản này

- Thêm thông báo cho tin nhắn chat mới.
- Thêm thông báo cho thư mời mới, cập nhật thư mời, xóa thư mời và pass chủ kèo.
- Cần chạy lại `supabase/schema.sql` trong Supabase SQL Editor để tạo bảng `notification_tokens` trước khi test notification đầy đủ.

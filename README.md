# MyLauncher

Kho phát hành công khai cho MyLauncher, launcher dành cho màn hình Android trên xe BYD.

Repo này chứa APK đã ký, ghi chú phát hành và metadata cập nhật. Mã nguồn được quản lý trong repo riêng tư; không đưa mã nguồn, khóa ký hoặc thông tin tài khoản vào đây.

## Tải và cài đặt

Tải APK từ [Releases](https://github.com/doanduy/MyLauncher-Release/releases/latest). Cài alpha83 trở lên thủ công lần đầu để chuyển sang kênh cập nhật này. Các bản từ alpha82 trở về trước chưa bật kênh cập nhật công khai.

Sau đó vào phần Giới thiệu của MyLauncher, chọn **Kiểm tra phiên bản mới**, tải bản cập nhật và xác nhận cài đặt. App kiểm tra SHA-256, application ID, versionCode và chứng chỉ ký trước khi mở trình cài đặt Android. Không tự tải hoặc tự cài bản cập nhật.

## Metadata cập nhật

URL: https://github.com/doanduy/MyLauncher-Release/releases/latest/download/update.json

Mỗi release có hai tài sản: `MyLauncher-v<version>.apk` và `update.json`. Metadata gồm `schemaVersion`, `versionCode`, `versionName`, `apkUrl`, `sha256`, `mandatory` và `releaseNotes`. Bản mới dùng versionCode tăng dần và cùng chứng chỉ ký.

Các bản alpha là bản thử nghiệm. Kết quả kiểm tra cục bộ và tình trạng kiểm thử trên xe được ghi trong từng release.
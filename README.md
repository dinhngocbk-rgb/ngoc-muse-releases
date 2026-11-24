# Ngoc Muse tool

## Tải bản mới nhất

Chọn đúng loại máy:

| Máy của bạn | Tải xuống |
| --- | --- |
| Windows 64 bit | [Tải cho Windows](https://github.com/dinhngocbk-rgb/ngoc-muse-releases/releases/latest/download/Ngoc-Muse-tool-Windows-x64.zip) |
| Mac chip M (Apple Silicon) | [Tải cho Mac chip M](https://github.com/dinhngocbk-rgb/ngoc-muse-releases/releases/latest/download/Ngoc-Muse-tool-macOS-Apple-Silicon.zip) |
| Mac dùng chip Intel | [Tải cho Mac Intel](https://github.com/dinhngocbk-rgb/ngoc-muse-releases/releases/latest/download/Ngoc-Muse-tool-macOS-Intel.zip) |

Xem loại chip Mac tại menu Apple > About This Mac (Giới thiệu về máy Mac này).

## Cài đặt

**Windows:** giải nén toàn bộ ZIP, mở `Ngoc Muse tool.exe`. Giữ thư mục `_internal` bên cạnh EXE, không chạy ngay trong ZIP.

**Mac:** giải nén ZIP, kéo `Ngoc Muse tool.app` vào Applications rồi mở. Nếu macOS chặn lần đầu, vào **System Settings > Privacy & Security > Open Anyway** và xác nhận mở ứng dụng vừa tải từ trang này. Gói tải trực tiếp chưa được Apple notarize. Đã kiểm tra trên macOS 15 ở cả chip M và Intel.

Cần **Google Chrome hoặc Microsoft Edge**, key MUSE được cấp và tài khoản Muse của bạn. Gói đã kèm Python, thư viện giao diện và FFmpeg/FFprobe. Trong ZIP có `HUONG_DAN_SU_DUNG.txt`; ZIP Mac có thêm `CAI_DAT_MAC.txt` cạnh ứng dụng.

## Cập nhật

Tool tự kiểm tra bản mới khi mở và chọn gói đúng hệ điều hành. Chờ tác vụ đang chạy hoàn tất, bấm **Cập nhật ngay** khi có thông báo. Tool kiểm tra chữ ký và SHA-256 trước khi thay ứng dụng; dữ liệu tài khoản và công việc được giữ trong thư mục dữ liệu riêng.

Từ 0.9.2, tải và giải nén chạy nền; hộp cập nhật hiện riêng bước đang làm sau khi tải xong 100%. Nếu đang dùng 0.9.0/0.9.1 và gặp đứng ở 100%, tải ZIP mới tại đây, đóng tool cũ và giải nén đầy đủ để chuyển sang bản mới. Giữ nguyên thư mục dữ liệu riêng.

Từ 0.9.4, bộ cài Windows xác nhận đã khởi động trước khi tool đóng và có log nếu không chạy được. Nếu bản cũ đóng sau 100% nhưng mở lại vẫn là phiên bản cũ, tải ZIP mới và giải nén đầy đủ một lần.

## Khi tạo video lỗi

Danh sách chỉ báo ngắn, ví dụ “Không tạo được video — lỗi 503, dịch vụ quá tải.” Bấm **Chi tiết / Prompt** để xem phản hồi Muse và lịch sử thử lại. Lỗi 500/503 của dịch vụ có thể thử lại trong giới hạn đã đặt; nếu chưa rõ Muse đã nhận prompt, cần kiểm tra hội thoại trước khi gửi lại. Tool không khóa tài khoản chỉ vì lỗi quá tải.

[Xem tất cả phiên bản và ghi chú](https://github.com/dinhngocbk-rgb/ngoc-muse-releases/releases).

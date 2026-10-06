# Mouse Hub

[English](#english) · [Tiếng Việt](#tiếng-việt)

## English

Mouse Hub is a macOS utility that makes any mouse feel right: smooth scrolling, custom buttons and gestures.

### Download

Get the latest `MouseHub-<version>.dmg` from the [Releases page](https://github.com/anhtran110501/MouseHub-releases/releases/latest).

### Install

Open the DMG and drag **Mouse Hub** onto the **Applications** folder.

### First open

Mouse Hub isn't notarized by Apple, so macOS (15 and later, including macOS 27) asks you to confirm it once:

1. Open Mouse Hub from Applications. macOS says Apple could not verify that Mouse Hub is free of malware. Click **Done**. Never click **Move to Trash**.
2. Within about an hour, open **System Settings → Privacy & Security**, scroll down, and click **Open Anyway** next to the message about Mouse Hub.
3. macOS asks once more: click **Open Anyway** again, then enter your password or use Touch ID.

_A screenshot of these steps will be added here._

### If Mouse Hub doesn't open

If nothing appears after the steps above (the icon bounces or nothing happens), do this once:

1. Quit Mouse Hub if it's running: Apple menu → **Force Quit…** → Mouse Hub.
2. Open **Terminal** and run:

   ```
   xattr -cr "/Applications/Mouse Hub.app"
   ```

3. Open Mouse Hub from Applications again. If it still hangs, restart the Mac and try once more.

Updates installed by Mouse Hub itself never need this again.

### Permissions

Mouse Hub shows cards for **Accessibility** and **Input Monitoring**. Click each card's button, turn on **MouseHubHelper** in the list that opens, then come back to Mouse Hub.

### Updates

Mouse Hub checks for updates once a day and asks before installing one. You can also check any time with **Mouse Hub → Check for Updates…**.

### Uninstall

Turn Mouse Hub off in the app, then delete it from the Applications folder. To remove your settings too, delete the folder `~/Library/Application Support/Mouse Hub` (in Finder, choose **Go → Go to Folder…** and paste that path).

## Tiếng Việt

Mouse Hub là tiện ích macOS giúp chuột nào dùng cũng sướng tay: cuộn mượt, tuỳ chỉnh nút bấm và cử chỉ.

### Tải về

Tải file `MouseHub-<phiên bản>.dmg` mới nhất ở [trang Releases](https://github.com/anhtran110501/MouseHub-releases/releases/latest).

### Cài đặt

Mở file DMG rồi kéo **Mouse Hub** thả vào thư mục **Applications**.

### Mở lần đầu

Mouse Hub chưa được Apple công chứng (notarize), nên macOS (từ bản 15 trở lên, kể cả macOS 27) sẽ bắt bạn xác nhận một lần:

1. Mở Mouse Hub trong Applications. macOS báo Apple không thể xác minh Mouse Hub không chứa phần mềm độc hại. Bấm **Done** (Xong). Tuyệt đối đừng bấm **Move to Trash** (Chuyển vào Thùng rác).
2. Trong vòng khoảng một tiếng, vào **System Settings → Privacy & Security** (Cài đặt hệ thống → Quyền riêng tư & Bảo mật), cuộn xuống dưới và bấm **Open Anyway** (Vẫn mở) cạnh dòng thông báo về Mouse Hub.
3. macOS hỏi lại một lần nữa: bấm **Open Anyway** (Vẫn mở) lần nữa, rồi nhập mật khẩu máy hoặc dùng Touch ID.

_Ảnh chụp màn hình các bước này sẽ được bổ sung sau._

### Nếu Mouse Hub không mở được

Nếu đã làm các bước trên mà vẫn không thấy gì (biểu tượng nảy lên rồi thôi, hoặc không có phản ứng), làm một lần như sau:

1. Nếu Mouse Hub đang chạy thì thoát hẳn: menu Apple → **Force Quit…** (Buộc thoát) → Mouse Hub.
2. Mở **Terminal** và chạy:

   ```
   xattr -cr "/Applications/Mouse Hub.app"
   ```

3. Mở lại Mouse Hub trong Applications. Nếu vẫn kẹt, khởi động lại máy rồi thử thêm một lần.

Các bản cập nhật do Mouse Hub tự cài sau này không cần làm lại bước này.

### Cấp quyền

Mouse Hub hiện hai thẻ **Accessibility** (Trợ năng) và **Input Monitoring** (Giám sát đầu vào). Bấm nút trên từng thẻ, bật **MouseHubHelper** trong danh sách hiện ra, rồi quay lại Mouse Hub.

### Cập nhật

Mỗi ngày Mouse Hub tự kiểm tra bản mới một lần và sẽ hỏi bạn trước khi cài. Bạn cũng có thể tự kiểm tra bất cứ lúc nào qua **Mouse Hub → Check for Updates…**.

### Gỡ cài đặt

Tắt Mouse Hub trong ứng dụng, rồi xoá nó khỏi thư mục Applications. Muốn xoá luôn phần cài đặt của bạn, hãy xoá thư mục `~/Library/Application Support/Mouse Hub` (trong Finder, chọn **Go → Go to Folder…** (Đi → Đi tới thư mục…) rồi dán đường dẫn đó vào).

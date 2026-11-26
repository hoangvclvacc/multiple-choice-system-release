# Hệ thống luyện tập trắc nghiệm dành cho các bạn sinh viên luyện tập đang học tại VAU được làm ra bởi D.Hoang

Phần mềm luyện tập và làm bài trắc nghiệm trên Windows, **miễn phí**, làm ra để hỗ trợ mọi người ôn tập.
Không cần tài khoản, không cần máy chủ, **chạy được khi không có mạng**.

## ⬇️ Tải về

👉 **[Tải bản mới nhất](https://github.com/hoangvclvacc/multiple-choice-system-release/releases/latest)**: ở mục *Assets*, tải file
`HeThongLuyenTapTracNghiem-Setup-x.y.z.exe`.

> ⚠️ Chỉ tải từ trang này. Bản do người khác gửi lại có thể đã bị sửa.

**Yêu cầu:** Windows 10 hoặc Windows 11 (64-bit).

## 🛠️ Cài đặt

1. Bấm đúp file `HeThongLuyenTapTracNghiem-Setup-x.y.z.exe` vừa tải.
2. Nếu Windows hiện màn hình xanh **"Windows protected your PC"**: bấm **More info** rồi **Run anyway**.
   *Lý do: phần mềm làm miễn phí nên chưa mua chữ ký số (code signing). Đây không phải virus.*
3. Chọn thư mục cài (hoặc để mặc định), bấm **Install**. Cài xong có biểu tượng ngoài màn hình Desktop.

**Cập nhật:** phần mềm tự kiểm tra bản mới khi có mạng. Có bản mới sẽ hiện thanh **Cài đặt ngay** ở trang chủ.
Muốn kiểm tra ngay thì bấm nút làm mới cạnh số phiên bản (góc trên bên phải).

**Gỡ cài đặt:** Settings → Apps → *Hệ thống luyện tập trắc nghiệm* → Uninstall.

## ✨ Tính năng chính

**Người làm bài**
- Mở file đề `.dethi` (bấm đúp, kéo thả, hoặc nút *Mở file đề*), làm bài giao diện giống Moodle.
- **Luyện tập:** chọn đáp án là biết đúng/sai ngay, có lời giải, luyện lại các câu sai.
- **Flashcard:** ôn bằng thẻ, lật xem đáp án, đánh dấu đã thuộc/chưa thuộc, lọc theo chương.
- **Thi:** đồng hồ đếm ngược, đặt cờ câu cần xem lại, tự nộp khi hết giờ, kết quả tự lưu vào `Tài liệu\KetQuaThi`.
- Mất điện hay lỡ tắt máy vẫn làm tiếp đúng chỗ cũ.
- **Thống kê của tôi:** điểm và tiến bộ qua các lần làm.
- Giao diện **Sáng / Tối / Theo Windows** (màn hình làm bài luôn nền sáng cho dễ đọc).

**Người ra đề** (thẻ *Tạo đề*, có thể đặt mã PIN)
- Nhập câu hỏi từ **file Word** (hoặc gõ/dán dạng chữ): đáp án gạch chân / tô đỏ / dòng `Đáp án: X`, lời giải, bảng, hình, công thức, câu hỏi chùm.
- **Chia chương** và **ma trận đề** (bốc số câu theo từng chương).
- Xuất file đề `.dethi`: chế độ Luyện tập hoặc Thi; thời gian, số câu, số câu mỗi trang, trộn câu và phương án.
- **Đề thi bắt buộc mật khẩu**: đề được mã hóa bằng chính mật khẩu đó.
- **Khóa màn hình khi thi**: chặn thoát ra, chặn chụp/chia sẻ màn hình; không cho thi khi đang mở phần mềm điều khiển từ xa, quay màn hình, trình duyệt, màn hình phụ hoặc máy ảo.
- **Sửa đề đã gửi** (thẻ *Đề thi* ở trang chủ): sửa câu hỏi, đáp án, cấu hình rồi lưu thẳng vào file; ai đang làm dở vẫn làm tiếp được.
- Thu kết quả, tự chấm lại, phát hiện file kết quả bị sửa, cảnh báo nhiều người nộp từ cùng một máy, xuất Excel.

Hướng dẫn chi tiết có ngay trong phần mềm: thẻ **Hướng dẫn sử dụng** ở trang chủ (xem được khi không có mạng).

## 🔒 Dữ liệu và quyền riêng tư

- Phần mềm **không thu thập, không gửi dữ liệu** của bạn đi đâu. Mọi thứ nằm trên máy bạn.
- Mạng chỉ dùng để kiểm tra và tải bản cập nhật từ trang này.
- Dữ liệu phần mềm: `%APPDATA%\ThiTracNghiem`. Kết quả bài thi: `Tài liệu\KetQuaThi`.

## ❓ Câu hỏi thường gặp

**Phần mềm diệt virus báo nguy hiểm?**
Do phần mềm chưa có chữ ký số nên đôi khi bị nghi nhầm. Chỉ cài bản tải từ trang này.

**Quên mã PIN của công cụ tạo đề?**
Tắt phần mềm, dán `%APPDATA%\ThiTracNghiem` vào thanh địa chỉ của File Explorer, xóa file `pin.json` rồi mở lại. Dữ liệu không mất.

**Đề luyện tập có bảo mật đáp án không?**
Đề luyện tập được mã hóa, người bình thường không xem được đáp án, nhưng người rành lập trình vẫn có thể moi ra.
Với bài thi quan trọng, hãy đặt mật khẩu đề và coi thi trực tiếp.

---

Phần mềm làm ra để hỗ trợ học tập, phát hành miễn phí. Góp ý và báo lỗi: liên hệ người phát hành.

WEBSITE TỐT NGHIỆP 2026 — ĐINH QUỐC DUY

Trong gói có:
- index.html: website cá nhân, thiết kế cinematic tối, responsive.
- assets/: nơi đặt ảnh và nhạc của bạn.

CÁCH THAY ẢNH:
1. Chuẩn bị ảnh chân dung và ảnh album.
2. Đổi tên ảnh đúng như sau rồi chép vào thư mục assets:
   portrait.jpg       (ảnh chân dung)
   graduate-01.jpg    (ảnh tốt nghiệp lớn)
   memory-02.jpg      (ảnh kỷ niệm 2)
   memory-03.jpg      (ảnh kỷ niệm 3)
3. Mở index.html bằng Notepad hoặc trình soạn thảo văn bản.
4. Tìm đoạn "Ảnh chân dung của bạn" và thay khối placeholder bằng:
   <img src="assets/portrait.jpg" alt="Đinh Quốc Duy">
   Để làm nhanh hơn, có thể gửi ảnh cho ChatGPT để cập nhật giúp bạn.
5. Trong các khung album, thay nội dung placeholder bằng thẻ img tương ứng, ví dụ:
   <img src="assets/graduate-01.jpg" alt="Ảnh tốt nghiệp">
   và giữ nguyên phần span có class="photo-label" nếu muốn giữ nhãn ảnh.

CÁCH THÊM NHẠC:
- Chép một tệp MP3 mà bạn có quyền sử dụng vào assets/ và đặt tên music.mp3.
- Người xem cần bấm nút "BẬT NHẠC NỀN" để phát; trình duyệt thường chặn tự phát nhạc.

XUẤT BẢN MIỄN PHÍ:
1. Đăng nhập Vercel tại https://vercel.com/
2. Dùng cách triển khai phù hợp với tài khoản Vercel hiện tại. Với dự án HTML tĩnh, có thể import dự án từ GitHub hoặc dùng phương thức upload được Vercel hỗ trợ.
3. Nếu dùng GitHub: tạo repository mới, upload toàn bộ nội dung trong thư mục này (index.html và assets), sau đó trong Vercel chọn Add New > Project và import repository.
4. Framework Preset chọn Other nếu được hỏi; Build Command để trống; Output Directory chọn ./ nếu giao diện yêu cầu.
5. Nhấn Deploy. Khi hoàn tất, Vercel cấp một URL dạng ten-du-an.vercel.app.

LƯU Ý:
- Đây là bản website cá nhân hóa từ đầu theo thông tin bạn cung cấp, không phải bản sao mã nguồn website tham khảo.
- Ảnh và nhạc phải được đưa vào thư mục assets trước khi triển khai để khách truy cập đều xem/nghe được.
- Chỉ đăng ảnh, nhạc và nội dung mà bạn có quyền chia sẻ công khai.
- Không đưa dữ liệu cá nhân nhạy cảm lên website công khai.

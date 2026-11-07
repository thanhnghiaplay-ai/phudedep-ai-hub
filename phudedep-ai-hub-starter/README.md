# phudedep-ai-hub

Bộ trung tâm bộ nhớ và phối hợp nhiều AI cho dự án `phudedep`.

## Mục tiêu
- AI nào cũng đọc cùng một trạng thái dự án đã được lưu.
- Mọi công việc có mã Task ID, trạng thái, người/AI phụ trách và checkpoint.
- Khi một AI bị ngắt, AI khác tiếp quản từ dữ liệu đã xác minh.
- Không AI nào tự ý đưa thay đổi quan trọng vào `main`.

## Bắt đầu nhanh trên điện thoại
1. Tải và giải nén ZIP này.
2. Mở https://github.com/new và tạo repository tên `phudedep-ai-hub`.
3. Chọn **Public** chỉ cho tài liệu không bí mật; tạo README nếu GitHub hỏi thì có thể bỏ qua.
4. Trong repository, chọn **Add file → Upload files**, tải toàn bộ nội dung bên trong thư mục này lên (giữ nguyên cấu trúc thư mục), rồi **Commit changes**.
5. Vào **Settings → General → Features**, bật **Discussions** nếu mục này có sẵn.
6. Tạo các Discussion category theo `02_COLLABORATION/GITHUB_SETUP.md`.
7. Mở `START_HERE.md`, thay các mục `[CẦN ĐIỀN]` bằng thông tin thật của dự án.
8. Gửi `00_SYSTEM/AI_JOIN_PROMPT.md` cho từng AI.

## Lưu ý quan trọng
- Repository Public: bất kỳ ai cũng có thể đọc và sao chép nội dung. Không tải lên mã nguồn độc quyền, dữ liệu khách hàng, thông tin cá nhân, API key, token, mật khẩu hoặc file `.env`.
- Nếu cần lưu code thật của sản phẩm, nên dùng repository **Private** riêng; hub public chỉ chứa tài liệu đã làm sạch.
- GitHub không tự làm các model AI nói chuyện với nhau. Mỗi AI phải được bạn cấp quyền truy cập GitHub, hoặc bạn đưa tài liệu cho AI và tải báo cáo của nó lên.
- Không đưa quyền ghi repository cho AI/ứng dụng nếu chưa hiểu rõ quyền đó.
- `main` là nhánh chuẩn. AI làm việc trên nhánh riêng và đề xuất Pull Request; chủ dự án duyệt và merge.

## Trạng thái hiện tại
Bộ khung mới được tạo. Chưa kết nối tài khoản GitHub, chưa tạo repository và chưa có AI nào được cấp quyền.

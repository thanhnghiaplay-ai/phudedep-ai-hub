# Thiết lập GitHub trên điện thoại

## Tạo repository
1. Mở https://github.com/new và đăng nhập.
2. Repository name: `phudedep-ai-hub`.
3. Description: `Shared memory and collaboration hub for phudedep AI agents`.
4. Chọn Public chỉ khi nội dung đã được làm sạch, không chứa bí mật.
5. Có thể bỏ chọn Add a README vì bộ khung đã có README.
6. Nhấn Create repository.

## Tải bộ khung
1. Mở repository mới.
2. Chọn Add file → Upload files.
3. Chọn tất cả file/thư mục đã giải nén; nếu điện thoại không cho chọn thư mục, tải ZIP lên không tự bung thành cấu trúc. Khi đó dùng trình duyệt chế độ desktop hoặc tải từng file qua Add file → Create new file.
4. Kiểm tra `START_HERE.md` nằm ở thư mục gốc.
5. Commit changes.

## Bật Discussions
1. Vào Settings → General → Features.
2. Bật Discussions nếu tùy chọn xuất hiện.
3. Vào tab Discussions và tạo các category:
   - General (General)
   - AI-Reports (Announcements hoặc General)
   - Architecture (General)
   - Code-Review (General)
   - Bug-Reports (Q&A hoặc General)
   - Decisions (Announcements)
   - Handover (General)

## Bảo vệ main
Trong Settings → Branches, thêm branch protection rule cho `main`:
- Require a pull request before merging.
- Nếu chỉ có một mình bạn và cần tự duyệt, đừng bật yêu cầu review approval bắt buộc.
- Không bật force pushes.
GitHub Free hỗ trợ protected branches cho public repositories. Kiểm tra giao diện và quyền tài khoản thực tế trước khi lưu.

## Lưu ý
Discussions không tự làm AI phản hồi. AI cần có quyền truy cập thông qua connector/API phù hợp hoặc bạn copy tài liệu vào chat. Không chia sẻ token trong Discussion.

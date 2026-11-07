# Hướng dẫn phục hồi khi AI bị ngắt

1. Mở `TASK_BOARD.md` và xác định task `IN_PROGRESS` hoặc quá hạn checkpoint.
2. Mở `HANDOVER.md`, `AI_ACTIVITY_LOG.md`, `CHECKPOINTS.md`.
3. Kiểm tra repository: branch, commit gần nhất, Pull Request, file thay đổi và diff.
4. Phân loại:
   - VERIFIED_DONE: đã có thay đổi và đã kiểm tra.
   - SAVED_UNTESTED: code đã lưu nhưng chưa test.
   - UNCOMMITTED: file thay đổi chưa commit.
   - CHAT_ONLY: chỉ có trong hội thoại; không thể coi là đã lưu.
   - UNKNOWN: không đủ dữ liệu.
5. AI tiếp quản phải báo cáo kiểm kê trước khi sửa.
6. Tạo branch mới từ trạng thái đã xác minh; không xóa branch cũ.
7. Tiếp tục phần còn thiếu; chạy test phù hợp.
8. Cập nhật checkpoint và handover.

## PROMPT tiếp quản khẩn cấp
Bạn đang tiếp quản task của một AI bị ngắt. Đọc START_HERE, AI_RULES, CURRENT_STATE, TASK_BOARD, AI_ACTIVITY_LOG, HANDOVER và CHECKPOINTS. Kiểm tra repository/branch/commit/diff thật. Phân loại phần hoàn tất, dang dở, chưa lưu, chưa test và không thể khôi phục. Không tin báo cáo trước nếu không có bằng chứng. Không viết lại phần đã hoàn tất nếu không cần. Không sửa main. Trước tiên hãy xuất báo cáo kiểm kê và kế hoạch tiếp tục; chỉ sửa sau khi chủ dự án duyệt nếu thay đổi có rủi ro hoặc phạm vi lớn. Không bịa dữ liệu thiếu.

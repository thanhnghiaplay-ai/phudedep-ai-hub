# Checkpoints

| Checkpoint | Task ID | UTC time | Commit | Trạng thái | Ghi chú |
|---|---|---|---|---|---|
| CP-0000 | NONE | 2026-11-07 | NONE | INITIAL | Khởi tạo bộ khung, chưa có code dự án |

## Quy tắc checkpoint
- Tạo checkpoint trước thay đổi lớn.
- Tạo checkpoint sau mỗi chặng có thể kiểm tra được.
- Ghi commit hash thật nếu có; nếu chưa commit ghi `UNCOMMITTED`.
- Không ghi `DONE` nếu chưa test.
- Lưu cả trạng thái dang dở, không chỉ kết quả cuối.

# Chính sách quyền

## Mức quyền
- READ: chỉ đọc tài liệu/code.
- PROPOSE: viết đề xuất/bản vá để chủ dự án áp dụng.
- WRITE_BRANCH: tạo/sửa nhánh riêng và mở PR.
- MERGE: chỉ chủ dự án hoặc người được chủ dự án chỉ định.

## Quy tắc
- Không cấp quyền Admin cho AI chỉ để tiện thao tác.
- Không bật workflow có quyền ghi nếu chưa xem nội dung workflow.
- Workflow chỉ cần đọc phải dùng `permissions: contents: read`.
- Không cho phép tự động merge, tự động xóa branch hoặc tự sửa `main`.
- Mọi thay đổi về bảo mật, thanh toán, dữ liệu người dùng, xác thực, quyền truy cập và triển khai production cần chủ dự án duyệt.

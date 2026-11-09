## Công thức Prompt 3 Thành phần để nhờ AI giải thích lỗi:

- **Context**: Dùng Windows 11, cần đẩy code lên GitHub kịp deadline. Chạy lệnh Git thì bị lỗi, chạy lại nhiều lần vẫn không được.

- **Raw Error**: error: open(".git/FETCH_HEAD"): Permission denied.

- **Instruction**: Giải thích lỗi bằng ngôn ngữ bình dân cho người mới học, rồi hướng dẫn sửa từng bước và nói rõ mỗi lệnh làm gì.

## Chạy bằng Run as Administrator và chụp ảnh:

- Đóng Terminal cũ, bấm Start, gõ PowerShell, chọn chuột phải chọn Run as administrator, bấm Yes.

- Dùng cd vào thư mục project, chạy lại lệnh Git bị lỗi.

- Chụp ảnh màn hình thật khi thực hiện: thấy rõ chữ Administrator trên thanh tiêu đề, dòng lệnh và kết quả bên dưới.

## Tin nhắn nhờ giảng viên

- **Context**: Máy em hệ Windows 11, dùng PowerShell, đang đẩy code lên GitHub để kịp deadline. Đã chạy lại lệnh và thử mở Terminal bằng quyền Administrator nhưng vẫn lỗi.

- **Expected**: Lệnh Git chạy thành công, code lên GitHub.

- **Actual**: Terminal báo lỗi và dừng, code chưa được đẩy lên.

- **Log & Screenshot**: error: open(".git/FETCH_HEAD"): Permission denied (kèm ảnh đã khoanh vùng lỗi và che thông tin cá nhân).
# hello-oss-doc
Một dự án mẫu đơn giản viết bằng ngôn ngữ C nhằm mục đích làm quen với quy trình làm việc trong môi trường mã nguồn mở (Open Source Software - OSS).

## Mục tiêu của dự án
- **Học tập & Thực hành:** Giúp sinh viên và người mới bắt đầu tiếp cận cách quản lý mã nguồn bằng Git và GitHub.
- **Chuẩn hóa tài liệu:** Thực hành viết tài liệu kỹ thuật cơ bản cho dự án phần mềm (`README.md` và `CONTRIBUTING.md`).
- **Làm quen quy trình đóng góp:** Hiểu rõ các bước báo lỗi, tạo nhánh và gửi Pull Request.

## Hướng dẫn build và chạy chương trình

### Yêu cầu hệ thống
Máy tính của bạn cần cài đặt sẵn trình biên dịch C (như `gcc` hoặc `clang`).

### Các bước thực hiện

1. **Tải mã nguồn về máy (Clone):**
   ```bash
   git clone https://github.com/khanglehuynhofficial/hello-oss-doc.git
   cd hello-oss-doc
   ```

2. **Biên dịch chương trình (Build):**
   Sử dụng lệnh sau để biên dịch file `main.c` thành file chạy `hello`:
   ```bash
   gcc main.c -o hello
   ```

3. **Chạy chương trình:**
   - Trên Linux/macOS:
     ```bash
     ./hello
     ```
   - Trên Windows (Command Prompt / PowerShell):
     ```bash
     hello.exe
     ```

   **Kết quả kỳ vọng:**
   ```text
   Hello OSS
   ```


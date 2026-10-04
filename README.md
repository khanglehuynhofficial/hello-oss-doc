# hello-oss-doc
Một dự án mẫu viết bằng C nhằm mục đích làm quen với quy trình mã nguồn mở (OSS).

## 1. Giới thiệu ngắn gọn về dự án
Mô phỏng cấu trúc quản lý mã nguồn với `.gitignore`, `CONTRIBUTING.md`, và `LICENSE`.

## 2. Mục tiêu của dự án
* Học tập & thực hành Git/GitHub.
* Chuẩn hóa tài liệu kỹ thuật.
* Làm quen quy trình đóng góp (Pull Request).

## 3. Hướng dẫn build và chạy chương trình
Cần cài đặt `gcc` hoặc `clang`.

* **Bước 3.1: Khởi tạo mã nguồn `main.c`**
```bash
cat << 'EOF' > main.c
#include <stdio.h>
int main() { printf("Hello OSS\n"); return 0; }
EOF
```
* **Bước 3.2: Biên dịch:** `gcc main.c -o hello`
* **Bước 3.3: Chạy chương trình:** `./hello` (Linux/macOS) hoặc `hello.exe` (Windows).

*Dự án phục vụ bài tập thực hành CI/CD.*
EOF

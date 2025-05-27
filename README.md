# m3 Hello

# Thêm .gitignore
🧠 Cheat Sheet VIM cơ bản – dành cho người mới học
📍 Dùng tốt trong Terminal macOS, Git Bash, hoặc RStudio Terminal

🚀 PHẦN 1: Cách mở và thoát Vim
Lệnh	Ý nghĩa
vim tenfile.sh	Mở hoặc tạo file mới
i	Vào chế độ soạn thảo (Insert mode)
Esc	Thoát khỏi chế độ soạn thảo
:w	Lưu file
:q	Thoát nếu không có thay đổi
:wq hoặc ZZ	Lưu và thoát
:q!	Thoát không lưu

✍️ PHẦN 2: Soạn thảo văn bản
Lệnh	Ý nghĩa
i	Chèn trước con trỏ (-- INSERT --)
a	Chèn sau con trỏ
o	Mở dòng mới bên dưới
O	Mở dòng mới bên trên

🔁 PHẦN 3: Di chuyển con trỏ
Phím	Di chuyển
h	Trái
l	Phải
j	Xuống
k	Lên
0	Đầu dòng
$	Cuối dòng
gg	Đầu file
G	Cuối file

✂️ PHẦN 4: Cắt – Dán – Hoàn tác
Lệnh	Ý nghĩa
dd	Xoá dòng
yy	Sao chép dòng
p	Dán sau con trỏ
P	Dán trước con trỏ
u	Hoàn tác
Ctrl + r	Làm lại thao tác hoàn tác

🔍 PHẦN 5: Tìm kiếm & thay thế
Lệnh	Ý nghĩa
/chuỗi + Enter	Tìm từ khóa phía trước
n	Tìm tiếp
N	Tìm ngược lại
:%s/old/new/g	Thay tất cả old thành new

🛠 PHẦN 6: Ví dụ đầy đủ
🔧 Soạn file script hello.sh:
bash
Copy code
vim hello.sh
Nhấn i và gõ:

bash
Copy code
#!/bin/bash
echo "Xin chào từ Vim! 🚀"
Nhấn Esc, gõ :wq → Enter để lưu và thoát.

▶️ Chạy:
bash
Copy code
chmod +x hello.sh
./hello.sh
📄 PHẦN 7: Mẹo bổ sung
:set number → Hiện số dòng

:set paste → Dán nội dung từ clipboard không lỗi

:help → Xem trợ giúp trong Vim

:!ls → Chạy lệnh terminal ngay trong Vim


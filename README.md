\*\*\*Các bước để clone, add, commit, push git

1. Clone the repository: $ git clone <url>
   //example: $git clone https://github.com/khoalyRikkei/JV-V1.1_Training_Program_Preparation.git

2. Cd vào thư mục đã clone: $ git cd <tên thư mục>
   // example: $ git cd JV-V1.1_Training_Program_Preparation

3. Thực hiện tạo git: $git init

4. Code trong thư mục...

5. Thêm tất cả thay đổi để commit: $git add .

6. Commit thay đổi sẵn sàng đưa lên repo: $git commit -m "<đặt tên commit>"
   // example: $git commit -m "Updated readme.md"

7. Đưa code lên repo: $git push

\*\*\* Các bước để tạo dự án sau đó push lên repo có sẵn:

1. Vào thư mục dự án

2. Tạo git: $git init

3. Tạo liên kết với repo: $git remote add origin <url>
   // example: $git remote add origin https://github.com/khoalyRikkei/JV-V1.1_Training_Program_Preparation.git

4. Thêm tất cả thay đổi: $git add .

5. Commit thay đổi sẵn sàng đưa lên repo: $git commit -m "<đặt tên commit>"
   // example: $git commit -m "Updated readme.md"

6. Đưa commit lên repo: $git push origin master // sẽ đưa lên branch có tên là master

5.1 Nếu muốn tạo branch mới, có thể dùng: $git checkout -b <tên branch>
// example: $git checkout -b version_1
5.2 Đưa code lên với branch mới: $git push --set-upstream origin <tên branch vừa tạo>
// example: $git push --set-upstream origin version_1

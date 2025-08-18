# git config

## git config --global user.name "user name"

## git config --global user.email "user email"

## git config --list (dùng để kiểm tra các git config) => nhấn Q để thoát

# Khởi tạo local repository

## git init

=> tạo local repository với nhánh chính master

## git init -b main

=> tạo ra local repository với nhánh chính là main

## Tạo remote repository => lên github tạo repository

=> khi tạo remote repository nhánh chính sẽ là nhánh main (github, gitlab)

## git status (dùng để kiểm tra sự thay đổi của các file ở trong thư mục)

## git add . ( dùng để thêm những file đã thay đổi vào trong staging area)

=> những file nằm trong những staging area thông qua lên git add mới có thể được đưa lên remote repository

## git rm --cached <tên file> (dùng để đưa file từ staging area => về lại working)

## git commit -m "message" (dùng để commit nội dung cho những file đang ở staging)

# Tạo SSH keys

## ssh-keygen -t -ed255919 -C "abc@gmail.com

## lấy đường dẫn nơi lưu trữ ssh key

## cat <đường dẫn file .pub>

## copy nội dung được hiển thi ra và add vào trong tài khoản github

## git remote add origin <đường dẫn remote repository (SSH)> (chỉ cần chạy 1 lần)

## git push -u origin main (dùng để đẩy code từ local repository lên remote repository)

=> -u origin : chỉ cần sử dụng ở lần git push đầu tiên => ở lần thứ 2 chỉ cần gõ git push

## git clone (dùng để clone 1 source code từ remote repository về máy)

## git pull (dùng để lấy code mới nhất từ remote repository)

## git branch

## git merge

git checkout <=> git switch

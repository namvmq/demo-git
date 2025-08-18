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

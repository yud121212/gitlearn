#GIT và GITHUB
  Git là một hệ thống quản lý phiên bản (VCS), một loại VCS phân tán chạy nhanh, ổn định, dễ sử dụng. Git là mã nguồn mở, có thể cài đặt và sử dụng trên nhiều nền tảng.
  Các lệnh Git
  git config –global user.name newname: đổi tên người dùng
git config –global user.email newemail@domain.com: đổi email
git init : khởi tạo một local repository mới
git init –bare: khởi tạo một Remote Repository mới ở git server
Làm việc với Local Repo
git status : trạng thái của Repo
git status –s: trang thái của Repo ngắn gọn
git clone path: sao chép một repositorycory có địa chỉ là path
git add: cập nhập vào staged
git add filename: thêm file vào staged
git add *.c file có phần mở rộng là .c
git add –A thêm mọi thứ có sự thay đổi
git add . thêm mọi thứ trừ loại xóa file
git add – thêm mọi thứ trừ file mới
git commit –m “mess”: commit mới
git commit –amend –m “thông báo” : commit + cập nhập vào commit cuối.
git log: lịch sử commit
git diff: xem sự khác biệc giữ thư mục làm việc là staged
git rm filename: xóa file
git reset HEAD filename: hủy thay đổi của file
git checkout – filename: khôi phục thay đổi của file
Làm việc với Remote Repo
git remote: xem các remote
git remote –v: xem các remote
git remote add name_remote addr_remote: thêm một remote vào local
git fetch name_remote: cập nhập local repo từ remote repo
git pull name_remote name_branch : cập nhập local repo từ remote repo

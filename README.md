

/**
Đối với người tạo project/repo:

B0: Tạo acc trên GitHub (tạo repo để lấy link cho B6)

B1: Tải Git về

B2: Check the version of git: git --version

B3: Set up trên terminal:
git config --global user.name "Dev name"    (thay dev name bằng tên acc github)
git config --global user.email "Dev email"    (thay dev email bằng tên email liên kết vs git đó)

B4: cd ten-thu-muc (bắt buộc phải change directory về chỗ cần upload lên git)

B5: git init      (tại đường dẫn đó khởi tạo git)

B6: Thêm link repo:
git remote add origin https://github.com/username/repo-name.git
( chỗ username thay = acc github; repo name là cái tên project tạo trên git)

B7: Check trạng thái file mình upload trên git:
git add tên_tệp
(nếu muốn up lên hết thì thay = " git add .  " )

B8: git commit -m "Mô tả thay đổi"
( thay đổi gì thì vắn tắt nội dung ở đây )

B9: 
git branch -M main
git push -u origin main
( 2 lệnh này để tạo nhánh main, và upcode lên main, sau tạo nhánh phụ nào thì tạo từ main ra)

**/

/**
Đối với thành viên: 

B0: Tạo acc trên GitHub 

B1: Tạo bản sao từ trên GitHub xuống:
git clone https://github.com/username/repo-name.git  
(cái url phải có đuôi .git nhé)

**/

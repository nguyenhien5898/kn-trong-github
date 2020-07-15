- đưa Repo từ Local lên Github: 
   + tạo 1 thư mục, mở thư mục bằng "git bash here"
   + $ git inti
   + $ git config --global user.name "nguyenhien"
   + $ git config --global user.email nguyenhien@gmail.com
   + $ git add * (add tất cả các tệp trong thư mục đã tạo. nếu không thì git add ten_tep)
   + $ git commit -m "tai tep len"  ( $ git commit -m " phần mô tả")
  (trên github: tải fike lên trong mục add file)

- Clone:
  + $ git clone địa chỉ repo

-Fork: chọn biểu tượng fork trên github

-Push: đẩy các thay đổi của mình vào máy chủ
   - $ git push origin master  
-pull: Khi muốn cập nhật các thay đổi từ trên remote server về local repository  
   - $ git pull <tên-remote> <tên-remote-branch> 
   tuy nhiên, khi sử dụng pull thì sẽ cập nhật tất cả các file trên server về local (dư thừa)  
   ta có thể sử dụng fetch, sẽ cập nhật nhữ file mà trên server có những local chưa có   
    - $ git fetch origin  
 -git remote add thêm Remote vào Local  
     - git remote add <remote_name> <url>  

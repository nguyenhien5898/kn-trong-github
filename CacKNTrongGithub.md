__-Repository__( private và public ):là nơi mà tất cả các file liên quan tới project được lưu trữ,  có thể truy cập thông qua URL của nó.  
         + private: cần quyền truy cập  
         + public: ai cũng có thể truy cập được    
-__Fork:__ là thao tác thực hiện sao chép repository của chủ sở hữu khác về git của mình. có thể sử dụng như repository mình tạo ra   
-__Clone:__ được gọi là nhân bản, hay thực hiện nhân bản. Sử dụng để clone các project, repository trên các hệ thống chạy trên cơ sở là git (vd:github).Việc clone này sẽ sao chép repository tại commit mình mong muốn, dùng để tiếp tục phát triển. Thao tác này sẽ tải toàn bộ mã nguồn, dữ liệu về máy tính.  
   git clone /đường-dẫn-đến/repository/  
__-Commit:__ Để ghi lại việc thêm/ thay đổi file hay thư mục vào repository thì sẽ thực hiện thao tác gọi là Commit.  
__-Pull Request:__ có nghĩa là thông báo với những người khác rằng bạn đã đẩy những thay đổi của nhánh lên Repository tổng (master respository). những người khác của repository này có thể chấp nhận hoặc từ chối pull request này. Khi nó được mở ra, bạn có thể thảo luận và xem lại công việc với những người cùng làm khác.  
      _các bước thực hiện:_  
             + Chuyển tới repository và tìm menu branch  
             + Trong branch menu, chọn branch chứa thay đổi của bạn  
             + Nhấn vào nút New pull request bên cạnh menu branch  
             + Thêm tiêu đề và mô tả vào pull request của bạn  
             + Nhấn nút Create pull request  
-__branches:__ Branch là cái dùng để phân nhánh và ghi lại luồng của lịch sử. Branch đã phân nhánh sẽ không ảnh hưởng đến branch khác nên có thể tiến hành nhiều thay đổi đồng thời trong cùng 1 repository.   
        Các thành viên của nhóm sẽ tạo branch dùng riêng cho công việc của mình từ branch chính để không ảnh hưởng đến công việc của các thành viên khác. Sau đó, những thành viên đã hoàn thành công việc của mình sẽ thực hiện đưa thay đổi của mình vào branch chính (Pull Request) . Theo cách như vậy, sẽ không bị ảnh hưởng từ công việc của các thành viên khác, và bản thân mình có thể thực hiện công việc của mình.  
-  __isssue:__ dùng để theo dõi các thông báo, lỗi, các yêu cầu về tính năng...trên github, isssue được tạo ra dưới dạng danh sách có thể tìm kiếm, lọc (trong trường hownpkhi đọc 1 repo, nếu phát hiện lỗi cũng có thể thống báo lại ở đây)  


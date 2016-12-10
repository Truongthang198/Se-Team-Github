...GITHUB...
<ul> ***1.Cách thức hoạt động của Github.*** <li>
Git là một công cụ để quản lý mã nguồn, nhưng tôi không phải là một coder nên tôi sẽ không sử dụng Git theo cách mà các coder hay sử dụng. 
<li> Tôi sử dụng git và github để lưu trữ các file cấu hình của mình, các script, viết các bài hướng dẫn, các bản nháp,... Các repo là những nơi tôi phân loại, lưu trữ những thứ bên trên và nó được lưu cả ở máy trạm và ở server github. Để làm việc với repo thì bạn phải hiểu về nó.

***2.Các khái niệm: Add, Remove, Commit, Push, Pull, Fetch, Clone, Fork, Star, Watch***
<li>Add : soạn thảo thêm mới file đoạn code
<li>Commit : update bản save hiện tại
<li>Push : đẩy file từ máy trạm lên server(Overwrite)
<li>Pull : kéo file từ server về máy trạm(Overwrite)
<li>Fetch :hủy tất cả thay đổi và commit cục bộ, lấy về (fetch) lịch sử gần đây nhất từ máy chủ và trỏ nhánh master cục bộ vào nó
<li>Clone: sao chép một repository
<li>Fork : Lấy repo của người khác về trang cá nhân
<li>Star : Gắn sao , tiện xem lại
<li>Watch : Theo dõi Repo, nhận thông báo

***3.Tìm hiểu các bước để Setting up Git, Generate and add SSH key, Caching -your GitHub password in Git.***

<ul>***a/ Setting up Git (Windows)***
<li>download tại địa chỉ: https://windows.github.com/

<li>Cài đặt bình thường, yêu cầu phải có .NET 4.5

<li>Giao diện của chương trình:

https://camo.githubusercontent.com/58b5fedd92a98e6f20a1d29b6a13e29f23d28edc/687474703a2f2f692e696d6775722e636f6d2f45627836644a442e706e67
<li>Thêm tài khoản Github:

<li>Click vào tool and options (hình bánh răng cạnh biểu tượng Sync) chọn options, Add account. Khai báo username và password trên github
https://camo.githubusercontent.com/7ef261b82227da4e2a1ee29a0988b1fc6745795e/687474703a2f2f692e696d6775722e636f6d2f35494f735776492e706e67

***b/ Generate and add SSH key***

<li>Mở Git Bash

<li>Nhập email của bạn: $ ssh-keygen -t rsa -b 4096 -C"your_email@example.com"

<li>Enter a file in which to save the key (/Users/you/.ssh/id_sra): Press Enter

<li>Nếu nhập passphrase thì nhớ pass

<li>Truy cập vào đường dẫn: https://github.com/settings/ssh

<li>Sau đó đặt tên cho file là Title và dán nội dung vừa copy vào ô Key

<li>Lúc này có thể commit mà không cần username hay password.

***c/ Thao tác với Repo:***
<li>Trên Linux

<li>Tạo mới

<li>Tạo một repo mới trên trang github.com

https://camo.githubusercontent.com/9aa3b64890ea8ff7e8520d6857db5fd71c839319/687474703a2f2f692e696d6775722e636f6d2f616c5246574b6c2e706e67

<li>clone


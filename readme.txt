TH1: Chưa kết nối dự án tới github
B1. Khởi tạo
- git init
B2. đóng gói dữ liệu chuẩn bị gửi lên github -> Đóng kiện hạng chuẩn bị gửi
- git add -A 
B3. Gán nhãn -> Nhãn Đ/c nhận & gửi -> gắn vào kiện hàng
- git commit -m 'init project'
B4. Kết nối dự án máy tính <-> dự án github
- git remote add origin https://github.com/thaydieplaptrinh/pre.git
B5. Đẩy code lên github -> chuyển hàng cho driver -> ship
- git push -u origin master
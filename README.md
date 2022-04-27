

## Cài đặt 
```
bash <(curl -Ls https://raw.githubusercontent.com/Quoctai0209/xrayr/master/install.sh)
```
## Cấu hình xrayr
Sử dụng `nano` hoặc `vi` để vào thư mục cấu hình
```
vi /etc/XrayR/config.yml
```
```
nano /etc/XrayR/config.yml
```
Hoặc gọi xrayr rồi bấm phím `0`

1: dòng `PanelType` : Tên kiểu web (ví dụ `V2board`, `SSpanel`,... chữ đầu viết hoa)

2: dòng `ApiHost` : Địa chỉ web muốn liên kết (ví dụ `https://domain.com/`)

3: dòng `ApiKey` : key của web (lấy trên web admin / cấu hình hệ thống / máy chủ `chìa khóa giao tiếp`)

4: dòng `NodeID` : `ID` server (lấy trên web admin / Quản lý nút / tên `ID nút`)

5: dòng `certdomain` : `IP` của server muốn đưa lên web

Dòng nào có ngoặc kép nhớ để ý viết trong ngoặc kép

Cấu hình xong nhớ khởi động lại xrayr nhé.

Nên sử dụng VPS sạch để cài đặt tránh lỗi vặt 

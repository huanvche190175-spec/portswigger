#LAB03: SQL injection attack, querying the database type and version on Oracle
<img width="1882" height="1307" alt="image" src="https://github.com/user-attachments/assets/6c6f3069-9740-4850-88f3-5800cc2e845e" />

Mục Tiêu: Display the database version string ( hiển thị phiên bản của Database )

Kiểm tra xem query có bao nhiêu cột: 
<img width="613" height="103" alt="image" src="https://github.com/user-attachments/assets/f717e29f-b0c3-40e8-a54e-4405fd615744" />
<img width="594" height="106" alt="image" src="https://github.com/user-attachments/assets/293a5bb2-f7fd-4b57-9e9a-fc2cb0f07e53" />
<img width="582" height="107" alt="image" src="https://github.com/user-attachments/assets/35c5a5c7-132b-43b7-88ec-d1d93d213789" />

--> query chỉ có 2 cột theo dạng: SELECT 1,2 -> Oracle Database

Để hiển thị version của database ta sẽ cần lấy dữ liệu từ cột banner của bảng v$version bằng cách dung UNION để bắt website hiển thị dữ liệu mà không thể hiển thị


<img width="902" height="208" alt="image" src="https://github.com/user-attachments/assets/05b2e813-05a8-412c-adbe-fa0a1010e48d" />

-> Đã biết được version của database

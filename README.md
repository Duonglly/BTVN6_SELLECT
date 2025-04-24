# BTVN6_SELLECT
Chủ đề: Câu lệnh Select
Yêu cầu bài tập: 
Cho file sv_tnut.sql (1.6MB)
1. Hãy nêu các bước để import được dữ liệu trong sv_tnut.sql vào sql server của em
2. dữ liệu đầu vào là tên của sv; sđt; ngày, tháng, năm sinh của sinh viên (của sv đang làm bài tập này)
3. nhập sql để tìm xem có những sv nào trùng hoàn toàn ngày/tháng/năm với em?
4. nhập sql để tìm xem có những sv nào trùng ngày và tháng sinh với em?
5. nhập sql để tìm xem có những sv nào trùng tháng và năm sinh với em?
6. nhập sql để tìm xem có những sv nào trùng tên với em?
7. nhập sql để tìm xem có những sv nào trùng họ và tên đệm với em.
8. nhập sql để tìm xem có những sv nào có sđt sai khác chỉ 1 số so với sđt của em.
9. BẢNG SV CÓ HƠN 9000 ROWS, HÃY LIỆT KÊ TẤT CẢ CÁC SV NGÀNH KMT, SẮP XẾP THEO TÊN VÀ HỌ ĐỆM, KIỂU TIẾNG  VIỆT, GIẢI THÍCH.
10. HÃY NHẬP SQL ĐỂ LIỆT KÊ CÁC SV NỮ NGÀNH KMT CÓ TRONG BẢNG SV (TRÌNH BÀY QUÁ TRÌNH SUY NGHĨ VÀ GIẢI NHỮNG VỨNG MẮC)

DEADLINE: 23H59:59 NGÀY 25/4/2025

Ghi chú: Giải thích tại sao lại có SQL như vậy.
# DEMO CÁC BƯỚC THỰC HIỆN

## Mở file sv_tnut
![Ảnh chụp màn hình 2025-04-24 143926](https://github.com/user-attachments/assets/26a2a9ac-ed84-4674-bcb6-d21470599930)
## Excute để chạy fille sv_tnut
![Ảnh chụp màn hình 2025-04-24 144305](https://github.com/user-attachments/assets/994b8a4d-b4cc-4931-a9ea-c9ff6063d6df)
## Dùng lệnh sellect để truy vấn Sinh viên trùng cả ngày tháng năm sinh với em
![image](https://github.com/user-attachments/assets/f20c4b34-cd42-4de1-8631-cb5dff299a1c)\
## Dùng lệnh sellect để truy vấn Sinh viên trùng ngày và tháng sinh với em
![image](https://github.com/user-attachments/assets/9b537545-4920-4034-8414-ea0b6b67526c)
## Dùng lệnh sellect để truy vấn Sinh viên trùng năm và tháng sinh với em
![image](https://github.com/user-attachments/assets/95811411-1051-410b-acce-f6dddcd65e28)
## Dùng hàm right: kiểm tra phần tên cuối cùng trong chuỗi họ tên, rồi so sánh với "Ly" để đưa ra những người cùng tên với em
![image](https://github.com/user-attachments/assets/d4c7aae3-1d3d-459d-ab26-7355c8b9bd23)
## Dùng hàm left: kiểm tra phần bên trái trong chuỗi họ tên, rồi so sánh với "Dương Thị" để đưa ra những người cùng họ đệm với em
![image](https://github.com/user-attachments/assets/4d9904f4-cd75-4d74-8360-86d3bf489859)
## So sánh từng ký tự một giữa số của bạn (0365395807) và cột SDT trong bảng để truy vấn ra sdt giống của em
![image](https://github.com/user-attachments/assets/6fe65e98-ad13-4a8f-ad8e-8dc78d612d92)
## Truy vấn và sắp xếp những sinh viên kMT, like:là một toán tử để so sánh chuỗi, order by: dùng để sắp xếp kết quả SELECT.
![image](https://github.com/user-attachments/assets/c82c6512-ce59-4672-8c1e-b20e6536c6c1)
## Lọc ra sv nu nghành kmt
### Lọc theo ngành KMT
### Suy luận giới tính nữ theo họ đệm (ví dụ: Thị)
### Suy luận thêm theo danh sách tên nữ phổ biến
![image](https://github.com/user-attachments/assets/8b4bb5f9-0411-4f20-9bdf-3f15973b9f5b)









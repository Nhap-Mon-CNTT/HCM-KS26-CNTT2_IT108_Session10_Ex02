# Yêu cầu đầu ra:

## Phần 1: Phân tích
```
1. Giới thiệu 
    1.1. Mục đích 
    1.2. Phạm vi 
    1.3. Định nghĩa, viết tắt và tài liệu tham khảo 
2. Mô tả tổng quan 
    2.1. Tổng quan hệ thống 
    2.2. Vai trò người dùng 
3. Mô tả chức năng lớp học ảo (Functional Requirements) 
    3.1. Tạo và quản lý lớp học 
    3.2. Tham gia lớp học 
    3.3. Tính năng trong lớp học 
4. Yêu cầu phi chức năng 
    4.1. Hiệu năng và khả năng mở rộng 
    4.2. Bảo mật và khả dụng 
5. Ràng buộc và giả định 
6. Phụ lục
```
## Phần 2: Báo cáo:
- File word: [SRS_HocTrucTuyen.docx](SRS_HocTrucTuyen.docx)
- File Excel: [DuLieu_HocTrucTuyen.xlsx](DuLieu_HocTrucTuyen.xlsx)
- File Powerpoint: [BaoCao_HocTrucTuyen.pptx](BaoCao_HocTrucTuyen.pptx)
- Kết quả lọc điểm chuyên cần dưới 7 và là khoa công nghệ thông tin: [KetQuaLoc.png](KetQuaLoc.png)
## Phần 3: Kiểm thử: 
- Dựa vào file DuLieu_HocTrucTuyen.xlsx thì ta sẽ thực hiện cách để sử dụng hàm `TRIM` để loại bỏ khoảng trắng thừa, vì nếu có khoảng trắng thừa thì khi lọc theo tên sẽ không được: bằng cách tạo một cột phụ bên cạnh cột họ và tên sau đó tại ô cùng hàng với người đầu tiên gõ =TRIM(B2) sau đó kéo xuống đến B13. Sau khi xử lý xong thì sử dụng cột phụ này để lọc theo tên.
## 2. PHÂN TÍCH
Quản lý đề cương cho từng môn học
Xuất file word, pdf, ...


### 2.1 Giới thiệu
Có UI để quản lý đề cương môn học, chương trình đào tạo của bộ môn, phân công giảng viên, thống kê, xuất file, tìm kiếm, phê duyệt đề cương, chương trình đào tạo

UI đơn giản dễ sử dụng, dễ tìm kiếm, dễ thống kê, dễ xuất file, dễ phê duyệt đề cương, chương trình đào tạo

#### 2.1.1. Mục đích

Mục đích của tài liệu này nhằm mô tả một cách đầy đủ và toàn diện yêu cầu của ứng dụng: các yêu cầu chức năng, yêu cầu phi chức năng, các ràng buộc về mặt thiết kế.

#### 2.1.2 Phạm vi
Phạm vi dùng cho trường đại học CÔNG NGHIỆP TP.HCM
Cho các giáo viên bộ môn có thể quản lý đề cương môn học của mình
Cho trưởng bộ môn có thể quản lý chương trình đào tạo của bộ môn

### 2.2 Phân tích yêu cầu
Có thể quảng lý đề cương môn học
Có thể quản lý chương trình đào tạo của bộ môn 
Xuất ra file word, pdf, ...
Lưu trữ trên server
Có thể tìm kiếm thông tin
Có thể thống kê thông tin


#### 2.2.1 Đặc tả Actors
Sủ dụng để quản lý đề cương môn học
Sử dụng để quản lý chương trình đào tạo của bộ môn


#### 2.2.2 Đặc tả Use-cases

- Danh sách các use-cases:
    - UC01: Đăng nhập
    - UC02: Thống kê
    - UC03: Tạo đề cương
    - UC04: Xem đề cương
    - UC05: Xóa đề cương
    - UC06: Sửa đề cương
    - UC07: Tìm kiếm
    - UC08: Xuất file
    - UC09: Phê duyệt đề cương
    - UC10: Tạo chương trình đào tạo
    - UC11: Xem chương trình đào tạo
    - UC12: Xóa chương trình đào tạo
    - UC13: Sửa chương trình đào tạo
    - UC14: Tìm kiếm
    - UC15: Xuất file
    - UC16: Phê duyệt chương trình đào tạo
    - UC17: Phân công giảng viên
- Liệt kê các use-cases theo actor: (LƯU Ý: nếu phần này các chức năng thực hiện khác nhau ở mỗi actor thì ghi rõ các khác nhau đó)
    - Actor 1:
        - UC01: đăng nhập
        - UC03: tạo đê cương
        - UC04: xem đê cương
        - UC05: xóa đê cương
        - UC06: sửa đê cương
        - UC07: tìm kiếm
        - UC08: xuất file
        - UC09: Phê duyệt đê cương
    - Actor 2:
        - UC01: đăng nhập
        - UC02: thống kê
        - UC03: tạo chương trình đào tạo
        - UC04: xem chương trình đào tạo
        - UC05: xóa chương trình đào tạo
        - UC06: sửa chương trình đào tạo
        - UC07: tìm kiếm
        - UC08: xuất file
        - UC09: Phê duyệt chương trình đào tạo
        - UC10: Phân công giảng viên
        - UC11: Tất cả các chức năng của actor 1

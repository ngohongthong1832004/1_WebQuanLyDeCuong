# XÂY DỰNG ĐỀ TÀI QUẢN LÝ ĐỀ CƯƠNG MÔN HỌC (FIT-curriculum)

- Web giải quyến vẫn đề quảng lý đề cương môn học một cách thông nhất theo một tiêu chuẩn đã được định sẵn nhằm mục đích thuận tiện nhất trong việc quản lý
  - Ứng dụng có thể CRUD đề cương, CRUD chương trình đào tạo cho từng khóa
  - Đối tượng người dùng là Giảng viên trường đại học IUH 

- Bạn có thể trải nghiệm ứng dụng ở đây [LINK](https://my-curr-v2.vercel.app/)
- Một số sceenshot của ứng dụng

## CÀI ĐẶT

Clone GitHub submodules:
- Clone tất cả các sorce:  ```git clone --recursive https://github.com/ngohongthong1832004/1_WebQuanLyDeCuong.git```
- Sau khi clone thì vô từng thư mục để có thể chạy từng phần riêng biệt:
- Front-End
    + ``` cd .\1_WebQuanLyDeCuong ```
    + ``` cd FE ```
    + ``` npm install ```
    + ``` npm run start ```
- Back-End
    + ``` cd backend_web_decuong ```
    + ``` python -m venv .venv ```
    + ``` .venv\Script\active ```
    + ``` pip install -r requirements.txt ```
    + ``` cd mysite```
    + ``` .\init_db.bat ```
    + ``` .\run.bat ```


## THÔNG TIN THÀNH VIÊN

- Ngô Hồng Thông MSSV: 22649011
- Hồ Duy Trường MSSV: 22671851

## TRÁCH NHIỆM

- Hồ Duy Trường:
    + Xây dụng BE
    + Xây dùng DB
    + Build docker
- Ngô Hồng Thông:
    + Xây dụng FE
    + Deploy sản phẩm
    + Thiết kế ứng dụng


---

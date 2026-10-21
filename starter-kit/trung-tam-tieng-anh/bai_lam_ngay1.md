# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên: Lê MInh Quân**
- **Lớp: CNTT3**
- **Link repository:**
- **Hệ điều hành (Windows/macOS): Windows**

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng
PS D:\starter-kit\starter-kit\trung-tam-tieng-anh> pwd
PS D:\starter-kit\starter-kit\trung-tam-tieng-anh> ls -r
PS D:\starter-kit\starter-kit\trung-tam-tieng-anh> mv .\Lich_Hoc.txt .\docs\; mv .\Logo_Trung_Tam.PNG,.\Anh_Lop_Hoc.JPG .\media\
PS D:\starter-kit\starter-kit\trung-tam-tieng-anh> cp .\media\Logo_Trung_Tam.PNG .\archive\
PS D:\starter-kit\starter-kit\trung-tam-tieng-anh> rm .\temp_201.tmp
PS D:\starter-kit\starter-kit\trung-tam-tieng-anh> rm .\temp_202.tmp
PS D:\starter-kit\starter-kit\trung-tam-tieng-anh> cd .\logs\
PS D:\starter-kit\starter-kit\trung-tam-tieng-anh\logs> ls
PS D:\starter-kit\starter-kit\trung-tam-tieng-anh>
PS D:\starter-kit\starter-kit\trung-tam-tieng-anh> cd .\docs\
PS D:\starter-kit\starter-kit\trung-tam-tieng-anh\docs> cp ..\media\Anh_Lop_Hoc.JPG ..\archive\
PS D:\starter-kit\starter-kit\trung-tam-tieng-anh\docs> cd ..

```

### Kết quả B1 (pwd)

```text
PS D:\starter-kit\starter-kit\trung-tam-tieng-anh> pwd

Path
----
D:\starter-kit\starter-kit\trung-tam-tieng-anh

```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
Directory: D:\starter-kit\starter-kit\trung-tam-tieng-anh


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/20/2026   8:44 PM                archive
d-----        10/20/2026   8:34 PM                data
d-----        10/20/2026   8:43 PM                docs
d-----        10/20/2026   8:34 PM                logs
d-----        10/20/2026   8:43 PM                media
-a----        10/19/2026  10:04 AM             83 .env
-a----        10/19/2026  10:04 AM            902 bai_lam_ngay1.md


    Directory: D:\starter-kit\starter-kit\trung-tam-tieng-anh\archive


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM          13559 Anh_Lop_Hoc.JPG
-a----        10/19/2026  10:04 AM           5184 Logo_Trung_Tam.PNG


    Directory: D:\starter-kit\starter-kit\trung-tam-tieng-anh\data


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM           5070 Hoc_Vien_Khoa_3.xlsx


    Directory: D:\starter-kit\starter-kit\trung-tam-tieng-anh\docs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM             67 Lich_Hoc.txt


    Directory: D:\starter-kit\starter-kit\trung-tam-tieng-anh\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM           1072 Access.log


    Directory: D:\starter-kit\starter-kit\trung-tam-tieng-anh\media


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM          13559 Anh_Lop_Hoc.JPG
-a----        10/19/2026  10:04 AM           5184 Logo_Trung_Tam.PNG

```

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** 85/100
- **Lỗi mình đã mắc và cách sửa:sửa kebab-case nhưng vẫn để cái đầu in hoa**

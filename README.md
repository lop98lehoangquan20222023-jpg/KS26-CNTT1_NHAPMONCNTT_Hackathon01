# KS26-CNTT1_NHAPMONCNTT_Hackathon01
# BÀI LÀM – HACKATHON 01

- **Mã đề:** 18
- **Họ tên:Lê Hoàng Quân** 
- **Lớp:CNTT1** 
- **Link repository:** 
- **Hệ điều hành (Windows/macOS):Window** 

## 4.2. Thao tác máy tính cơ bản bằng CLI

### Các lệnh đã chạy

```shell
pwd
ls
cp '.\Logo Noi That.PNG.\' media
cp '.\kich_thuoc.txt\' docs
cp .\media\* backup
rm temp_267.tmp
cd .\logs\

```

### Kết quả liệt kê toàn bộ dự án (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/28/2026   7:59 AM                backup
d-----        10/28/2026   7:51 AM                docs
d-----        10/28/2026   7:51 AM                logs
d-----        10/28/2026   7:54 AM                media
------        10/27/2026   1:32 AM             68 .env
------        10/27/2026   1:32 AM           6121 Don Noi That Quy 1.xlsx
------        10/27/2026   1:32 AM           1028 Furniture.log
-a----        10/27/2026   1:32 AM             53 kich thuoc.txt
------        10/27/2026   1:32 AM           4403 Logo Noi That.PNG

```

## 4.3. Lọc log thủ công

### Lệnh đã chạy

```shell
get-content .\Furniture.log | select-string "ERROR" >> daily_report.txt
```

### 2 dòng lỗi đầu tiên trong daily_report.txt

```text
2026-01-28 07:35:33 [ERROR] Dat coc bi tu choi
2026-01-28 07:47:33 [ERROR] Dat coc bi tu choi

```

## 4.4. Thao tác với tài liệu Markdown (README.md)

> README.md được chấm trực tiếp trên file `README.md` ở gốc dự án. Đánh dấu `[x]` vào các mục đã làm để tự kiểm tra.

- [x] Heading 1: tên dự án
- [x] Mô tả ngắn có cả **in đậm** và *in nghiêng*
- [x] Bảng `Thư mục | Nội dung`, ít nhất 3 dòng dữ liệu
- [x] Code block chứa lệnh PowerShell/Terminal liệt kê nội dung dự án
- [x] Task list ít nhất 2 công việc, có ít nhất 1 mục đã hoàn thành
- [ ] Blockquote nhắc không upload `.env`

## 4.5. Chạy script auto_report (.ps1 hoặc .sh)

### Lệnh chạy (Windows: nếu dùng Phụ lục 2 thì ghi cả 2 lệnh)

```shell
#Script:auto_report.ps1
#Tac gia:Le Hoang Quan
#Ngay hoan thien:28-10-2026
@echo off
Write-Host"dang loc log..." >> auto_report.txt
echo "===Bao cao loi===" >> auto_report.txt
get-content .\Furniture.log | select-string "ERROR" >> auto_report.txt
echo "Write-Host "Hoan Thanh"" >> auto_report.txt

```

### Kết quả hiển thị

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.6. Đếm số dòng lỗi

### Lệnh

```shell
# Ghi lệnh vào đây (xoá dòng này)

```

### Kết quả đếm (Windows: giá trị Count; macOS: con số in ra)

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.7. Báo cáo tổng hợp

### Các lệnh đã chạy

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng (xoá dòng này)

```

### Nội dung file logs/tong_hop.txt

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.8. Excel

> Phần Excel được chấm trực tiếp trên file `data/don_noi_that_quy_1.xlsx`, không cần ghi vào đây.

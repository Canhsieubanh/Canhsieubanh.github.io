+++
date = '2026-03-08T14:41:25+07:00'
draft = false
title = 'Glory of the Garden'
summary = 'Một challenge khởi động cực cháy trong mảng Forensics. Liệu những gì mắt thấy có phải là tất cả? Cùng soi xem flag giấu ở đâu nhé!'
+++

Đây là một bài Forensics khá thú vị được đánh giá mức độ Dễ trên picoCTF, rất phù hợp với những ai mới bắt đầu. 
## Ta mở thử thách lên và có đề bài như sau: 
![Ảnh chụp terminal chạy lệnh strings](/images/gloryofthegarden.png)
## Đề bài gợi ý về một "Trình chỉnh sửa hex", ta nghĩ ngay tới Hexed.it
#### Chi tiết bước giải:
##### Bước 1: Tải ảnh đề bài cung cấp [Tải file đề bài: garden.jpg](/files/garden.jpg) , mở trình duyệt Internet, gõ `Hexed.it` trên thanh tìm kiếm và truy cập vào.
##### Bước 2: Nhấn vào "Mở tệp" rồi chọn vào file ảnh đề bài cung cấp.
##### Bước 3: Nhấn vào ô "Tìm kiếm", gõ "pico" rồi nhấn Enter , sau đó ta sẽ thấy flag sẽ hiện ra ở cột bên phải 
![Ảnh chụp terminal chạy lệnh strings](/images/flaggarden.png)
**Flag:** `picoCTF{more_than_m33ts_the_3y395e12915}`
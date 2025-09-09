# Arduino_Project_Template

`git clone https://github.com/longhoney/4WD_I2C-Motor-Driver_Mecanum.git`

- git status
- git add . // git add examples/<File_Name>
- git status
- git commit -m"editted readme"  
- git push

`Code test 2 driver`
- Xe đi tiến và đi lùi tốt khi bắt đầu ở tốc độ 100% và giảm dần xuống 50%
- Xe đi tiến tốt khi bắt đầu ở tốc độ 50% và tăng dần
- Xe đi lùi tốt khi bắt đầu ở tốc độ 75% và tăng dần

`Quy tắc kết nối`
- Dây cấp nguồn phải to, không được dùng dây bus

`Cập nhật`
- Sau khi thay dây nguồn, dùng sang nguồn tổ ong 12V-5A (Lm2596 3A xuống 9V). Code nạp vào Uno vẫn chạy hiệu quả, nhưng có thể do nguồn cấp nên dù ra lệnh chạy 100% nhưng 4 bánh chạy như 50%
- lm2596 khá nóng, động cơ cũng nóng lên vì quay chậm trong thời gian dài
- Dùng Pin sạc thì động cơ quay nhanh. Nhưng ở lệnh stop, các động cơ không stop được
- Xe chạy đúng 1 lúc rồi lại bị lỗi chương trình: xe chạy liên tục không dừng, ban đầu chạy nhanh sau đó chạy chậm

`Cập nhật tiến độ`
- https://docs.google.com/document/d/1SmDWLpdE43OGyefFhWPm1k47KTTY6QEGslYMM_aYo_g/edit?usp=sharing
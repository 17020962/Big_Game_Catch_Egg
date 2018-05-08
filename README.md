# Big_Game_Catch_Egg
Big_Game
Bài Tập lớn giữa kì 2 năm Nhất

_ Cách cài đặt: Giải nén file rar rồi vào file đã giải nén rồi vào file exe để chơi.

Bài tập lớn học kì hai năm nhất được thực hiện bởi sinh viên Trần Hồng Phúc có các nội dung sau:

Làm một trò chơi theo yêu cầu của thầy có tựa đề là Catch Egg bằng thư viện lập trình SDL
Trò chơi có luật chơi như sau: Người chơi sử dụng các phím up, dowm, right, left để điều khiển cái rổ hứng trứng và hứng các quả trứng, nếu người chơi hứng trúng thì điểm sẽ tự động tăng lên, nếu hứng trượt mạng sống sẽ giảm xuống, nếu mạng sống không còn (có nghĩa là số quả tim trên màn hình không còn) hoặc người chơi hứng phải quả bom thì trò chơi kết thúc.
Người chơi có thể xem điểm cao và thông tin trước khi chơi.
Các đối tượng trong game : egg (bao gồm ba quả trứng với egg, egg2, egg3 và bomb) Basket (chỉ có basket)

Game chia ra các file: Common.h Common.cpp : file này có tác dụng chứa các hàm dùng chung trong game

Basket.h Basket.cpp : file này có tác dụng chứa các hàm xử lí cho cái rổ hứng trứng

egg.h egg.cpp : file này có tác dụng chứa các xử lí với trứng

main.cpp : file này có tác dụng xử lí chính cho game

các file hình ảnh và các file .dll hỗ trợ đồ họa cho SDL

Lưu ý: việc quả bom và quả trứng di chuyển load ảnh giống nhau hoàn toàn nên cùng một class chỉ có đoạn va chạm là khác nhau đã xử lí ở hàm main.

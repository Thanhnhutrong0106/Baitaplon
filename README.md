# Henvenly Forest
* Họ và tên: Nhữ Trọng Thành
* Mã Sinh Viên: 22028219
* Lớp môn học: INT2215_23
## Mục lục 
1. Hướng dẫn cài đặt và chạy game
2. Mô tả chung về trò chơi
3. Các chức năng của trò chơi
4. Các kỹ thuật lập trình được sử dụng
5. Hỗ trợ
6. Kết luận
7. Tham khảo
## I, Hướng dẫn cài đặt và chạy game
### B1: Tải project về
Cách 1: Trên Github, chọn Code => Copy url, sau đó mở Terminal, gõ git clone + url
Cách 2: Tải trực tiếp file Zip về và giải nén
### B2: Cài đặt Visual Studio 2022
Vào google gõ VS2022 và tải về bản mới nhất, cài đặt lên máy tính
### B3: Chạy game
Mở VS2022, chọn Open Project, mở file ProjectNewSdl.sln từ file đã tải về
## Mô tả chung về trò chơi
### Thể loại: Game đi ải, platformer
Game sinh tồn phiêu lưu trong thế giới 2D, lấy ý tưởng từ tựa game nổi tiếng Contra
Người chơi sẽ hóa thân vào vai một trong những nhân vật ở thế giới Fantasy, trên đường khám phá những thế giới mới
### Các chức năng của trò chơi
* Điều khiển nhân vật bằng các phím a, d để di chuyển sang trái và phải
* Sử dụng nút phải chuột để bắn ra quả cầu ma thuật, nút trái chuột để nhảy di chuyển và tránh các chướng ngại
* Quái vật sẽ tự đuổi người chơi trong phạm vi tấn công, đồng thời sẽ bắn đạn khi người chơi ở trong tầm ngắm của quái
* Chèn âm thanh vào các button
* Được phép chọn nhân vật, chọn Map tăng hứng thú cho người chơi
* Ghi điểm, được hiện ở thanh menu phía trên màn hình
### Các kỹ thuật lập trình được sử dụng
* Sử dụng thư viện đồ họa SDL2
* Lập trình hướng đối tượng (class) dùng để tạo các đối tượng riêng biệt thực hiện các chức năng của trò chơi
* Sử dụng các kỹ năng cơ bản như Tile Map, kiểm tra va chạm, xử lí animation, frame,.... Ngoài ra em còn tự tìm hiểu và phát triển thêm thuật toán giúp quái tự di chuyển, bắn đạn khi nhân vật trong tầm ngắm
* Biến/kiểu dữ liệu/con trỏ/cấp phát động dùng trong các hàm trong thư viện
* Danh sách/nhiều đối tượng
### Hỗ trợ
* Sử dụng các phần mềm edit để vẽ ảnh nhân vật như PhotoShop, Canva
* Sử dụng phần mềm để tạo map tương đối rộng và đa dạng: Tiled
* Sử dụng Aseprite để vẽ các nhân vật, quái và chi tiết cho map
### Kết luận
* Sử dụng thư viện đồ họa SDL2
* Tự thiết kế đồ họa cho game (có sử dụng ý tưởng sẵn có trên các web như Crapix, itch.io,...)
* Thiết kế map, nhân vật đa dạng, có thể thay đổi
### Tham khảo
* Hướng dẫn làm game của Codegrapher
* Hướng dẫn làm game của Phát triển phần mềm 123az.com
* Tựa game Dino in Jungle, SwordX của anh chị khóa trên
* Các trang web miễn phí về đồ họa như Crapix, Itch.io,....

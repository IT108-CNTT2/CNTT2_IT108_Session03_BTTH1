### **Phần 1: Phân tích**

* Việc đặt file trong System32 sẽ không làm tốc độ đọc/ghi file nhanh hơn mà tốc độ đọc/ghi file phụ thuộc vào loại ssd/hdd mà bạn Huy đang dùng.  
* Sai lầm của Nam khi đặt tên lưu trữ là tên tệp, thư mục có khoảng trống “C:\\Windows\\System32\\Bai Tap Cua Nam\\Session 01\\bai tap 1.py” . Điều này có thể khiến mốt số app không đọc được khoảng trắng sẽ gây ra xung đột và lỗi.   
* Nam không bị nhà mạng lừa mà Mbps và Mb/s là hai đơn vị khác nhau.  
  * Gói mạng 100Mbps: 100 Megabit/s    
  * Tốc độ mạng đạt 12.5Mb/s: 12.5 megabyte/s  
  * 1 byte \= 8 bit  
  * Vậy lấy 100 / 8 \= 12.5Mb/s  
  * Vậy gói mạng 100Mbps hoàn toàn đúng với tốc độ mạng 12.5Mb/s.

  → Gói tệp tin python 1GB thì sẽ đạt thời gian tải: 1000Mb / 12.5Mb/s \= 80s

* Lý do ổ SSD 256 GB thực tế lại hiển thị dung lượng thấp hơn con số 256:  
  * Vì cách tính dung lượng của từng hệ điều hành là khác nhau  
  * 256GB \= 10^9 byte  
    * 1GB \= 1024^3 byte  
    * Do đó:  
      * 256GB \= 256 \* 1000000000  
      * 1GB \= 1073741824 bytes  
      * 256000000000 / 1073741824 $\approx$ 238GB  

### **Phần 2: Hoàn Thiện**

D:\\nam-study\\programming\\python\\session-01\\  
├── hello-world.py  
├── calculator.py  
├── loop-practice.py  
├── function-practice.py  
└── README.md  

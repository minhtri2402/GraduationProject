# GraduationProject
1. Đề tài:
            Xây dựng hệ thống dự đoán và cảnh báo cháy tự động
          
2. Mô tả
- Thiết lập dự báo và cảnh báo cháy thông qua các cảm biến, các cảm biến đc kêt nối với 1 chip dùng để xữ lí thông tin
- Hệ thống đc xây dựng trên nền tảng arduino 
- Sữ dụng Firebase database để upload dữ liệu

3. Thiết bị
- Chip NodeMCU(ESP 8266)
- Sensor DHT22( cảm biến độ ẩm và nhiệt độ)
- Sensor FLame(cảm biến lửa)

4. Tổng quang về hệ thống

- Nếu nhà có lửa học độ ẩm và nhiệt độ thay đổi đột ngột, có nguy cơ dẫn đến cháy, thì hệ thống sẽ xữ lí thông tin, phân theo từng cấp dộ khác nhau để cảnh báo cho gia chủ qua trang web hoạc cảnh báo qua app trên thiết bị di động

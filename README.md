## jmeter-Load-Testing
## Tổng quan về JMeter
- Jmeter là một phần mềm cái mà có thể sử dụng để chạy thử nghiệm hiệu suất, thử nghiệm tại và thử nghiệm chức năng của ứng dụng web. - JMeter cũng có thể mô phỏng tải nặng trên máy chủ bằng cách tạo hàng tấn người dùng ảo đồng thời lên máy chủ web.

- JMeter là một ứng dụng mã nguồn mở. Điều này có nghĩa là bạn có thể tải xuống mã nguồn của JMeter để phân tích và sửa đổi nó nếu bạn muốn.

- Stefano Mazzocchi của Quỹ phần mềm Apache thiết kế nó đầu tiên. Bây giờ anh ấy là một kỹ sư phần mềm tại Google. Ngày nay, JMeter đã trở thành một trong những công cụ thử nghiệm phổ biến nhất trên thế giới, bên cạnh Selenium và Load Runner.
# Mục tiêu:
    - Giới thiệu các khái niệm cơ bản về jMeter.
    - Hướng dẫn sinh viên cách sử dụng jMeter để thực hiện các bài kiểm tra hiệu năng đơn giản.
    - Giúp sinh viên hiểu cách phân tích kết quả kiểm tra và đưa ra kết luận. 
# Mô tả bài tập
    - Bài tập nhằm giới thiệu các khái niệm cơ bản về jMeter và hướng dẫn sinh viên cách sử dụng jMeter để thực hiện các bài kiểm tra hiệu năng đơn giản.
## Kịch bản kiểm tra
## Thread Group
    - Number of Threads: 10
    - Ramp-Up Period(seconds): 2
    - Loop Count: 10
### 1. Kiểm tra `canvas.phenikaa-uni.edu.vn`
- ![image](https://github.com/quang10122003/JMeter_test/assets/124878902/975f424c-2ca5-40fc-afb2-583dd59f06bb)


### 2. Kiểm tra `canvas.phenikaa-uni.edu.vn/courses`
- ![image-1](https://github.com/quang10122003/JMeter_test/assets/124878902/b18f14f6-981f-4f86-9120-e177ea9a9dcb)

### 3. Kiểm tra `canvas.phenikaa-uni.edu.vn/courses/10836`
- ![image-2](https://github.com/quang10122003/JMeter_test/assets/124878902/e1276356-848e-4737-865a-5a4d124207d7)


### 4. View Results Tree
- ![image-3](https://github.com/quang10122003/JMeter_test/assets/124878902/37e53e4b-7969-414b-af1b-121b77fa8a28)

## Kết quả in ra loading.csv
- ![image-4](https://github.com/quang10122003/JMeter_test/assets/124878902/e37236d7-1a81-4dff-8421-699776b10bec)

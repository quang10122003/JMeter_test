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
- ![alt text](image.png)


### 2. Kiểm tra `canvas.phenikaa-uni.edu.vn/courses`
- ![alt text](image-1.png)

### 3. Kiểm tra `canvas.phenikaa-uni.edu.vn/courses/10836`
- ![alt text](image-2.png)

### 4. View Results Tree
- ![alt text](image-3.png)
## Kết quả in ra loading.csv
- ![alt text](image-4.png)

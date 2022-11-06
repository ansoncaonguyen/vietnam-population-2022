# TÌNH HÌNH DÂN SỐ VIỆT NAM 

## Các thành viên

| MSSV | Họ tên              | Github                                               |
| ------------ | ----------------- | ---------------------------------------------------- |
| 18127196     | Cao Nguyễn An Sơn | [@ansoncaonguyen](https://github.com/ansoncaonguyen) |
| 18127124     | Bùi Thành Long    | [@buithanhlongcb](https://github.com/buithanhlongcb) |
| 18127113     | Võ Văn Quốc Huy   |
| 18127187     | Dương Ngọc Nguyên Phương | [@dnnphuong](https://github.com/dnnphuong)


## Thông tin đề tài

Lấy ý tưởng từ việc dân số hiện đang là một trong những vấn đề đáng quan tâm tại thế giới nói chung và Việt Nam nói riêng. Do tầm quan trọng và mức độ ảnh hưởng sâu rộng, có thể nói là ít nhiều tác động trực tiếp đến tăng trưởng kinh tế của nước nhà, các vấn đề về giáo dục, giáo dục, y tế, môi trường dẫn theo nhiều hệ luỵ đáng quan ngại...

Ở đề tài lần này, nhóm chọn Trực quan hóa về dân số tại đất nước Việt Nam. Nhóm có bộ dữ liệu thông qua trang của Tổng Cục Thống Kê Việt Nam: [[link]](https://www.gso.gov.vn/). Tại đây dữ liệu khá đa dạng và đầy đủ được tổng hợp thành các file: csv, xlsx… và cho phép người dùng tải về sử dụng với định dạng người dùng mong muốn. Sau đó, nhóm sẽ sử dụng Python để thực hiện tiền xử lý để có được các thông tin mong muấn thuận tiện cho việc trực quan hóa dữ liệu,

Ngoài ra, nhóm sử dụng thêm nguồn dữ liệu từ Word Bank để vẽ nên tháp tuổi. Dữ liệu sau khi được tải về có thể trực tiếp sử dụng Tableau cho việc tiền xử lý.

## Các dashboard

### Dashboard chính

Dashboard chính thể hiện dân số trung bình và mật độ dân số của các tỉnh thành tại Việt Nam. 

![main dashboard](/img/dashboard1.png "Dashboard chính")


Nhóm có sử dụng thêm biểu đồ Tree Map để thể hiện sự tương quan giữa dân số trung bình và mật độ dân số của các tỉnh thành. Mật độ dân số tiếp tục sử dụng màu sắc để thể hiện, còn dân số trung bình ta sẽ sử dụng kích thước của ô trong biểu đồ. Ta thấy, hai thành phố Hồ Chí Minh và thủ đô Hà Nội vừa có dân số trung bình cao nhất cũng như mật độ dân số cũng lần lượt đứng vị trí cao nhất. Ở các tỉnh thành còn lại, ta thấy rõ dù dân số trung bình có cao nhưng chưa chắc có mật độ dân số cao. Ví dụ như trường hợp của Thanh Hóa và Nghệ An có dân số trung bình cao hơn nhưng có mật độ dân số thấp hơn hai tỉnh thành có diện tích nhỏ hơn nhưng hiện có nhiều các khu công nghiệp là Đồng Nai và Hải Phòng.

Ngoài ra, nhóm còn sử dụng biểu đồ cột để thể hiện dân số trung bình giữa thành thị và nông thôn, cũng như giữa nam và nữ. Biểu đồ tròn để thể hiện dân số trung bình phân theo các vùng, cũng như thông tin về tuổi thọ trung bình và dân số trung bình ở nước ta. Các thông tin trên sẽ thay đổi tương ứng khi ta thay đổi thanh kéo (slider) để chọn số năm mong muốn.


### Dashboard về thành phần dân số

![dashboard2](/img/dashboard2.png "Dashboard 2")

Dashboard chứa các biểu đồ về tháp tuổi, so sánh giữa tỉ suất sinh thô và dân số trung bình. Cũng như thông tin về chỉ số già hóa, tỷ lệ giới tính và tuổi thọ trung bình trong 5 năm.

### Dashboard về dân số và kinh tế

![dashboard3](/img/dashboard3.png "Dashboard 3")

Dashboard cuối cùng chứa biểu đồ về phần trăm người lao động được đào tạo trong các ngành kinh tế, biểu đồ so sánh giữa tỷ lệ thiếu việc làm và thất nghiệp và cuối cùng là dự đoán tỷ lệ dân số được đào tạo trong những năm sắp tới.

Xem báo cáo hoàn chỉnh tại: [[link]](report/Report.pdf)

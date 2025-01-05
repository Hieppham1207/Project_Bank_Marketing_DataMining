# Project_Bank_Marketing_DataMining

 I.**MÔ TẢ TẬP DỮ LIỆU:**
Tập dữ liệu bao gồm 45211 bản ghi tương ứng với 45211 khách hàng lưu trữ thông tin về chiến dịch marketing mở sổ tiết kiệm có kỳ hạn. Mỗi một bản ghi tương ứng với một khách hàng mà ngân hàng đã liên lạc để tiếp thị dịch vụ, bao gồm 10 thông tin như sau:
* **Phần A.Dữ liệu khách hàng:**
1. age: Tuổi của khách hàng (int)
2. job: Nghề nghiệp ("admin.","unknown","unemployed","management","housemaid","entrepreneur","student", "blue-collar","self-employed","retired","technician","services")
3. marital: Tình trạng hôn nhân ("married","divorced","single")
4. education: Trình độ học vấn ("unknown","secondary","primary","tertiary")
5. balance: Số dữ trong tài khoản(đơn vị: Euro)
6. loan: Hiện có vay liên tiêu dùng cá nhân nào hay không (yes/no)

* **Phần B.Thông tin liên quan tới chiến dịch tiếp thị:**
7. contact: loại kết nối liên lạc tới khách hàng ("other","telephone","cellular")
8. month: Tháng liên lạc marketing cuối cùng trong năm (jan, feb, mar...nov,dec)
9. campaign: Số lần liên lạc với khách hàng này trong một chiến dịch
10. deposit: Kết quả của đợt marketing này là khách hàng có đăng ký tiền gửi tiết kiệm hay không (yes/no)

II. **PHÂN TÍCH** 
1. Thống kê độ tuổi của khách hàng
![image](https://github.com/user-attachments/assets/4d5b65d2-c059-43cf-8c5c-8cc917ae16f2)
**Nhận xét:**
 a. Độ tuổi của khách hàng trong chiến dịch marketing mở sổ tiết kiệm có kỳ hạn nằm trong khoảng từ 18-95 tuổi, tuổi chung bình là ~41 tuổi.
 b. khách hàng trong chiến dịch Marketing này tập trung chủ yếu trong khoảng từ 28-60 tuổi (chiếm ~87%)
2. Thống kê tình trạng công việc
![image](https://github.com/user-attachments/assets/fc5888e4-0c73-46a9-9dd1-176d063760b0)
**NHẬN XÉT:**
 Khách hàng của đợt tiếp thị chủ yếu lao động phổ thông, quản lý, kỹ thuật viên, quản trị viên và người làm dịch vụ chiếm ~ 80% dữ liệu
3. Thống kê tình trạng hôn nhân
   ![image](https://github.com/user-attachments/assets/cd871bdf-6941-43e8-9491-916bcfa33cdf)
4. Thống kê trình độ học vấn của khách hàng
   ![image](https://github.com/user-attachments/assets/1f43b477-4f02-4269-8fd1-4651272afc0e)
5. Thống kê số lượng khách hàng có khoản vay (loan) trong tập dữ liệu thực hiện Marketing
   ![image](https://github.com/user-attachments/assets/4a37979e-cba0-49df-8011-9aef9163d0e0)
6. Thuộc tính số dư tài khoản (balance) trong tập khách hàng thực hiện Marketing
   ![image](https://github.com/user-attachments/assets/10bef1f8-1e1b-44ef-8484-ac2612f17a83)
   ![image](https://github.com/user-attachments/assets/1f7691b7-fe72-4a0d-88ab-53407c5dc5c2)
   **NHẬN XÉT:**
   a. Khoản dư trong tài khoản khách hàng có mức độ biến thiên lớn từ -8019 đến 102127 Euro
   b. Khoản dư trung bình của mỗi tài khoản là ~ 1362 Euro
   c. Số khách hàng có khoản dư <=0 chiếm ~ 16%, >=2500 Euro chiếm ~ 15%;
   d. Đại đa số khách hàng trong chiến dịch Marketing có số dư nằm trong khoảng (0,2500) chiếm ~ 70% dữ liệu
7. Loại liên lạc sử dụng để marketing
   ![image](https://github.com/user-attachments/assets/646a6e78-51cd-4135-9dd1-7f1ac4c3a1ff)
8. Kết quả
   ![image](https://github.com/user-attachments/assets/09df18bc-04f0-4df5-9f36-3ff3f692e7ee)

III. CÁC YẾU TỐ ẢNH HƯỞNG ĐẾN MỞ SỔ TIẾT KIỆM
1. Đánh giá Công việc của khách hàng tới việc mở sổ
   ![image](https://github.com/user-attachments/assets/7096234b-02ca-4658-9fad-5ae6b676f747)
2. Đánh giá Tình trạng hôn nhân của khách hàng tới việc mở sổ
   ![image](https://github.com/user-attachments/assets/f1cc65b3-9a6d-471e-bf07-9e82d8c207f9)
3. Đánh giá trình độ học vấn (education) của khách hàng tới việc mở sổ
   ![image](https://github.com/user-attachments/assets/97189f60-3159-4457-a1b2-a8cf66ad1d68)
4. Đánh giá Độ tuổi (age) khách hàng tới hiệu quả của chiến dịch Marketing
   ![image](https://github.com/user-attachments/assets/39bd64a1-73e1-4ac3-84ee-3c5912fcf378)
5. Đánh giá Số dư tài khoản (blance) ảnh hưởng tới việc mở sổ
   ![image](https://github.com/user-attachments/assets/5b97b217-26b0-4c16-bcb9-46ab29aab3d2)
6. Đánh giá Loại hình liên lạc (contact) tới kết quả của chiến dịch
   ![image](https://github.com/user-attachments/assets/90c22fc2-d74d-468b-9a63-1609dec9da66)
7. Số lần liên lạc tiếp thị tới khách hàng
   ![image](https://github.com/user-attachments/assets/7241c957-987e-472a-83e6-607b6693f090)
8. Thời gian tiếp thị trong năm ảnh hưởng tới hiệu quả của chiến dịch marketing
   ![image](https://github.com/user-attachments/assets/0a434f3e-0f9d-44ab-9550-416e2aa10d64)


IV. TỔNG KẾT


Từ các phân tích và đánh giá dựa trên dữ liệu của chiến dịch Marketing đã thực hiện, cho thấy việc thực hiện tiếp thị của ngân hàng cho toàn bộ khách hàng thuộc mọi đối tượng tuổi tác, ngành nghề, kéo dài trong suốt cả một năm...là không hiệu quả. 

Để cải thiện và nâng cao hiệu quả cho chiến dịch Marketing sắp tới ngân hàng nên lưu ý một số đề xuất như sau:


**ĐỀ XUẤT 1:** Thực hiện chiến dịch tiếp thị nên chia làm 2 đợt tập trung vào khoảng thời gian đầu năm và cuối năm, mỗi đợt 3 tháng: 

    * Đợt 1: Tháng 2, 3, 4
    * Đợt 2: Tháng 9, 10, 12

**ĐỀ XUẤT 2:** Tập trung tiếp thị với Khách hàng trẻ (<30 tuổi) và già (>=60 tuổi)

**ĐỀ XUẤT 3:** 4 Nhóm ngành nghề của khách hàng ưu tiên lựa chọn cho việc marketing: student (sinh viên); retired (nghỉ hưu); unemployed (thất nghiệp); management (quản lý)

**ĐỀ XUẤT 4:** Tập trung vào các khách hàng có số dư tài khoản từ 1000 euro trở lên và không có khoản vay cá nhân nào

**ĐỀ XUẤT 5:** Nên sử dụng phương thức liên lạc thông qua điện thoại di động và cố định

**ĐỀ XUẤT 6:** Chỉ nên liên lạc marketing tối đa 3 lần với mỗi một khách hàng.










  









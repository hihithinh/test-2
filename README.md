# Quy trình làm việc

## Scrum team
- Project Owner
- Scrum Master
- Development team

## Quy trình thực hiện task

1. Tiếp nhận yêu cầu
2. Phân tích yêu cầu
3. Ước lượng
4. Lên kế hoạch
5. Thực hiện task
6. Review
7. Kiểm thử
8. Bàn giao khách hàng 

### 1. Tiếp nhận yêu cầu

**Thực hiện**: Project owner

**Mục tiêu**: Liệt kê yêu cầu của khách hàng vào danh sách tất cả các công việc cần làm.

### 2. Phân tích yêu cầu

**Thực hiện**: Project owner, Development team

**Mục tiêu**: 
- Định nghĩa như thế nào là "done": Quy định hoặc thống nhất như thế nào để có thể đánh giá task đã hoàn thành.
- Đánh giá được sự ảnh hưởng của task này với những task khác.

### 3. Ước lượng

**Thực hiện**: Development team

**Mục tiêu**: Đưa ra được con số đánh giá độ khó của task.

### 4. Lên kế hoạch

**Thực hiện**: Project owner, Development team

**Mục tiêu**: 
- Project owner: Sắp xếp độ ưu tiên cho các task.
- Development team: Lên kế hoạch thực hiện các task.

### 5. Thực hiện task

**Thực hiện**: Development team

**Mục tiêu**: Tiến hành thực hiện các công việc ở phía lập trình viên để đáp ứng được các yêu cầu để "done".

### 6. Review

**Thực hiện**: Development team

**Mục tiêu**: 
- Đánh giá chất lượng code.
- Đưa ra yêu cầu cải tiến phù hợp.
- Đưa ra những yêu cầu giúp giảm thiểu khả năng gây ra bug hoặc ảnh hưởng tiêu cực đến các task khác.

### 7. Kiểm thử

**Thực hiện**: Development team

**Mục tiêu**: 
- Đảm bảo chất lượng sản phẩm đã đáp ứng được các yêu cầu để "done".
- Đảm bảo chất lượng những task bị ảnh hưởng.

### 8. Bàn giao khách hàng 

**Thực hiện**: Project owner

**Mục tiêu**: Khách hàng feedback về task.

## Quy trình release 
1. Lên kế hoạch release
2. Chuẩn bị release
3. Review
4. Deploy
5. Kiểm thử
6. Bàn giao khách hàng 

### 1. Lên kế hoạch release

**Thực hiện**: Project owner

**Mục tiêu**:  Làm rõ các nội dung sau
- Thời gian release
- Môi trường release:  staging hay production
- Nội dung release: Liệt kê danh sách task mong muốn release
Note: Nên có release history

### 2. Chuẩn bị release

**Thực hiện**: Development team

**Mục tiêu**:  
- Tạo nhánh release: Tổng hợp source code sẽ được release vào một nhánh 
- Tổng hợp các yêu cầu để source code mới nhất có thể chạy bình thường: Cập nhật biến môi trường, cài đặt các gói, thư viện, clear cache, chạy migration, update database,...

### 3. Review

**Thực hiện**: Development team

**Mục tiêu**: 
- Đánh giá chất lượng code.
- Xem lại phần Tổng hợp các yêu cầu để source code mới nhất có thể chạy bình thường

### 4. Deploy

**Thực hiện**: Development team

**Mục tiêu**:  
- Đưa source code mới nhất lên môi trường release
- Đảm bảo các yêu cầu để source code mới nhất có thể chạy bình thường: Cập nhật biến môi trường, cài đặt các gói, thư viện, clear cache, chạy migration, update database,...

### 5. Kiểm thử

**Thực hiện**: Development team

**Mục tiêu**: 
- Đảm bảo chất lượng các task được release ở môi trường release đã đáp ứng được các yêu cầu để "done".
- Đảm bảo chất lượng những task bị ảnh hưởng.

### 6. Bàn giao khách hàng 

**Thực hiện**: Project owner

**Mục tiêu**: Khách hàng feedback về task.

# Một số mong muốn

## Quản lý document
- Ticket cũng có thể dùng để làm document.
- Trường hợp không dùng ticket để làm document, cần:
	- Để document vào trong thư mục google drive của dự án.
	- Gắn link tới document tương ứng với yêu cầu của ticket
- Document quan trọng thì liệt kê vào danh sách tài liệu quan trọng.
- Tài liệu đặt tên rõ ràng, dễ phân biệt, dễ tìm kiếm (nên dùng tiếng Anh)
- Đề xuất format tên tài liệu: 20240126_{Tên dự án}_{Tên tài liệu}

## Ticket
- Tiêu đề và mô tả đều cần áp dụng các theo template.
- Cần định nghĩa rõ ràng như thế nào là "done", cả phía QC và dev đều hiểu một cách thống nhất.
- Cần liệt kê đầy đủ các tài liệu cần cho task **ở trong phần mô tả**.
- Phần mô tả của ticket nên là requirement mới nhất của ticket.
- Nên áp dụng mối quan hệ giữa các task, ví dụ: cha - con.

## Làm việc với khách hàng
- Bởi vì khách hàng không biết tiếng anh và dev không biết tiếng Nhật. Để tối ưu thì khi làm việc với khách hàng nên thông qua PM và IT Comtor.

## Meeting
- Cần agenda và meeting note.
- Nếu không cần thiết có thể không tham gia.
- Meeting note cần format.
- Meeting cần mục đích.

## Áp dụng scrum
- Mọi người học về scrum và chúng ta áp dụng nó vào dự án Sankyo.

### Django Life Cycle

Chi tiết các thành phần:

- **Model**: Thuật ngữ chỉ ra các đối tượng(class, data,...) đơn giản hơn nó đại diện cho dữ liệu sẽ được sử dụng dưới
  dạng
  đối tượng(class). Các class sẽ được khai báo trong models.py, và sau đó chúng ta dùng lệnh migrate để biến chúng thành
  các bảng trong CSDL
- **View**: Là nơi chứa nội dung hiển thị của trang Web. Nội Dung này được thể hiện dưới dạng template Django(Jinja) và
  lưu dưới dạng .html
    + Về cơ bản, nơi đây sẽ lưu 1 tập các tệp .html để làm kết quả trả về cho phần Controller.
    + Controller sẽ gửi data đến các trang views này, chúng ta sử dụng ngôn ngữ mẫu django kiểu như vậy
    + <p> {% a = "Khoa" %} </p> - > <p>Khoa</p>

- **Controller**: Chứa các chức năng của bộ điều khiển tương ứng với request được các url chỉ định. Mỗi chức năng
  controller thực hiện chức năng truy cập/cập nhật dữ liệu và sau đó truyền các đối tượng dữ liệu này đến View để hiển
  thị
  Điều làm django hơi rối là thành phần controller của MVC lại được đặt tên views.py, nhưng làm 1 hồi các bạn sẽ quên.

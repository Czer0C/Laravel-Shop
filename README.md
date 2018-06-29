# Đồ án cuối kì môn lập trình Web 1

### Thành viên:

**1. Nguyễn Hải Triều**

**2. Trần Quốc Trí**

**3. Dương Quang Vinh**

***

### Yêu cầu:

> ### Xây dựng một website kinh doanh mua bán điện thoại di động.

### Đặc tả:
**1 Phân hệ Anonymous/Guest**

**1.1 Nội dung trang chủ**

- Hiển thị 10 điện thoại mới nhất (sắp giảm theo ngày tiếp nhận).
- Hiển thị 10 điện thoại bán chạy nhất (sắp giảm theo số lượng bán).

**1.2 Menu danh mục**

- Hiển thị danh sách loại điện thoại:
  + Phân theo phổ thông, trung cấp hoặc cao cấp

  + Phân theo giá (tự đặt các ngưỡng giá)

  + Phân theo tính năng (màn hình tràn cạnh, 2 camera…)

  + Nhà sản xuất


**1.3 Trang theo loại điện thoại và trang theo nhà sản xuất**

- Hiển thị các điện thoại theo loại (theo mục 1.2) hay điện thoại theo nhà sản xuất tương ứng vừa được chọn.

**1.4 Trang chi tiết điện thoại**

- Hiển thị được các thông tin sau:

    +  Hình ảnh hiển thị chính

    +  Các bình luận liên quan tới điện thoại này

    +  Giá bán

    +  Số lượt xem

    +  Số lượng bán

    +  Mô tả

    +  Xuất xứ

    +  Nhà sản xuất

    +  Điểm đánh giá trung bình dựa theo bình luận người dùng (từ 1 tới 5 sao)

- Hiển thị danh sách 5 món điện thoại cùng loại

**1.5 Trang Tìm kiếm**

**1.5.1 Tìm kiếm cơ bản**

- Chỉ hiện cho phép người dùng thực hiện tìm kiếm trên một tiêu chí tìm kiếm dựa vào tên của điện thoại

**1.5.2 Tìm kiếm nâng cao**

- Cho phép người dùng thực hiện tìm kiếm trên nhiều tiêu chí như: tên điện thoại, loại điện thoại, nhà sản xuất, giá bán từ khoản nào đến khoản nào… (tùy thuộc vàođộ phức tạp của thông tin mà nhóm sinh viên có thể thực hiện tìm kiếm trên nhiều tiêu chí khác).

**1.6 Đăng nhập và đăng ký**

**1.6.1 Đăng nhập vào hệ thống**

- Thiết kế giao diện hiển thị chức năng đăng nhập vào hệ thống bằng tài khoản của người dùng. Nếu không đăng nhập được thì hiển thị thông báo lỗi cho người dùng.

**1.6.2 Đăng ký tài khoản**

- Tao trang đăng ký tài khoản với một số tiêu chí như sau: 
![N|Solid](https://i.imgur.com/pwuR4JN.png)

- Chức năng Mã kiểm tra sử dụng công nghệ AJAX hoặc tương đương.

**2 Phân hệ Registered User**

- Kế thừa và có đầy đủ các chức năng của phân hệ Anonymous/Guest

**2.1 Thực hiện chọn và mua một món điện thoại**

- Cho phép người dùng lựa chọn mua một món điện thoại nào đó bỏ vào giỏ hàng.

**2.2 Quản lý giỏ hàng**

- Thực hiện quản lý các món điện thoại mà người dùng đã thực hiện mua và bỏ vào giỏ hàng như: thay đổi số lượng mua của một món điện thoại, hủy loại điện thoại đã chọn.

**2.3 Thanh toán toàn bộ giỏ hàng**

- Thực hiện thanh toán toàn bộ giỏ hàng và lưu xuống CSDL. Cập nhật lại số lượng các sản phẩm vừa mới được bán.

**3 Phân hệ Admin**

**3.1 Menu Admin**

- Xây dựng menu hiển thị các chức năng quảnlý điện thoại, quản lý loại điện thoại, quản lý nhà sản xuất, quản lý người dùng, quản lý hóa đơn bán hàng.

**3.2 Quản lý Điện thoại**

- Xây dựng 5 chức năng thêm, xóa, sửa, liệt kê và tìm kiếm thông tin của điện thoại

**3.3 Quản lý Loại điện thoại**

- Xây dựng 5 chức năng thêm, xóa, sửa, liệt kê và tìm kiếm thông tin của loại điện 

**3.4 Quản lý Nhà sản xuất**

- Xây dựng 5 chức năng thêm, xóa, sửa, liệt kê và tìm kiếm thông tin của nhà sản xuất

**3.5 Quản lý Tài khoản người dùng**

- Xây dựng 5 chức năng thêm, xóa, sửa, liệt kê và tìm kiếm thông tin tài khoản người dùng.

**3.6 Quản lý đơn đặt hàng**

- Xây dựng 5 chức năng thêm, xóa, sửa, liệt kê và tìm kiếm thông tin đơn đặt hàngm (trong đó, sẽ thực hiện lại việc cập nhật tình trạng của đơn đặt hàng khi tiến hành giao điện thoại cho khách).


### Các tool sử dụng:
+ Sublime Text
+ Laragon

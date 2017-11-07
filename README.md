# QuanLyKhachSan
# Goals: Phần mềm quản lý Khách sạn cho máy tính cá nhân, chỉ có nhân viên lễ tân, nhân viên bán hàng và quản lý khách sạn được sử dụng. Bao gồm các chức năng:
  1 Quản lý thông tin phòng của khách sạn
  
  2 Quản lý thông tin khách hàng
  
  3 Đặt phòng, hủy đặt phòng
  
  4 Thanh toán cho khách hàng
  
  5 Quản lý báo cáo: Xem báo cáo, tạo hóa đơn,...
  
# Objectives:
  1 Quản lý thông tin phòng của khách sạn:
   - Tìm phòng trống và đặt phòng theo yêu cầu của khách hàng
   - Thêm/sửa/xóa thông tin phòng
   - Thông tin về khách sạn bao gồm : tên, địa chỉ, số sao, mô tả 
   - Trong khách sạn có nhiều phòng được mô tả bằng các thông tin: tên phòng, loại phòng, giá niêm yết, các loại dịch vụ đi kèm, mô tả phòng.
  
  2 Quản lý thông tin khách hàng Mỗi khách hàng:
  - Khi đến ở hoặc đặt phòng, sẽ được lưu các thông tin bao gồm số CMND, loại giấy tùy thân (CMND, passport), họ tên đầy đủ, địa chỉ, số điện thoại, ghi chú về phục vụ đặc biệt như cho người khuyết tật, ăn chay...
  
  3 Đặt phòng, hủy đặt phòng: 
  - Tại một thời điểm, chỉ có một khách ở trong một phòng, và xác định một giá phòng cụ thể.
  -  Khách hàng chỉ có thể đặt phòng nếu phòng đó còn trống trong suốt thời gian khách hàng muốn đặt.
  -  Khách hàng có thể hủy đặt phòng (miên phí) nếu hủy trước ngày đến. Nếu khách hàng hủy sau ngày đặt thì khách hàng bị lưu vào danh sách đen và có thể bị từ chối đặt phòng trong các lần tiếp theo
  -  Mỗi phòng có thể được đặt/ở bởi nhiều khách hàng khác nhau tại những thời điểm khác nhau.
    Mỗi khách hàng có thể đặt/ở nhiều phòng khác nhau tại những thời điểm khác nhau.
  
  4 Thanh toán cho khách hàng: 
  -  Mỗi lần thanh toán, lễ tân sẽ in hóa đơn cho lần thanh toán đó bao gồm các thông tin: họ tên và địa chỉ khách hàng, số phòng, ngày đến, ngày đi, giá phòng, các dịch vụ đi kèm , số tiền thanh toán. 
  -  Khách hàng có thể thanh toán nhiều lần cho đến ngày trả phòng.
 
 5 Quản lý báo cáo: có thể xem và tạo báo cáo: 
  -  Báo cáo thu chi
  -  Báo cáo số lượng khách hàng theo tháng/quý/năm....

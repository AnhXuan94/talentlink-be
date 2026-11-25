# User Stories - RikEdu Portal

## Vai trò 1: Sinh viên (Candidate)

### US-01: Đăng ký tài khoản sinh viên
**Là** sinh viên,  
**tôi muốn** đăng ký tài khoản với email, mật khẩu, họ tên, số điện thoại,  
**để** có thể sử dụng hệ thống tìm kiếm thực tập.

**Tiêu chí chấp nhận:**
- [ ] Form có các trường: họ tên, email, mật khẩu, xác nhận mật khẩu, số điện thoại
- [ ] Email phải có định dạng hợp lệ (có @)
- [ ] Mật khẩu tối thiểu 6 ký tự
- [ ] Hiển thị thông báo lỗi màu đỏ nếu dữ liệu không hợp lệ
- [ ] Sau khi đăng ký thành công, chuyển đến trang đăng nhập

---

### US-02: Đăng nhập
**Là** sinh viên,  
**tôi muốn** đăng nhập bằng email và mật khẩu,  
**để** truy cập hồ sơ và ứng tuyển vị trí thực tập.

**Tiêu chí chấp nhận:**
- [ ] Nhập đúng thông tin → chuyển đến trang chủ
- [ ] Nhập sai → hiển thị thông báo "Email hoặc mật khẩu không đúng"
- [ ] Có link "Quên mật khẩu" và "Đăng ký"

---

### US-03: Xem và chỉnh sửa hồ sơ cá nhân
**Là** sinh viên,  
**tôi muốn** cập nhật hồ sơ (CV, kỹ năng, học vấn),  
**để** nhà tuyển dụng xem được thông tin của tôi.

**Tiêu chí chấp nhận:**
- [ ] Có thể upload file CV định dạng PDF (tối đa 5MB)
- [ ] Có thể sửa họ tên, số điện thoại, mô tả bản thân
- [ ] Nút "Lưu" cập nhật thành công và hiện thông báo

---

### US-04: Tìm kiếm và ứng tuyển vị trí thực tập
**Là** sinh viên,  
**tôi muốn** tìm kiếm vị trí thực tập theo từ khóa và ngành,  
**để** nộp đơn ứng tuyển phù hợp.

**Tiêu chí chấp nhận:**
- [ ] Thanh tìm kiếm theo từ khóa (tên vị trí, công ty)
- [ ] Bộ lọc theo ngành học
- [ ] Nút "Ứng tuyển" gửi hồ sơ cho nhà tuyển dụng
- [ ] Hiển thị thông báo "Đã ứng tuyển thành công"

---

### US-05: Xem trạng thái ứng tuyển
**Là** sinh viên,  
**tôi muốn** xem danh sách các đơn ứng tuyển và trạng thái,  
**để** biết kết quả hồ sơ của mình.

**Tiêu chí chấp nhận:**
- [ ] Hiển thị danh sách với cột: Vị trí, Công ty, Ngày ứng tuyển, Trạng thái
- [ ] Trạng thái gồm: Chờ duyệt (vàng), Đã duyệt (xanh), Từ chối (đỏ)

---

## Vai trò 2: Nhà tuyển dụng (Employer)

### US-06: Đăng ký tài khoản nhà tuyển dụng
**Là** nhà tuyển dụng,  
**tôi muốn** đăng ký tài khoản doanh nghiệp với thông tin công ty,  
**để** có thể đăng tin tuyển dụng sau khi được admin duyệt.

**Tiêu chí chấp nhận:**
- [ ] Form có thêm: tên công ty, mã số thuế, lĩnh vực hoạt động
- [ ] Sau đăng ký, tài khoản ở trạng thái "Chờ duyệt"
- [ ] Hiển thị thông báo "Tài khoản đang chờ admin duyệt"

---

### US-07: Đăng tin tuyển dụng
**Là** nhà tuyển dụng,  
**tôi muốn** đăng tin thực tập với mô tả chi tiết,  
**để** thu hút ứng viên phù hợp.

**Tiêu chí chấp nhận:**
- [ ] Form gồm: tiêu đề, mô tả công việc, yêu cầu, mức lương, thời hạn
- [ ] Sau khi lưu, tin hiển thị công khai trên trang tìm kiếm
- [ ] Có thể xem lại và chỉnh sửa tin đã đăng

---

### US-08: Tìm kiếm ứng viên
**Là** nhà tuyển dụng,  
**tôi muốn** tìm kiếm ứng viên theo kỹ năng và trường học,  
**để** lựa chọn người phù hợp phỏng vấn.

**Tiêu chí chấp nhận:**
- [ ] Tìm theo kỹ năng (Java, Python, Marketing...)
- [ ] Lọc theo trường đại học
- [ ] Hiển thị danh sách card ứng viên với ảnh đại diện, tên, kỹ năng

---

### US-09: Xem chi tiết ứng viên
**Là** nhà tuyển dụng,  
**tôi muốn** xem hồ sơ đầy đủ của ứng viên,  
**để** đánh giá năng lực trước khi mời phỏng vấn.

**Tiêu chí chấp nhận:**
- [ ] Hiển thị: thông tin cá nhân, học vấn, kỹ năng, kinh nghiệm
- [ ] Có nút "Tải CV" để download file PDF
- [ ] Có nút "Mời phỏng vấn"

---

### US-10: Gửi yêu cầu phỏng vấn
**Là** nhà tuyển dụng,  
**tôi muốn** gửi lịch phỏng vấn cho ứng viên,  
**để** mời họ đến phỏng vấn trực tiếp hoặc online.

**Tiêu chí chấp nhận:**
- [ ] Form chọn: ngày giờ, hình thức (online/trực tiếp), địa điểm/link họp
- [ ] Có ô ghi chú thêm
- [ ] Ứng viên nhận được thông báo qua email

---

## Vai trò 3: Admin

### US-11: Quản trị tài khoản người dùng
**Là** admin,  
**tôi muốn** xem danh sách tất cả tài khoản trong hệ thống,  
**để** quản lý và xử lý vi phạm.

**Tiêu chí chấp nhận:**
- [ ] Bảng hiển thị: ID, họ tên, email, vai trò, trạng thái
- [ ] Có nút "Khóa" và "Mở khóa" tài khoản
- [ ] Có nút "Xóa" với hộp thoại xác nhận

---

### US-12: Duyệt tài khoản nhà tuyển dụng
**Là** admin,  
**tôi muốn** duyệt tài khoản NTD đăng ký mới,  
**để** đảm bảo chỉ doanh nghiệp hợp lệ được sử dụng hệ thống.

**Tiêu chí chấp nhận:**
- [ ] Hiển thị danh sách chờ duyệt với thông tin công ty
- [ ] Nút "Duyệt" → tài khoản hoạt động
- [ ] Nút "Từ chối" → gửi email thông báo cho NTD

---

### US-13: Xem hàng chờ duyệt
**Lá** admin,  
**tôi muốn** xem tổng hợp các mục chờ duyệt (tài khoản, tin đăng),  
**để** xử lý công việc kịp thời.

**Tiêu chí chấp nhận:**
- [ ] Dashboard hiển thị số lượng chờ duyệt theo loại
- [ ] Click vào số → chuyển đến danh sách chi tiết

---

### US-14: Quản lý tin đăng
**Là** admin,  
**tôi muốn** xem và xóa tin đăng không phù hợp,  
**để** đảm bảo chất lượng thông tin trên hệ thống.

**Tiêu chí chấp nhận:**
- [ ] Danh sách tất cả tin đăng với nút "Xem" và "Xóa"
- [ ] Khi xóa có hộp thoại "Bạn có chắc chắn muốn xóa?"

---

### US-15: Xem thống kê hệ thống
**Là** admin,  
**tôi muốn** xem dashboard thống kê số liệu,  
**để** báo cáo tình hình hoạt động.

**Tiêu chí chấp nhận:**
- [ ] Hiển thị: tổng số sinh viên, NTD, tin đăng, lượt ứng tuyển
- [ ] Biểu đồ cột hoặc tròn minh họa
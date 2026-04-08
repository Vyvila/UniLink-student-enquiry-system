Các tính năng chính:

Dashboard — Hiển thị KPI tháng 4/2025 thực tế (Resolution Rate, Satisfaction, Escalation…) với thanh gauge trực quan, bảng trạng thái enquiry, và feed hoạt động gần đây
Quản lý Enquiry — Danh sách đầy đủ 8 enquiry mẫu, tìm kiếm/lọc theo trạng thái, xem chi tiết từng enquiry với luồng trao đổi, cập nhật trạng thái, gán cho officer, và theo dõi SLA
Tạo Enquiry mới — Form cho sinh viên điền thông tin, danh mục (Academic, Visa, Financial, Welfare…), gửi và lưu vào hệ thống
Quản lý Appointment — Lịch tháng 3/2026, danh sách appointment sắp tới, form đặt lịch với officer tương ứng
KPI Reports — Bảng tổng hợp hiệu suất đầy đủ kèm khuyến nghị cải thiện
Sơ đồ tổ chức — Toàn bộ cây nhân sự từ Dr. Helen Moore đến các Support Officers
Chính sách dịch vụ — Nội dung policy đầy đủ theo tài liệu gốc
Chatbot UniBot — Hỗ trợ sinh viên tra cứu nhanh, có quick replies
Role Switcher — Chuyển đổi giữa Manager / Admin Officer / Support Officer / Student
UnilinkCode · HTML Downloadko có hệ thống đăng nhập và xác thực à23 thg 3Reading frontend design skill for login UI guidanceReading frontend design skill for login UI guidanceĐể thêm hệ thống đăng nhập đầy đủ với xác thực theo từng vai trò vào file hiện tại.Edited 3 files, viewed 2 filesEdited 3 files, viewed 2 filesNow close the mainApp div and add login JS logic:Edited 2 files, read a fileEdited 2 files, read a fileĐã thêm hệ thống đăng nhập và xác thực đầy đủ! Đây là những gì đã được tích hợp:
Màn hình Login:

Giao diện 2 cột — bên trái giới thiệu hệ thống, bên phải là form đăng nhập
Hiệu ứng fade-out mượt khi chuyển vào app

Xác thực theo vai trò (Role-Based Access):
Vai tròEmailMật khẩu🎓 Studentvanan@abc.edu.austudent123📋 Admin Officerlily.tran@abc.edu.auadmin123🧑‍💼 Support Officersarah.chen@abc.edu.auofficer123👩‍💼 Managerkaren.thompson@abc.edu.aupassword123
Quick Role Cards — click vào card để tự điền thông tin đăng nhập tương ứng
Phân quyền sau đăng nhập:

Student — chỉ thấy New Enquiry, Enquiries, Appointments, Chatbot
Officer — không thấy KPI Reports
Manager/Admin — toàn quyền truy cập

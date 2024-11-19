# API Routes

## Routers
- **authRouter.js**: Quản lý xác thực (đăng nhập, đăng ký, đổi mật khẩu) (Chưa tách)
- **userRouter.js**: Quản lý người dùng (profile, lịch sử đặt vé)
- **categoryRouter.js**: Quản lý thể loại phim
- **foodDrinkRouter.js**: Quản lý đồ ăn/uống
- **movieRouter.js**: Quản lý phim
- **promotionRouter.js**: Quản lý chương trình khuyến mãi
- **ticketBookingRouter.js**: Đặt vé xem phim
- **bookingRouter.js**: Lịch sử đặt vé của tất cả người dùng (Admin)
- **reviewRouter.js**: Quản lý đánh giá phim
- **showtimeRouter.js**: Quản lý suất chiếu phim
- **paymentRouter.js**: Quản lý thanh toán
- **trailerRouter.js**: Xem trailer phim

## Controllers
- **AuthController.js**: Quản lý xác thực (Đăng nhập, Đăng ký, Đổi mật khẩu, Quên mật khẩu, Đăng xuất)
- **UserController.js**: Quản lý người dùng (Hiển thị, chỉnh sửa Profile, Lịch sử đặt vé)
- **CategoryController.js**: Quản lý thể loại phim (Thêm, Sửa, Xóa, Hiển thị, Tìm kiếm theo từ khóa)
- **FoodDrinkController.js**: Quản lý đồ ăn/uống (Thêm, Sửa, Xóa, Hiển thị, Tìm kiếm theo từ khóa)
- **MovieController.js**: Quản lý phim (Thêm, Sửa, Xóa, Hiển thị, Tìm kiếm theo từ khóa hoặc thể loại)
- **PromotionController.js**: Quản lý chương trình khuyến mãi (Thêm, Sửa, Xóa, Hiển thị)
- **TicketBookingController.js**: Đặt vé xem phim (Chọn giờ chiếu, phòng chiếu, số lượng vé, ghế, đồ ăn/uống)
- **BookingController.js**: Lịch sử đặt vé (Admin) (Xem, Tìm kiếm theo ID hoặc QR Code)
- **ReviewController.js**: Quản lý đánh giá phim (Thêm, Sửa, Xóa, Hiển thị review)
- **ShowtimeController.js**: Quản lý suất chiếu phim (Thêm, Sửa, Xóa, Hiển thị danh sách giờ chiếu)
- **PaymentController.js**: Quản lý thanh toán (Thanh toán qua ví điện tử, ngân hàng)
- **TrailerController.js**: Xem trailer phim


## Thành viên

| STT | Họ và tên | ID | Task|
|---|---|---| --- |
| 1 | Nguyễn Ngọc Hoàng Thắng | AoiSyShiro, SoraNega | Server API - UI, Thuật toán Server, Movie Trailer, QR, Khuyến Mãi, DEV Server
| 2 | Trần Văn Cường | | Hiển Thị Phim, Thông Tin Phim, Thêm Sửa Xoá, Tìm Kiếm Phim
| 3 | Võ Minh Huy | | Hiển Thị Thuật Toán Phim Khác, Thêm Yêu Thích Phim,
| 4 | Nguyễn Nam Hà Thành | milkypig-code |  Thanh Toán, Lịch Sử, Lịch Sử Đặt Vé
| 5 | Tuấn Ngọc | | Tạo Xuất Chiếu, Sửa, Xoá Xuất Chiếu, Food, Thêm Sửa Xoá
| 6 | Khánh| lekhanh1234| UI, User Đăng Ký, Đăng Nhập, Quên Mật Khẩu, Cập Nhật Thông Tin


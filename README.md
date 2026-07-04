# Shopee Seeding Bot

Shopee Seeding Bot là công cụ desktop Windows hỗ trợ quét bài trong Facebook Group, nhận diện nhu cầu mua hàng bằng AI, tìm sản phẩm Shopee phù hợp, tạo link affiliate và hỗ trợ comment tự động hoặc gửi bài qua Telegram để xử lý thủ công.

Tool phù hợp cho người làm affiliate Shopee, vận hành seeding group, quản lý nhiều group Facebook hoặc muốn theo dõi hiệu quả comment, link và đơn hàng theo từng nhóm.

## Tool này làm gì?

Shopee Seeding Bot giúp tự động hóa quy trình:

1. Quét bài viết mới trong các Facebook Group đã cấu hình.
2. Lọc bài có dấu hiệu đang hỏi mua, tìm sản phẩm hoặc cần gợi ý.
3. Dùng AI phân tích nội dung bài viết để xác định nhu cầu mua hàng.
4. Tìm sản phẩm phù hợp từ kho sản phẩm hoặc Shopee.
5. Tạo link affiliate Shopee theo từng group.
6. Sinh nội dung comment tiếng Việt tự nhiên.
7. Comment trực tiếp trên Facebook hoặc gửi về Telegram để người dùng duyệt và comment thủ công.
8. Lưu lịch sử comment, trạng thái xử lý và hiệu quả chạy theo từng group/tài khoản.

## Tính năng chính

### Quét và phân tích bài Facebook Group

- Quét nhiều Facebook Group đã lưu.
- Hỗ trợ bật/tắt từng group.
- Hỗ trợ chạy tất cả group, chạy group được chọn hoặc chạy theo cụm group.
- Lọc bài theo keyword mua hàng.
- Dùng AI để nhận diện bài có nhu cầu mua thật.
- Lưu lịch sử bài đã xử lý để tránh comment trùng.

### Tạo comment bán hàng tự nhiên

- AI tạo comment tiếng Việt phù hợp với nội dung bài viết.
- Comment có thể kèm link affiliate Shopee.
- Hạn chế kiểu viết quá quảng cáo hoặc máy móc.
- Có thể xử lý theo chế độ tự động hoặc gửi Telegram để duyệt thủ công.

### Quản lý sản phẩm và link affiliate

- Lưu kho sản phẩm để tái sử dụng.
- Tìm sản phẩm Shopee theo nhu cầu trong bài viết.
- Tạo link affiliate Shopee.
- Hỗ trợ SubID theo từng group để dễ theo dõi hiệu quả.
- Hỗ trợ rút gọn link bằng TinyURL hoặc Muahangre.

### Điều khiển bot qua Telegram

- Mở menu chạy bot từ Telegram.
- Chạy tất cả group đang bật.
- Chạy một hoặc nhiều group được chọn.
- Chạy theo cụm group.
- Tạm dừng, tiếp tục hoặc dừng bot từ xa.
- Xem trạng thái bot đang chạy.
- Nhận bài/comment để xử lý thủ công.
- Nhận thông báo khi comment gặp lỗi, chờ duyệt hoặc bị từ chối.

### Đổi tài khoản Facebook và fanpage/profile

- Đổi tài khoản Facebook đã lưu ngay trong Telegram.
- Đổi nhanh fanpage/profile đang sử dụng.
- Xem tài khoản hoặc profile hiện tại.
- Hỗ trợ trường hợp Facebook đang mở nhiều tab hoặc đang ở màn chọn tài khoản.

### Theo dõi trạng thái và lịch sử

- Lưu lịch sử comment.
- Theo dõi trạng thái: đã comment, gửi Telegram, chờ xử lý, bị từ chối, lỗi Facebook, lỗi link.
- Xem group nào đang chạy, group nào bị tạm dừng.
- Ghi nhận tài khoản Facebook đang dùng tại thời điểm chạy.

### Thống kê doanh thu Shopee Affiliate

- Đồng bộ dữ liệu click/order Shopee Affiliate nếu đã cấu hình.
- Theo dõi hiệu quả theo SubID.
- Hỗ trợ xem doanh thu, đơn hàng và hiệu suất theo nguồn.

## Các lệnh Telegram thường dùng

```text
/run
/run all
/run group 1,2
/run cụm 3
/pause
/resume
/stop
/connect
/status
/account
/page
/switch
/addaccount
/removeaccount
/logoutfb
/help
```

Menu nhanh dưới ô nhập Telegram hiện có các lựa chọn chính:

```text
Chạy
Đổi tài khoản
Trợ giúp
```

## Yêu cầu sử dụng

- Máy Windows.
- Trình duyệt Edge hoặc Chrome.
- Tài khoản Facebook đã đăng nhập trên trình duyệt.
- Bot Telegram nếu muốn điều khiển từ xa.
- Cấu hình Shopee Affiliate nếu muốn tạo link affiliate.
- API AI hoặc cấu hình AI tương ứng nếu dùng phân tích/comment tự động.

## Cách bắt đầu

1. Tải bản mới nhất trong mục Releases.
2. Giải nén và mở ứng dụng.
3. Kết nối trình duyệt Edge hoặc Chrome.
4. Cấu hình tài khoản, group Facebook, Shopee Affiliate và AI.
5. Thêm group hoặc cụm group cần chạy.
6. Chạy bot từ app hoặc Telegram.

## Lưu ý an toàn

- Không chia sẻ file cấu hình có chứa token, cookie, API key hoặc thông tin đăng nhập.
- Nên chạy với tốc độ hợp lý để tránh Facebook giới hạn thao tác.
- Nội dung comment nên được kiểm tra định kỳ để đảm bảo phù hợp với group.
- Tool hỗ trợ tự động hóa thao tác, người dùng chịu trách nhiệm với cách sử dụng trên tài khoản và group của mình.

## Mục đích phát hành

Repo release này dùng để phân phối bản build của Shopee Seeding Bot cho người dùng cuối.
Người dùng có thể vào mục Releases để tải phiên bản mới nhất và xem ghi chú cập nhật của từng bản.

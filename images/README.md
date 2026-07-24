# Ảnh cho các điểm đến

Trang web tự chọn ảnh theo thứ tự ưu tiên cho **mỗi điểm**:

1. **Ảnh của bạn** — file `images/<slug>.jpg` (nếu có) → luôn được ưu tiên.
2. **Ảnh Wikimedia** — với các điểm nổi tiếng đã gắn sẵn.
3. **Gradient** — nếu cả hai trên đều không có.

## Cách thêm ảnh của bạn

Chỉ cần bỏ ảnh vào thư mục này, **đặt đúng tên file** theo cột "Tên file" bên dưới (đuôi `.jpg`), rồi:

```bash
git add images/
git commit -m "Thêm ảnh chuyến đi"
git push
```

Trang sẽ tự hiển thị ảnh của bạn thay cho ảnh mặc định (đợi ~1 phút GitHub build). Ảnh nên nằm ngang, tỉ lệ ~4:3 hoặc 16:9, dung lượng < 1MB để tải nhanh.

## Danh sách tên file

| Điểm | Tên file | Ảnh sẵn |
|---|---|:--:|
| Biển Mỹ Khê | `bien-my-khe.jpg` | ✅ Wikimedia |
| Sơn Trà Marina | `son-tra-marina.jpg` | gradient |
| Chùa Linh Ứng Sơn Trà | `chua-linh-ung-son-tra.jpg` | ✅ Wikimedia |
| Đỉnh Bàn Cờ | `dinh-ban-co.jpg` | gradient |
| Cầu Rồng | `cau-rong.jpg` | ✅ Wikimedia |
| Chợ đêm Sơn Trà | `cho-dem-son-tra.jpg` | gradient |
| Rừng dừa Bảy Mẫu | `rung-dua-bay-mau.jpg` | gradient |
| Cơm gà & Bánh mì Phượng | `com-ga-banh-mi-phuong.jpg` | ✅ Wikimedia |
| Chùa Cầu & Hội quán | `chua-cau-hoi-quan.jpg` | ✅ Wikimedia |
| Faifo Rooftop | `faifo-rooftop.jpg` | gradient |
| Đèn lồng & Hoa đăng sông Hoài | `den-long-hoa-dang-song-hoai.jpg` | ✅ Wikimedia |
| Cano ra đảo | `cano-ra-dao.jpg` | ✅ Wikimedia |
| Lặn ngắm san hô | `lan-ngam-san-ho.jpg` | gradient |
| Bãi Chồng & Chợ Tân Hiệp | `bai-chong-cho-tan-hiep.jpg` | gradient |
| Hải sản tươi | `hai-san-tuoi.jpg` | gradient |
| Cầu Vàng | `cau-vang.jpg` | ✅ Wikimedia |
| Vườn hoa Le Jardin | `vuon-hoa-le-jardin.jpg` | gradient |
| Hầm rượu Debay | `ham-ruou-debay.jpg` | gradient |
| Làng Pháp & Fantasy Park | `lang-phap-fantasy-park.jpg` | gradient |

> Mẹo: muốn dùng ảnh đuôi `.png`/`.jpeg`? Cứ đổi tên thành `.jpg` là được (trình duyệt vẫn đọc theo nội dung).

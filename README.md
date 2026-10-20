# Dota 2 Coaching

Trợ lý Dota 2 tiếng Việt cho Windows: chọn tướng, lên đồ, item rừng, nhắc mốc giờ và cảnh báo ngay trong trận — chạy cạnh game, không chạm vào tiến trình game.

> Bản hiện tại: **0.3.0** · Dữ liệu game: **Dota 2 bản 7.41f (build 6964, 19/10/2026)**

## Tải về
Vào [**Releases**](https://github.com/ktruong-afk/tqk-dota2-coaching/releases/latest) → tải `tqk-dota2-coaching-setup-<phiên bản>.exe` → mở để cài (không cần quyền quản trị).

Windows có thể báo *"Windows protected your PC"* vì bộ cài chưa có chữ ký số: bấm **More info → Run anyway**.

## Làm được gì
- **Hot pick theo chế độ** (Turbo / Rank theo bậc) và **Draft**: counter, combo với đồng đội.
- **Lên đồ** theo độ phổ biến; rê chuột vào món để xem **mô tả chính thức của Valve với số của bản hiện tại**.
- **Item rừng**: mỗi tier mở lúc nào, các artifact có thể ra, enchantment có thể ra **theo thuộc tính chính của tướng anh**, chỉ số đúng cấp ở từng tier.
- **Trong trận** (qua Game State Integration chính thức của Valve):
  - Nhắc mốc giờ: Bounty, Power, Water rune, Shrine of Wisdom, Lotus, ngày / đêm, Tormentor, giờ mở item rừng.
  - Cảnh báo **THOÁT** khi bị dí / bị khống chế, kèm phím combo thoát thân.
  - Tips theo tướng và trình độ, mẹo đi lane, combo.
- **HUD tuỳ chỉnh**: hub mini + 3 bảng chữ trong suốt (trên / dưới / trái), mỗi loại thông báo gán vào đúng một chỗ, chỉnh độ trong suốt, kéo sang màn hình phụ. Phím **Ctrl+Shift+L** để sắp xếp vị trí.

## Kết nối với Dota 2
1. Mở app → **Cấu hình HUD** → **Kết nối Dota 2 (GSI)** → bấm **Cài / cập nhật kết nối**.
2. Steam → Dota 2 → Properties → Launch Options: thêm `-gamestateintegration`.
3. Dota để **Display Mode: Borderless Window** để HUD nổi trên game.

App chỉ nhận dữ liệu Valve cho phép gửi qua Game State Integration; **không đọc bộ nhớ game, không can thiệp vào game**.

## Cập nhật
App tự kiểm tra bản mới trên trang Releases này (lúc mở app và mỗi 6 giờ, **không bao giờ lúc đang trong trận**). Có bản mới → **Cấu hình HUD → Cập nhật → Tải về → Cài ngay**. Mỗi khi Dota 2 ra bản vá, bản mới của app mang theo dữ liệu game của bản vá đó.

## Dữ liệu lấy từ đâu — và vì sao tin được
Nguyên tắc: **không chắc thì không nhắc**.
- **Số liệu game** (tướng, kỹ năng, item, item rừng, chu kỳ rune / lotus / tormentor…): lấy từ **file game của chính bản Dota mới nhất** (qua dự án [SteamTracking/GameTracking-Dota2](https://github.com/SteamTracking/GameTracking-Dota2)), không chép tay.
- **Kiểm chứng bằng trận thật**: mốc giờ được đối chiếu với các trận đã phân tích trên [OpenDota](https://www.opendota.com) của đúng bản vá (vd Bounty rune 4 phút — đổi từ 7.39 dù patch notes không ghi).
- **Turbo**: chỉ nhắc những mốc đã kiểm đủ trận Turbo; chưa đủ thì không nhắc.
- **Tỉ lệ thắng / lên đồ phổ biến**: [OpenDota](https://www.opendota.com) và [STRATZ](https://stratz.com).
- **Tips theo tướng**: dịch và rút gọn từ [Dota 2 Wiki](https://dota2.fandom.com) — giấy phép [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/); một số tướng mới tự soạn theo dữ liệu kỹ năng.

## Lịch sử phiên bản
### 0.3.0 — 20/10/2026
- Dữ liệu game 7.41f lấy từ file game; mốc giờ sinh tự động và kiểm chứng bằng trận thật (Bounty 4 phút, Shrine of Wisdom thay Wisdom rune, Tormentor 20:00, Water rune 2:00).
- Item rừng theo file game: giờ mở tier, artifact, enchantment theo thuộc tính, chỉ số đúng cấp.
- Mô tả item chính thức của Valve với số của bản hiện tại.
- Tips theo tướng × trình độ; luồng thông báo chặt (mỗi loại đúng một vị trí); HUD co giãn theo tỉ lệ màn hình; Ctrl+Shift+L.
- Kết nối Dota (GSI) và cập nhật ngay trong app.

---
Dota 2 là thương hiệu của Valve Corporation. App không liên kết với Valve.

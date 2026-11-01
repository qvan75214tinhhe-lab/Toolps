# PokeSurvivor Bot

**Tiếng Việt** · [English](README.en.md)

Bot tự chơi [pokesurvivor.com](https://pokesurvivor.com/) và [pokesurvivor.doofcraft.com](https://pokesurvivor.doofcraft.com/) (tự nhận bản game theo trang). Có phí, giá rẻ ([cách mua](#mua-mã-kích-hoạt)) · tác giả [damhieu2808](https://github.com/damhieu2808)

## Cài trên máy tính (Chrome)

1. [**Tải bot (ZIP)**](https://github.com/damhieu2808/PokeSurvivorTool/archive/refs/heads/main.zip). Link này luôn tải bản mới nhất.
2. Giải nén, mở `chrome://extensions`, bật **Developer mode**.
3. Bấm **Load unpacked**, chọn thư mục vừa giải nén.

## Cài trên điện thoại (Android)

> ℹ️ Toàn bộ bot nằm sẵn trong file userscript. Trình quản lý userscript tự chạy code đó trong trang, nên việc pokesurvivor.com chặn script chèn vào trang (CSP) không còn ảnh hưởng. Khuyên dùng **Firefox**. Edge / Kiwi + Tampermonkey trên Android từng không chạy được với bản cũ; với cách mới thì chưa thử lại.

1. Cài **Firefox** (CH Play).
2. Trong Firefox, cài tiện ích **Violentmonkey** hoặc **Tampermonkey** (menu ⋮ → Tiện ích / Add-ons).
3. Bấm nút copy ở góc khối dưới đây, dán vào **thanh địa chỉ** của trình duyệt đó rồi mở:

```
https://raw.githubusercontent.com/damhieu2808/PokeSurvivorTool/v2.2.1/psbot.user.js
```

4. Trình quản lý tự mở trang cài script → bấm **Install** (Cài đặt). Đã cài bản cũ thì cài đè lên.
5. Vào game: panel **PokeSurvivor Bot** hiện ở góc trên bên trái.

Trình quản lý tự kiểm tra bản mới định kỳ. Muốn cập nhật ngay: mở trình quản lý → **Check for updates** (Kiểm tra cập nhật), hoặc mở lại link ở bước 3.

## Cài trên iPhone / iPad

1. Cài app **Userscripts** (App Store, miễn phí).
2. Mở **Cài đặt → Safari → Tiện ích → Userscripts**: bật lên và cho phép trên mọi trang web.
3. Trong **Safari**, dán link ở bước 3 phần Android vào thanh địa chỉ rồi mở.
4. Bấm biểu tượng tiện ích (hình mảnh ghép hoặc **aA**) trên thanh địa chỉ → **Userscripts** → **Cài đặt** (Install).
5. Vào game trong Safari: panel hiện ở góc trên bên trái. iOS chưa thử; pokesurvivor.com có thể bị chặn như trên Android. Nếu lỗi, báo qua liên hệ bên dưới.

## Mua mã kích hoạt

Bot cần **mã kích hoạt** còn hạn để chạy. Panel, Moveset, Level-up, Item vẫn mở được khi chưa có mã.

| Gói | Giá |
|---|---|
| 10 ngày | 30k |
| 30 ngày | 70k |
| 90 ngày | 180k |
| Vĩnh viễn | 500k |

Gói vĩnh viễn: 1 máy, dùng tới khi tool còn hoạt động.

⚠ Hạn dùng tính tới khi game chưa chặn tool. Nếu game chặn, mình sẽ tìm mọi cách cho tool chạy lại; thử hết cách vẫn không được thì không hoàn tiền.

**Dùng thử miễn phí 2 giờ:** nhắn [Zalo 0355011166](https://zalo.me/0355011166) mã máy của bạn (bước 1 bên dưới). Cần bot từ bản 2.0.7.

1. Cài bot, vào game. Panel hiện **🔒 Cần mã kích hoạt** và **mã máy** (dạng `ABCD-1234`), bấm **Copy**.
2. Chuyển khoản (tab **💳 Mua mã** trên panel có QR và số tài khoản), nội dung ghi mã máy.
3. Nhắn [Zalo 0355011166 (Đàm Xuân Hiếu)](https://zalo.me/0355011166) hoặc [TikTok @phuongnguyenconhat](https://www.tiktok.com/@phuongnguyenconhat) ảnh chuyển khoản + mã máy.
4. Nhận mã (bắt đầu bằng `PSB1.`), dán vào ô trên panel → **Nhập** → **▶ Chạy**.

- Gia hạn trước khi hết hạn: ngày mới được cộng nối tiếp, không mất ngày. Bấm **Gia hạn** trên panel để nhập mã mới.
- Mỗi trình duyệt và mỗi trang game (pokesurvivor.com / doofcraft) có mã máy riêng. Chơi cả 2 trang thì gửi cả 2 mã máy, tác giả làm 1 mã dùng chung.
- Xoá dữ liệu trình duyệt (cookie / dữ liệu trang) sẽ đổi mã máy: nhắn tác giả để được cấp lại, không mất ngày.
- Game cập nhật làm bot hỏng: tác giả bù ngày cho thời gian bot không chạy được.

## Dùng

Nhập **Số ván** (0 = chơi mãi) rồi bấm **▶ Chạy**, bấm lại để **■ Dừng**. **⚔ Moveset** để chọn 4 move bot ưu tiên cho từng pokémon, thêm 2 move dự phòng (#5, #6: bot chỉ lấy khi move chính chưa ra mà sắp hết ô). **⬆ Level-up** để xem / đổi thứ tự bot chọn thẻ khi lên cấp, **🎒 Item** để đổi thứ tự đồ cầm. Danh sách move lấy theo đúng từng bản game, có thêm các move TM pokémon đó học được (pokesurvivor.com: Kecleon Shop; doofcraft: Poké Mart): "TM ✓" là đã dạy, "TM" là chưa dạy (game chỉ đưa thẻ TM đã dạy). Phím tắt trên máy tính: **F8** bật/tắt bot, **F9** hiện lớp vẽ (bot đang thấy gì).

**VI | EN** (dưới tiêu đề panel, cạnh "by damhieu2808"): đổi panel và các popup sang tiếng Anh cho người chơi nước ngoài, bấm lại để về tiếng Việt (mặc định). Lưu trên trình duyệt.

**Màn hình nhỏ** (điện thoại, nhất là khi xoay ngang): panel gọn hơn, lần đầu thu gọn sẵn thành một dòng tiêu đề có nút **▶ / ■** để chạy / dừng; bấm **+** để mở ra. Popup Moveset nằm cạnh panel thay vì bên dưới.

**Không gửi bảng xếp hạng** (pokesurvivor.com, bật sẵn): ván do bot chơi không được gửi lên bảng xếp hạng. Ván bạn tự chơi (bot tắt) vẫn được gửi. Muốn ván của bot lên bảng thì bỏ tick ô này trên panel.

**Auto skill** (bật sẵn): bot liên tục đổi skill (phím E) để dùng hết các move. Bỏ tick thì bot không đổi skill nữa, bạn tự đổi bằng tay.

**Lưu game sau mỗi ván:** trên pokesurvivor.com, hết ván bot về menu, bấm **Guardar** và đợi game báo đã lưu lên cloud rồi mới chơi ván tiếp (đợi tối đa 1 phút). Doofcraft tự lưu lên server khi hết ván nên bot không cần bấm gì.

**Chế độ chơi** ([pokesurvivor.doofcraft.com](https://pokesurvivor.doofcraft.com/)): 3 ô chọn trên panel, giống màn Solo của game.
- **Chế độ:** Normal (chơi tới khi chết) / Waves (các vòng liên tiếp, rương giữa vòng, boss mỗi 25 vòng).
- **Độ khó:** Easy / Medium / Hard.
- **HYPER:** Tắt / Bật (mọi thứ mạnh lên nhanh gấp đôi, Eternatus ở 30:00, ×1,5 xu, bảng xếp hạng riêng; nên dùng pokémon đã nâng max). Đi kèm được với mọi chế độ và độ khó.

Mỗi ô có **Game** = giữ nguyên lựa chọn đang có trong game. Trước mỗi ván, bot bấm các tab trên màn Solo cho khớp rồi mới bấm Play. Nếu đang có ván lưu dở khác chế độ đã chọn, bot không tự chơi tiếp hay bỏ ván đó mà dừng, báo trên panel và hiện 2 nút: **▶ Chơi tiếp ván lưu** (đổi 3 ô cho khớp ván đó rồi chạy) hoặc **✕ Bỏ ván lưu** (bấm End run, mất ván đó, rồi chạy đúng chế độ đã chọn).

**Lái** (doofcraft, từ 2.0.7): **Kéo quái** (mặc định: né cả bầy, tránh góc chật, kéo quái chạy vòng, giống cách bot đi trên pokesurvivor.com) hoặc **Cũ** (cách đi trước 2.0.7).

Nếu tài khoản đang mở ở tab / máy khác (game báo "The game was opened in another tab or device"), bot dừng và báo trên panel, không tự vào ván mới (vào ván mới sẽ đóng ván đang chơi bên kia). Thoát game bên kia rồi bấm **↻ Tải lại trang**.

> ⚠️ **Bot 1.5.0–1.5.6 chuyển pokesurvivor.com sang `/dev.html`.** Từ 26/10, trang này của game không còn dùng tài khoản (không lưu lên cloud, không lên bảng xếp hạng). Từ bản 1.5.7, bot đưa bạn về trang chính. Nếu thấy địa chỉ là `pokesurvivor.com/dev.html`, hãy cập nhật bot rồi mở lại `pokesurvivor.com`.

### Bot chọn thẻ lên cấp thế nào

Mỗi lần lên cấp, bot chấm điểm từng thẻ rồi chọn thẻ điểm cao nhất. Lý do mỗi lần chọn hiện trong console (F12), ví dụ `chọn 2 Psychic — lấy move build #2`.

Thứ tự giống [pokesurvivor-autofarm](https://github.com/BoundlessEgret/pokesurvivor-autofarm) (MIT), áp dụng cho cả 2 bản. **Build** là Moveset của pokémon đang chơi: bot nhận ra pokémon qua tên trên HUD, hoặc pokémon partner trong save nếu đang ở menu. Popup tự đổi theo pokémon đang chơi: khi đã nhận ra pokémon, popup chỉ hiện tên trên tiêu đề và các ô move. Bấm ✎ để sửa build của pokémon khác (gõ tên); bấm 🎯 để quay lại theo pokémon đang chơi. Có sẵn build của tool đó cho 3 pokémon (đều nên cầm Shell Bell):
- **Mewtwo:** Confusion → Harden → Nasty Plot → Psychic.
- **Kyogre:** Bubble → Nasty Plot → Aqua Ring → Hydro Pump.
- **Bulbasaur:** Energy Ball → Nasty Plot → Petal Blizzard → Grass Knot (mua "Starting move" Energy Ball trong shop).

Pokémon khác chưa có Moveset thì dùng **build mặc định 3 move**: move khởi đầu (★) → buff tấn công đúng phía (Nasty Plot nếu Sp.Atk cao hơn, Swords Dance / Dragon Dance nếu Atk cao hơn) → Harden. Ô thứ 4 để bạn tự chỉnh; nếu bạn chưa lưu build thì bot tự lấp ô đó trong trận (move sát thương hợp chỉ số, đạn tự ngắm trước). Popup Moveset hiện build mặc định này; sửa rồi bấm **Lưu** thì bot theo build của bạn.

Danh sách move trong popup: pokesurvivor.com lấy **từ game** (đúng move khởi đầu đã mua, TM đã dạy / chưa dạy, tên theo ngôn ngữ game) khi bot đọc được game, không thì dùng bản lưu từ lần gần nhất đọc được game (hoặc bảng có sẵn, cũng xuất từ game); doofcraft đọc từ cấu hình game. Không dùng wiki. Phía tấn công lấy từ chỉ số trong game; không đọc được thì theo move khởi đầu.

Tầng trên luôn thắng tầng dưới. Đây là thứ tự mặc định; bấm **⬆ Level-up** trên panel để đổi (↑ ↓ từng dòng, kể cả dòng reroll; lưu trên trình duyệt, **Mặc định** để trả lại). Mỗi bản game có danh sách và thứ tự riêng: doofcraft có thêm Mega / đổi dạng (thẻ Unique, ngay dưới tiến hoá), Z-move, Revive, Focus / Sniper:

1. Thẻ **tiến hoá** một skill.
2. Nội tại **lấy là tiến hoá ngay** một move đã max (thẻ vàng; pokesurvivor.com).
3. **Sitrus Berry / Baya Zidra** (hồi 45% máu) khi **máu dưới 35%**. Máu khoẻ thì gần cuối (sau mục 8).
4. **Lấy move trong build** chưa có (#1 trước #2…). Move dự phòng #5, #6 xếp sau, chỉ lấy khi còn ô dư cho các move chính chưa có, hoặc là ô cuối cùng (move chính chưa ra thì ô đó không bị bỏ trống). Không có build: move mới khi còn ô, theo thứ tự tự chọn ở trên.
5. **Nội tại mà move đang có cần để tiến hoá** (ví dụ Magnet cho Psychic), khi chưa lấy nội tại đó. Đứng trên mọi nâng cấp move.
6. **Nâng cấp move trong build** (#1 trước #2…), move buff cũng như move tấn công: các move của Moveset được max trước move khác.
7. **Nâng cấp move ngoài build còn tiến hoá được**: càng gần max càng gấp. Chỉ khi dùng build mặc định (chưa lưu Moveset); đã lưu Moveset thì loại thẻ này xuống ngay dưới mục 8, để bot không nâng move khởi đầu hay move lấy thêm thay cho nội tại.
8. **Nội tại**: **giáp** (Armor / Coraza) trước tiên cho tới khi đầy (pokesurvivor.com: -6% sát thương mỗi thẻ, tới 70%; doofcraft: 20 thẻ, khoảng 67%). Sau đó: Power > Reflexes > (Focus / Sniper, doofcraft) > Vigor > Synthesis > Learning > Magnet > Sprint.
9. **Nâng cấp move ngoài build không tiến hoá được**.
10. **Move mới ngoài build** khi còn ô thừa (ô của các move build chưa có luôn được giữ lại).
11. Skill mới khi đã hết ô: chỉ lấy khi không còn gì khác.

**Z-move** (pokesurvivor.doofcraft.com, thẻ "Firium Z", "Psychium Z"… có nhãn Z-Move, từ phút 15, vòng 10 ở Waves, phút 7:30 ở Hyper): xếp giữa mục 5 và 6. Đã có Z-move thì bot bấm **F** khi có từ 8 quái trong tầm nổ (400), hoặc từ 3 quái khi máu thấp; nổ xong phải chờ 120 giây.

Nếu không có thẻ nào thuộc mục 1–7 và còn lượt **Reroll** thì bot đổi thẻ (máy tính; pokesurvivor.com thì cả điện thoại).

Số ô move: bản thường đọc từ game (thường 4, nâng cấp được), pokesurvivor.doofcraft.com tính là 4. Các move đã **bond** chỉ chiếm chung 1 ô, nên sau khi bond bot lại lấy thêm move mới. Game chỉ đưa thẻ move mới khi còn ô trống, nên thấy thẻ đó là bot biết còn chỗ.

**Đồ cầm** (cả 2 bản), mặc định xếp cho sống lâu: Shell Bell > Leftovers > Quick Claw > Focus Sash > Assault Vest > (doofcraft: Wise Glasses > Scope Lens > Muscle Band) > Rocky Helmet > Lucky Egg > Amulet Coin > Choice Scarf > Life Orb > Choice Band (luôn bỏ khi có món khác). Bấm **🎒 Item** trên panel để đổi (↑ ↓, cả dòng "bỏ"; mỗi bản game một danh sách và thứ tự riêng). Đá Mega của doofcraft không phải đồ cầm: tiến hoá Mega là thẻ lên cấp "Unique" (dòng riêng trong ⬆ Level-up).

### Cách bot chơi trên pokesurvivor.com

Bot đọc trạng thái thật của game thay vì nhìn màn hình. Cách lái dựa trên [pokesurvivor-autofarm](https://github.com/BoundlessEgret/pokesurvivor-autofarm) (MIT):
- **Né:** chấm 16 hướng, dự đoán quái đuổi tới đâu và vùng skill nổ lúc nào (lúc nó nổ mình đứng ở đâu). Máu càng thấp càng sợ quái thường; boss, đạn, vùng skill thì luôn né.
- **Mục tiêu:** Gholdengo > rift > cứu pokémon lạc / Meowth > buff, hồ hồi máu (máu < 60%), rương lớn > nhặt đồ. Đường đi tính bằng A* trên địa hình thật; không tới kịp trước khi mục tiêu biến mất thì bỏ.
- Đứng chỗ bắn không bị tường / cây chặn. Quái đông thì chạy vòng tròn lớn, kéo quái theo sau.
- **Rift** và **Arceus** (phút 30): chạy vòng trong sân, giữ boss ở phía đối diện.
- **Orb** (4 ô, phím 5–8, mỗi ô tối đa 3): orb khống chế (Slumber / Slow / Blowback) khi máu dưới 50% hoặc có 6 quái quanh người; Quick khi máu dưới 50% để chạy; orb buff khi có boss. Ô nào đủ 3 thì dùng bớt khi đang đánh nhau (Luminous: bất cứ lúc nào) để còn nhặt orb mới.
- **Bond** (ghép move vào 1 ô): move build trước theo thứ tự build, rồi move cấp cao hơn.
- **Auto skill tắt:** bot giữ đúng ô move bạn chọn; game tự đổi ô (vd sau Rift) thì bot đổi lại.
- Game tự pause khi mất focus thì bot tự chơi tiếp (trừ khi bạn tự bấm Esc / P).
- **Gợi ý pokémon** (ở menu / màn kết thúc trận): 3 pokémon bạn đang có mạnh nhất khi treo máy, và pokémon đang dùng có nên đổi không. Điểm tính theo công thức sát thương của game: move tự ngắm tốt nhất × chỉ số tấn công hợp move × cùng hệ (×1,2) × thời tiết tự tạo (Kyogre có mưa: ×1,5 hệ Nước) × độ trâu × tốc độ × nâng cấp đã mua. Bot không tự đổi, bạn tự chọn.

Không có trạng thái game (bookmarklet, doofcraft) thì bot dùng cách cũ: đọc màn hình.

## Cập nhật

- **Máy tính:** khi panel hiện dòng vàng "⬆ Có bản mới", tải lại ZIP ở bước 1 rồi giải nén đè lên thư mục cũ.
- **Điện thoại:** trình quản lý userscript tự cập nhật định kỳ (hoặc bấm **Check for updates**).

Cần cài hộ: liên hệ [Zalo 0355011166](https://zalo.me/0355011166) hoặc [TikTok @phuongnguyenconhat](https://www.tiktok.com/@phuongnguyenconhat) · [Giấy phép](LICENSE)

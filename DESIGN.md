# DESIGN.md --- Thái Ất Thần Quẻ

> Tài liệu định hướng hình ảnh và giao diện cho ứng dụng tử vi, tướng số
> và thuật số phương Đông.\
> Phạm vi: **visual design, bố cục và danh mục ảnh**. Không mô tả logic
> code hoặc đặc tả chi tiết nghiệp vụ.

Requirements: thiết kế hình ảnh nền, họa tiết trang trí, bảng màu, bố cục
    - Images: 
        ./images/demo_giao_dien_toan_app.png (demo giao diện toàn app)
        ./images/app_home_menu.png (demo giao diện trang chủ)
        ./images/app_bg_1.png (demo ảnh nền màn hình)
        ./images/app_bg_2.png (demo ảnh nền màn hình)
    - Font: UTM ThuPhap Thien An
        ./fonts/UTM ThuPhap Thien An/UTM ThuPhap Thien An.ttf
    - Logo: ./images/logo_app.png
## 1. Định hướng mỹ thuật

### Chủ đề

-   Lấy cảm hứng từ văn hóa phương Đông: Thái Ất, Bát Quái, Âm Dương,
    thiên văn cổ, sơn thủy họa và kiến trúc cổ.
-   Cảm giác tổng thể: huyền bí, trầm tĩnh, cổ điển, trang nhã; tránh
    phong cách fantasy phương Tây hoặc giao diện bói toán đại trà.
-   Hình ảnh nên có chiều sâu không gian, sương mù, ánh sáng dịu và chi
    tiết trang trí vừa đủ.

### Bảng màu

-   **Mực đen / xanh than:** nền tối, khung và vùng điều hướng.
-   **Ngà giấy / be ấm:** nền sáng cho nội dung đọc.
-   **Vàng đồng / vàng cổ:** đường viền, họa tiết, điểm nhấn.
-   **Đỏ son:** dấu triện và điểm nhấn nhỏ.
-   **Xanh xám / nâu khói:** núi non, kiến trúc và các lớp sương.

### Chất liệu và họa tiết

-   Giấy dó, giấy cổ có vân nhẹ; mực loang và nét cọ.
-   Viền kim loại chạm khắc mảnh, hoa văn mây, sóng nước và đường hình
    học.
-   Họa tiết Bát Quái, Thái Cực, vòng thiên văn và ký hiệu quẻ chỉ dùng
    như yếu tố trang trí; cần rõ nét, cân đối và không lấn át nội dung.
-   Hoa mai hoặc hoa mận, cành cây, đèn lồng, mái đình, tháp và núi mờ
    có thể dùng làm chi tiết phụ.

## 2. Nguyên tắc sử dụng hình ảnh

-   Tách **ảnh nền** khỏi thành phần giao diện; ảnh nền không chứa nút,
    icon chức năng, thanh điều hướng, chữ tiêu đề hay thẻ nội dung.
-   Chừa vùng ít chi tiết ở vị trí dự kiến đặt chữ để nội dung dễ đọc.
-   Với nền tối, dùng lớp phủ tối nhẹ nếu cần; với nền giấy sáng, tránh
    vùng sáng gắt ngay sau chữ.
-   Ưu tiên ảnh dọc cho màn hình điện thoại, tỷ lệ tham khảo **9:16**
    hoặc **9:19.5**.
-   Không để biểu tượng Bát Quái hoặc vòng đồ hình bị cắt cụt ở vùng
    tiêu điểm.
-   Không nhúng chữ giả, chữ Hán ngẫu nhiên, watermark hoặc logo vào ảnh
    nền.
-   Hình ảnh chân dung tướng số, nếu có, phải là asset minh họa riêng;
    không đặt sẵn vào ảnh nền chung.
-   Chuẩn bị phiên bản sáng/tối khi một màn hình cần thay đổi nền theo
    chủ đề.

## 3. Danh mục hình ảnh theo màn hình

### 3.1. Trang chủ --- `home_bg`

**Mục đích:** tạo không khí tổng thể và làm nền cho các lối vào nội dung
chính.

**Hình ảnh đề xuất** - Thung lũng sơn thủy nhiều lớp, núi đá ẩn hiện
trong mây. - Mặt trời hoặc vầng trăng ở xa, dòng sông phản chiếu ánh
vàng. - Mái đình hoặc hành lang gỗ ở rìa khung hình, cành hoa mận/mai ở
góc trên. - Có thể thêm một vòng thiên văn rất mờ ở vùng trung tâm phía
trên.

**Bố cục** - Chi tiết kiến trúc và cành hoa tập trung ở viền. - Trung
tâm có độ tương phản thấp, đủ thoáng để đặt lời chào hoặc thông điệp. -
Phần dưới tối hơn để dễ đặt các thẻ điều hướng.

**Tránh:** nhân vật lớn ở trung tâm, chữ viết, nút, icon hoặc bảng thông
tin được vẽ sẵn trong ảnh.

### 3.2. Tử vi --- `tu_vi_bg`

**Mục đích:** gợi cảm giác lá số cổ và thiên văn học phương Đông.

**Hình ảnh đề xuất** - Nền giấy ngà hoặc xanh than có vân giấy nhẹ. -
Vòng thiên bàn nhiều lớp, các cung phân chia đều và đường kẻ mảnh. -
Điểm nhấn Thái Cực ở tâm; ký hiệu cung/quẻ được trình bày có trật tự. -
Mây núi hoặc thiên tượng mờ ở phần rìa.

**Bố cục** - Vòng thiên bàn là tiêu điểm chính, đặt giữa hoặc ở nửa
trên. - Chừa khoảng trống phía dưới cho các khối nội dung. - Họa tiết
trang trí không được làm giảm khả năng đọc các thông tin lá số.

### 3.3. Bát Quái / Thái Ất --- `bat_quai_bg`

**Mục đích:** thể hiện rõ biểu tượng thuật số phương Đông.

**Hình ảnh đề xuất** - Đồ hình Bát Quái với tám quái bao quanh vòng tròn
Thái Cực. - Các vòng đồng tâm, đường phương vị, nét khắc cổ và họa tiết
thiên văn. - Nền mực đen, xanh mực hoặc giấy cổ; đường nét màu vàng
đồng/ngà. - Có thể lồng ghép núi mờ và mây khí ở phía sau.

**Bố cục** - Đồ hình lớn, cân xứng, dễ nhận biết ngay cả trên màn hình
nhỏ. - Giữ trục trung tâm thẳng và các quái phân bố đều. - Đồ hình là
chủ thể chính; cảnh nền chỉ đóng vai trò hỗ trợ.

**Tránh:** Bát Quái méo, sai số lượng quái, biểu tượng Thái Cực biến
dạng hoặc quá nhiều ký tự trang trí khó đọc.

### 3.4. Tướng số --- `tuong_so_bg`

**Mục đích:** tạo bối cảnh trang nhã cho nội dung xem tướng.

**Hình ảnh đề xuất** - Không gian thư phòng hoặc hiên cổ nhìn ra núi
sương. - Gương đồng, cuộn thư, nghiên mực, đèn lồng và hoa văn hình học
tinh tế. - Một vòng Bát Quái hoặc đồ hình nhân tướng mờ ở nền sau. -
Tông nâu gỗ, xanh xám, ngà giấy và vàng đồng.

**Bố cục** - Để trống khu vực trung tâm hoặc một bên màn hình dành cho
ảnh chân dung riêng. - Các vật dụng đặt ở cạnh dưới/góc ảnh, không tranh
chấp với nội dung chính. - Tránh vẽ sẵn khuôn mặt có đường phân tích lên
nền.

### 3.5. Bát tự --- `bat_tu_bg`

**Mục đích:** gợi hình ảnh thư tịch và hệ thống Can Chi, Ngũ Hành.

**Hình ảnh đề xuất** - Giấy cổ, thẻ tre, cuộn thư hoặc bàn thư pháp. -
Họa tiết mờ về Thiên Can, Địa Chi và Ngũ Hành. - Năm yếu tố Kim, Mộc,
Thủy, Hỏa, Thổ thể hiện bằng màu sắc tiết chế, không dùng biểu tượng
hoạt hình. - Có thể dùng đường tròn Ngũ Hành rất mờ làm nền.

**Bố cục** - Nền ít chi tiết, ưu tiên vùng trống để trình bày nội
dung. - Các biểu tượng ngũ hành nếu có cần đồng nhất về nét vẽ và kích
thước.

### 3.6. Tình duyên --- `tinh_duyen_bg`

**Mục đích:** mềm mại, gần gũi nhưng vẫn giữ mỹ thuật phương Đông.

**Hình ảnh đề xuất** - Hồ nước, cầu đá, trăng sáng, hoa rơi và hai dải
mây đối xứng. - Dây tơ đỏ hoặc họa tiết nút kết truyền thống làm điểm
nhấn nhỏ. - Tông ngà, đỏ son trầm, hồng đất và xanh đêm.

**Bố cục** - Trung tâm thoáng để đặt nội dung. - Các chi tiết lãng mạn
nằm ở rìa, tránh trái tim kiểu hoạt hình hoặc hiệu ứng neon.

### 3.7. Tài vận --- `tai_van_bg`

**Mục đích:** gợi sự ổn định, thịnh vượng và cân bằng.

**Hình ảnh đề xuất** - Núi vững, dòng nước uốn lượn, ánh nắng vàng
nhẹ. - Họa tiết đồng tiền cổ, mây lành hoặc hoa văn cát tường dùng rất
tiết chế. - Tông xanh than, nâu gỗ, vàng đồng và đỏ son làm điểm nhấn.

**Bố cục** - Nền có chiều sâu nhưng không quá nhiều chi tiết. - Tránh
hình ảnh vàng bạc chất đống hoặc phong cách quảng cáo làm giàu.

### 3.8. Sự nghiệp --- `su_nghiep_bg`

**Mục đích:** tạo cảm giác vững chãi, tập trung và có phương hướng.

**Hình ảnh đề xuất** - Đường núi dẫn lên đình cao, cổng thành hoặc con
đường giữa mây. - Mặt trời mọc phía xa, đường nét kiến trúc thẳng và
chắc. - Tông xanh xám, mực đen, đá ấm và vàng nhạt.

**Bố cục** - Dùng đường dẫn thị giác hướng lên phía trên. - Giữ vùng đặt
chữ tương đối phẳng, không có chi tiết sáng phức tạp.

### 3.9. Tarot / quẻ --- `tarot_bg`

**Mục đích:** tạo không khí nghi lễ và khám phá biểu tượng.

**Hình ảnh đề xuất** - Bàn gỗ tối, vải lụa, khói hương, ánh nến và hoa
văn Bát Quái. - Họa tiết thẻ/quẻ cổ, đường viền vàng đồng và bóng đổ
mềm. - Nền tối, điểm sáng tập trung ở giữa.

**Bố cục** - Giữ trung tâm đủ sạch để đặt hình lá bài hoặc thẻ quẻ
riêng. - Không nhúng sẵn lá bài, chữ hay nút vào ảnh nền nếu chúng cần
được hiển thị riêng trong giao diện.

### 3.10. Hồ sơ cá nhân --- `profile_bg`

**Mục đích:** tạo cảm giác như một trang thư tịch cá nhân.

**Hình ảnh đề xuất** - Nền xanh mực hoặc giấy cổ, mây núi và vòng thiên
bàn mờ. - Họa tiết triện, dấu son hoặc khung trang trí thanh mảnh. - Có
thể dùng một huy hiệu tròn mang chủ đề Thái Cực/Bát Quái làm điểm nhấn.

**Bố cục** - Vùng đầu trang tương đối tối giản để đặt ảnh đại diện và
tiêu đề. - Họa tiết nền giảm độ tương phản ở khu vực thông tin.

## 4. Bộ asset trang trí dùng chung

  --------------------------------------------------------------------------
  Tên asset               Mô tả hình ảnh             Cách sử dụng
  ----------------------- -------------------------- -----------------------
  `motif_bagua`           Đồ hình Bát Quái nét mảnh  Họa tiết nền hoặc huy
                                                     hiệu

  `motif_yinyang`         Biểu tượng Thái Cực cân    Điểm nhấn trung tâm
                          đối                        

  `motif_tianpan`         Vòng thiên bàn nhiều lớp   Nền Tử vi, Thái Ất

  `motif_five_elements`   Bộ biểu tượng              Họa tiết hoặc minh họa
                          Kim--Mộc--Thủy--Hỏa--Thổ   nhỏ

  `border_ornamental`     Khung viền cổ, nét vàng    Bao quanh khu vực nội
                          đồng                       dung

  `seal_red`              Dấu triện đỏ son           Điểm nhấn trang trí

  `cloud_motif`           Mây cách điệu phương Đông  Phân lớp và chuyển tiếp

  `mountain_inkwash`      Núi sơn thủy dạng mực      Nền phụ
                          loang                      

  `blossom_branch`        Cành mai/mận               Trang trí góc

  `lantern_glow`          Đèn lồng ánh sáng ấm       Tạo chiều sâu

  `paper_texture`         Vân giấy cổ nhẹ            Nền sáng

  `ink_texture`           Vân mực hoặc giấy xanh đen Nền tối
  --------------------------------------------------------------------------

## 5. Quy chuẩn hình ảnh bàn giao

-   **Ảnh nền màn hình:** PNG hoặc WebP chất lượng cao, ưu tiên tỷ lệ
    dọc.
-   **Họa tiết trong suốt:** PNG hoặc SVG nếu là đường nét/vector đơn
    giản.
-   **Không gian an toàn:** chừa vùng trống theo bố cục thực tế của từng
    màn hình; không đặt chi tiết quan trọng sát mép.
-   **Tính nhất quán:** cùng một phong cách nét vẽ, độ chi tiết, chất
    liệu và sắc độ ánh sáng trong toàn ứng dụng.
-   **Khả năng đọc:** hình nền phải hỗ trợ giao diện, không cạnh tranh
    với nội dung.
-   **Tính xác thực biểu tượng:** kiểm tra kỹ Bát Quái, Thái Cực và các
    đồ hình trước khi sử dụng; không dùng ký tự giả làm chi tiết chính.

## 6. Hướng dẫn prompt tạo ảnh

Khi tạo từng ảnh nền, giữ cấu trúc prompt gồm: 1. **Chủ thể:** ví dụ đồ
hình Bát Quái, thiên bàn, thư phòng cổ hoặc sơn thủy. 2. **Mỹ thuật:**
tranh thủy mặc pha digital painting, kiến trúc phương Đông, chất liệu
giấy/mực. 3. **Bảng màu:** chọn theo từng màn hình nhưng giữ vàng đồng
và màu mực làm ngôn ngữ chung. 4. **Bố cục:** nêu rõ vùng cần thoáng để
đặt giao diện. 5. **Ràng buộc:** không chữ, không logo, không nút, không
icon UI, không watermark.

**Prompt nền chung tham khảo**

> Vertical mobile background for a refined East Asian divination app
> inspired by Thai At, Bagua and Yin-Yang philosophy; cinematic ink-wash
> mountains, ancient temple architecture, drifting mist, subtle
> antique-gold geomantic linework, restrained navy ink and warm ivory
> palette, delicate paper texture, elegant and contemplative atmosphere,
> carefully composed negative space for interface overlays, no people,
> no text, no logos, no buttons, no UI icons, no watermark.

## 7. Tiêu chí duyệt hình

-   Nhìn vào là nhận ra tinh thần phương Đông, không giống giao diện
    chiêm tinh phương Tây.
-   Đồ hình Thái Cực/Bát Quái cân đối, rõ ràng và không bị biến dạng.
-   Có vùng trống hợp lý cho thành phần giao diện.
-   Không có chữ giả hoặc thành phần UI bị vẽ sẵn.
-   Màu sắc, ánh sáng và chất liệu thống nhất với các màn hình còn lại.
-   Khi thu nhỏ trên điện thoại, tiêu điểm vẫn rõ và tổng thể không bị
    rối.

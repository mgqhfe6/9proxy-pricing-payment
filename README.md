# mua 9proxy: chọn gói theo IP hay theo GB, thanh toán từ Việt Nam và cách không trả tiền cho phần mình không dùng

Câu hỏi khó nhất khi mua 9Proxy không nằm ở nút thanh toán. Nó nằm ở chỗ 9Proxy bán proxy theo hai cách tính hoàn toàn khác nhau, và chọn nhầm kiểu thì tiền vẫn mất nhưng bạn không dùng hết phần đã trả.

Cụ thể: gói theo IP tính tiền một lần cho số lượng địa chỉ, băng thông đi kèm không giới hạn, và số IP chưa dùng thì không hết hạn. Gói theo GB thì ngược lại, trả tiền cho dung lượng, dùng trong 180 ngày. Cùng một nhu cầu "nuôi 200 tài khoản" hay "cào dữ liệu 3 sàn thương mại điện tử" có thể rẻ hơn vài lần nếu chọn đúng loại, hoặc đắt hơn vài lần nếu chọn sai.

Phần dưới đây là những gì cần biết trước khi bấm mua: giá hiện hành, các cổng thanh toán dùng được từ Việt Nam, giới hạn thật của từng gói, và vài cách cắt chi phí mà không phải đổi nhà cung cấp.

## Chọn sai mô hình tính phí là cách mất tiền nhanh nhất

Hai mô hình của 9Proxy không phải hai mức giá của cùng một thứ. Chúng là hai sản phẩm khác nhau về cách vận hành.

**Gói theo IP** cấp cho bạn một số lượng địa chỉ dân cư cố định. Mỗi IP chạy được từ vài giờ tới khoảng 24 giờ tùy địa chỉ, trong thời gian sống thì bạn truyền bao nhiêu dữ liệu cũng được, không bị trừ thêm. Số IP chưa kết nối vẫn nằm nguyên trong ví, không có ngày hết hạn. Đổi lại, mô hình này bắt buộc dùng ứng dụng 9Proxy trên máy (Windows, macOS, Linux) để forward cổng, nên không hợp với người chỉ muốn mở trình duyệt là chạy.

**Gói theo GB** thì bạn mua dung lượng, và hệ thống tự sinh endpoint không giới hạn qua toàn bộ pool. Không cần cài gì, chỉ cần user/password hoặc whitelist IP là dùng ngay từ dashboard. Hạn dùng 180 ngày, riêng các gói Enterprise thì không giới hạn thời gian.

Cách chọn nhanh:

- Việc cần **giữ nguyên một IP trong nhiều giờ** (nuôi tài khoản, phiên đăng nhập, thao tác trên nền tảng chống bot gắt): gói theo IP.
- Việc cần **đổi IP liên tục nhưng mỗi request nhẹ** (kiểm tra quảng cáo, kiểm tra giá, polling API, kiểm tra vị trí hiển thị): gói theo GB thường rẻ hơn nhiều.
- Việc cần **cả hai** trong cùng một dự án: gói bundle.

Một điểm dễ bỏ qua: gói theo IP có băng thông không giới hạn, nên nếu bạn tải nội dung nặng hoặc chạy job dài mà không đo được dung lượng, đây là loại duy nhất không khiến bạn phải nhìn đồng hồ GB.

## Bảng giá 9Proxy hiện hành

9Proxy đã điều chỉnh giá một lần kể từ khi thành lập, áp dụng từ 00:00 UTC ngày 1/6/2026, và chỉ áp dụng cho gói theo IP cùng gói bundle. Giá gói theo GB giữ nguyên. Các mức dưới đây là giá niêm yết sau lần điều chỉnh đó.

### Gói proxy dân cư theo IP (băng thông không giới hạn)

| Gói | Đơn giá | Tổng | Hiệu lực | Mua |
| --- | --- | --- | --- | --- |
| 100 IP | $0,24/IP | $24 | IP không hết hạn | Mua gói 100 IP 9Proxy |
| 500 IP | $0,144/IP | $72 | IP không hết hạn | Mua gói 500 IP 9Proxy |
| 1.000 IP + 500 IP thưởng | $0,084/IP | $126 | IP không hết hạn | Mua gói 1.000 IP 9Proxy |
| 2.500 IP | $0,084/IP | $210 | IP không hết hạn | Mua gói 2.500 IP 9Proxy |
| 5.000 IP | $0,072/IP | $360 | IP không hết hạn | Mua gói 5.000 IP 9Proxy |
| 15.000 IP | $0,048/IP | $720 | IP không hết hạn | Mua gói 15.000 IP 9Proxy |
| 25.000 IP | $0,035/IP | $863 | IP không hết hạn | Mua gói 25.000 IP 9Proxy |
| 50.000 IP | $0,029/IP | $1.438 | IP không hết hạn | Mua gói 50.000 IP 9Proxy |
| 100.000 IP | $0,023/IP | $2.300 | IP không hết hạn | Mua gói Business 100.000 IP |
| 200.000 IP | $0,021/IP | $4.140 | IP không hết hạn | Mua gói Business 200.000 IP |
| 500.000 IP | $0,018/IP | $8.625 | IP không hết hạn | Mua gói Business 500.000 IP |

Gói nhỏ nhất của mô hình này là 100 IP, không có bậc thấp hơn. Nếu bạn chỉ cần test 5–10 IP, cách rẻ nhất là xin trial giới hạn qua kênh hỗ trợ thay vì mua.

### Gói proxy dân cư theo GB

| Gói | Đơn giá | Tổng | Hiệu lực | Mua |
| --- | --- | --- | --- | --- |
| 5 GB | $3,00/GB | $15 | 180 ngày | Mua gói 5 GB 9Proxy |
| 50 GB + 5 GB thưởng | $2,10/GB | $105 | 180 ngày | Mua gói 50 GB 9Proxy |
| 100 GB | $1,50/GB | $150 | 180 ngày | Mua gói 100 GB 9Proxy |
| 200 GB | $1,00/GB | $200 | 180 ngày | Mua gói 200 GB 9Proxy |
| 1.000 GB | $0,80/GB | $800 | 180 ngày | Mua gói 1.000 GB 9Proxy |
| 2.000 GB | $0,75/GB | $1.500 | 180 ngày | Mua gói 2.000 GB 9Proxy |
| 3.000 GB | $0,72/GB | $2.160 | Không giới hạn | Mua gói Enterprise 3.000 GB |
| 6.000 GB | $0,70/GB | $4.200 | Không giới hạn | Mua gói Enterprise 6.000 GB |
| 10.000 GB | $0,68/GB | $6.800 | Không giới hạn | Mua gói Enterprise 10.000 GB |

### Gói bundle (IP kèm dung lượng)

| Gói | Cấu hình | Tổng | Hiệu lực dung lượng | Mua |
| --- | --- | --- | --- | --- |
| Bundle entry | 100 IP + 5 GB | $30 | 180 ngày | Mua bundle 100 IP + 5 GB |
| Bundle mid | 1.500 IP + 50 GB | $180 | 180 ngày | Mua bundle 1.500 IP + 50 GB |
| Bundle cao | 5.000 IP + 500 GB | $720 | 180 ngày | Mua bundle 5.000 IP + 500 GB |

Bundle cũng nằm trong đợt tăng giá ngày 1/6/2026, nên nếu bạn từng thấy mức $25 / $150 / $600 ở đâu đó thì đó là giá cũ.

Hiện 9Proxy chỉ niêm yết hai dòng sản phẩm dân cư (theo IP và theo GB) cùng các gói bundle. Dòng proxy datacenter từng được nhắc trong tài liệu giới thiệu nhưng chưa mở bán công khai, nên đừng tính toán ngân sách dựa trên nó.

Một lưu ý về giá: bảng trên là giá niêm yết tại thời điểm viết, tính bằng USD. Giá có thể thay đổi và 9Proxy từng chạy khuyến mãi theo mùa, nên bước cuối trước khi trả tiền vẫn nên xem lại trang giá.

## mua 9proxy từ Việt Nam: thanh toán bằng gì

Đây là phần khiến nhiều người bỏ cuộc giữa đường, dù thực tế không phức tạp. Checkout của 9Proxy có ba nhóm.

**Thẻ và ví quốc tế:** Credit Card, Google Pay, Apple Pay, Alipay.

**Crypto:** USDT, BTC, ETH, LTC, DOGE và một số đồng khác. Điểm đáng chú ý: theo mô tả của 9Proxy, khách trả bằng crypto được cộng thêm 5% IP. Nếu bạn định mua gói lớn, đây là mức giảm thật, không phải khuyến mãi trang trí.

**Local Payment:** hệ thống tự hiển thị phương thức theo quốc gia. Với người ở Việt Nam, kênh này gồm chuyển khoản ngân hàng online và một số ví điện tử phổ biến như Momo, ShopeePay, Appota. Quét QR, xác nhận, proxy vào ví gần như ngay. Đây là lựa chọn hợp lý nếu bạn không muốn dùng thẻ quốc tế hoặc không có crypto.

Về mã giảm giá: các đợt coupon của 9Proxy thường có thời hạn ngắn và được phát qua hai kênh là mục My Coupons trong dashboard và Telegram hỗ trợ. Ví dụ đợt Tết 2026 chạy mã LNY2026 giảm 8% cho gói IP và GB thường, thời gian 23/1–23/2/2026, đến nay đã hết. Tháng 4/2026 có chương trình hoàn 9% cho đơn GB, mã sinh tự động, hạn dùng 30/6/2026, cũng đã kết thúc. Nghĩa là đừng tin các trang liệt kê "mã 9Proxy còn hiệu lực" nếu không ghi rõ ngày, và đừng áp mã cũ rồi thắc mắc tại sao không giảm.

Thứ luôn có: mua qua link giới thiệu thì tài khoản mới được giảm 5% cho đơn hàng, và mức này đi kèm với việc bạn đăng ký bằng mã mời. Đó là lý do nên tạo tài khoản qua link có sẵn mã mời ngay từ đầu, thay vì đăng ký chay rồi tìm cách áp mã sau.

👉 Tạo tài khoản 9Proxy kèm mã mời để nhận 5% cho đơn đầu tiên

## Quy trình mua và nhận proxy

1. **Đăng ký tài khoản** bằng email qua link có mã mời. Mã mời chỉ áp được khi đăng ký hoặc ở bước checkout, không gắn bù về sau.
2. **Chọn đúng trang giá** theo nhu cầu: gói theo IP, gói theo GB, hay bundle. Ba nhóm này ở ba trang riêng, giá không nằm chung một bảng.
3. **Chọn bậc số lượng**, bấm Order Now để sang checkout.
4. **Chọn cổng thanh toán.** Nhập mã coupon nếu có tại ô dành riêng, trước khi xác nhận. Với Local Payment, hệ thống sẽ hiện phương thức khả dụng theo vị trí của bạn.
5. **Nhận proxy.** Gói theo GB dùng ngay trong dashboard bằng user/password hoặc whitelist IP, hoặc qua Proxy2Web nếu chỉ cần kiểm tra nhanh trên trình duyệt. Gói theo IP cần tải ứng dụng 9Proxy cho Windows, macOS hoặc Linux để forward cổng. Có API công khai cho ai chạy pipeline tự động, và 9Proxy hỗ trợ SOCKS5 nên cắm vào antidetect browser hoặc script Python không cần đổi gì nhiều.

👉 Xem các bậc gói và mua 9Proxy tại đây

## Những giới hạn nên biết trước khi trả tiền

Phần này ít được nhắc trong các bài giới thiệu, nhưng lại quyết định việc bạn có thấy tiền bỏ ra hợp lý hay không.

**IP dân cư không sống vĩnh viễn.** Mỗi IP tồn tại vài giờ, cá biệt tới khoảng 24 giờ. Đây là đặc điểm của proxy dân cư nói chung, không phải lỗi riêng của 9Proxy. Chính sách bù là: nếu IP chết trong 60 giây đầu sau khi forward, bạn được thay miễn phí. Ngoài 60 giây đó thì không.

**Today List.** IP nào bạn đã dùng trong 24 giờ gần nhất mà quay lại hoạt động thì được dùng lại miễn phí, không trừ vào số dư. Với job chạy hằng ngày, tính năng này cắt được một phần đáng kể lượng IP phải mua.

**Gói theo IP yêu cầu ứng dụng desktop.** Đây là hạn chế thật. Nếu bạn muốn chạy proxy trực tiếp trên điện thoại, máy ảo, hay thiết bị không cài được app, mô hình theo IP sẽ vướng. iTWire cũng ghi nhận điểm này khi so với các nhà cung cấp dùng extension trình duyệt. Giải pháp thay thế là ProxyHub cho thiết bị di động, hoặc chuyển sang gói theo GB vốn không cần app.

**Dung lượng GB có hạn 180 ngày**, trừ gói Enterprise. Mua 2.000 GB rồi dùng chậm thì phần chưa dùng sẽ hết hạn. Đây là lý do không nên mua GB dự trữ quá nhiều nếu lịch làm việc của bạn không đều.

**Không có trial tự động.** Trial tồn tại nhưng ở dạng giới hạn, phụ thuộc vào tình trạng còn hàng, và phải liên hệ hỗ trợ (live chat, email, Telegram) để xin. Một số người dùng trên các nền tảng đánh giá ghi nhận việc thử trước khi mua là điểm cộng, nhưng đừng mặc định là có.

**Pool không phải lớn nhất thị trường.** 9Proxy công bố 20 triệu IP dân cư tại hơn 90 quốc gia và định vị tới cấp thành phố, bang, mã ZIP và ISP. Con số này nhỏ hơn các nhà cung cấp tầm 80–150 triệu IP. Với công việc thông thường thì không thành vấn đề; nếu bạn cần IP ở những khu vực rất hẹp, nên kiểm tra khu vực cụ thể trước.

## Cách mua 9proxy rẻ hơn mà không đổi chất lượng

Không cần thủ thuật gì phức tạp, chỉ cần đừng trả tiền cho thứ bạn không dùng.

- **Đo dung lượng trước khi chọn mô hình.** Nếu mỗi request chỉ vài chục tới vài trăm KB, gói GB sẽ rẻ hơn nhiều so với việc mua cả một bậc IP. Nếu job tải nội dung nặng hoặc chạy liên tục, băng thông không giới hạn của gói IP lại tránh được rủi ro vượt dung lượng.
- **Tận dụng Today List.** Một số nguồn ghi nhận tính năng này giúp giảm 20–30% nhu cầu IP cho các job lặp lại hằng ngày.
- **Trả bằng crypto nếu bạn có.** Cộng 5% IP là mức giảm cố định, dễ hơn là đi săn coupon theo mùa.
- **Đăng ký bằng link có mã mời.** 5% cho đơn hàng, áp ngay từ tài khoản mới.
- **Chọn bậc số lượng hợp lý.** Đơn giá giảm rõ khi lên bậc: từ $0,24/IP ở gói 100 IP xuống $0,084/IP ở gói 1.500 IP, rồi $0,048/IP ở gói 15.000 IP. Tuy nhiên đừng nhảy bậc chỉ vì đơn giá đẹp, vì số IP không dùng vẫn nằm đó mãi.

👉 Kiểm tra bậc giá phù hợp với khối lượng công việc của bạn

## Mua trực tiếp hay qua đại lý bán CDKey?

Có một thị trường thứ cấp ở Việt Nam bán CDKey nạp vào tài khoản 9Proxy với giá thấp hơn niêm yết, thường kèm hướng dẫn nạp và cam kết bảo hành riêng. Cơ chế này có thật: 9Proxy hỗ trợ nạp tiền qua CDKey, và 9Proxy vẫn là bên cấp IP.

Điều cần cân: bảo hành và hỗ trợ khi mua qua đại lý là do đại lý chịu, không phải 9Proxy. Bạn vẫn phải có tài khoản trên hệ thống chính thức để nạp, nhưng mọi tranh chấp về đơn hàng sẽ nằm ngoài luồng hỗ trợ 24/7 của nhà cung cấp. Nếu tiết kiệm được vài chục phần trăm là yếu tố quyết định với bạn thì cần đọc kỹ điều kiện bảo hành của bên bán trước. Còn nếu bạn cần hóa đơn rõ ràng, hỗ trợ kỹ thuật trực tiếp và quyền lợi affiliate thì mua thẳng từ 9Proxy là đường ngắn nhất.

## Đánh giá từ bên thứ ba: con số và điều đáng lưu ý

Không có bài test độc lập nào đủ để kết luận thay bạn, nhưng vài dữ liệu đáng tham khảo:

- Geekflare chạy 300 request qua IP dân cư xoay vào một sàn thương mại điện tử lớn có Cloudflare: 293 request thành công (97,7%), 5 lần gặp CAPTCHA (1,7%), 2 lần bị chặn cứng (0,6%), thời gian phản hồi trung bình 0,63 giây. Cùng kịch bản đó qua pool datacenter cho tỷ lệ chặn 34% ở lần chạy đầu.
- ProxyLook cho 9Proxy 3,9/5 và điểm tin cậy 7,8/10, xếp vào nhóm proxy dân cư giá rẻ với mô hình trả theo IP.
- Caproxy ghi điểm biên tập 4,78 và điểm người dùng 4,33, kèm lưu ý "không khuyến khích cho người mới" — hợp lý, vì gói theo IP đòi hỏi hiểu biết về forward cổng và vòng đời IP.
- iTWire ghi nhận hoạt động tốt cho thương mại điện tử, nhưng dịch vụ streaming như Netflix có thể phát hiện proxy, và ứng dụng bắt buộc gây bất tiện khi dùng nhiều thiết bị.
- Có một báo cáo người dùng trên Caproxy ngày 2/7/2026 phản ánh dịch vụ gián đoạn khoảng một tuần. Đây là báo cáo đơn lẻ, không phải sự cố được xác nhận rộng rãi, nhưng nó là lý do hợp lý để lần đầu chỉ nên mua bậc nhỏ rồi nâng sau, thay vì nạp 500.000 IP ngay.

## Câu hỏi hay gặp khi mua 9Proxy

**Mua 100 IP dùng được bao lâu?** Không có hạn theo tháng. Mỗi IP sau khi kết nối sẽ hoạt động vài giờ tới khoảng 24 giờ, và bạn bị trừ một IP khi kết nối. Số IP chưa kết nối nằm trong ví vô thời hạn.

**Một IP dùng được bao nhiêu GB?** Với gói theo IP, băng thông không giới hạn trong thời gian IP còn sống.

**Có cần cài phần mềm không?** Gói theo IP thì có, cần app desktop để forward cổng. Gói theo GB thì không, dùng trực tiếp bằng user/password, whitelist IP hoặc Proxy2Web.

**Proxy chết thì sao?** Trong 60 giây đầu, bạn được thay miễn phí. Ngoài khoảng đó, dùng auto-refresh của app để tự thay, hoặc chờ IP cũ quay lại và dùng lại qua Today List.

**Trả bằng crypto có lợi gì?** Theo mô tả của 9Proxy, được cộng thêm 5% IP.

**Hỗ trợ ở đâu?** Live chat trên trang chủ, email support@9proxy.com, và Telegram @Official9Proxy. Geekflare ghi nhận hỗ trợ là người thật trực 24/7, không phải bot trả lời vòng lặp.

## Trước khi bấm mua

Danh sách kiểm tra ngắn: xác định job của bạn thuộc dạng giữ IP lâu hay đổi IP liên tục; nếu chưa chắc thì mua bậc nhỏ nhất của cả hai bên để so trực tiếp; đăng ký bằng link có mã mời để lấy 5%; chọn cổng thanh toán phù hợp, crypto nếu muốn thêm 5% IP; và kiểm tra trang giá một lần nữa vì con số có thể đã thay đổi kể từ ngày bài này được viết.

👉 Đăng ký tài khoản 9Proxy và chọn gói theo đúng nhu cầu của bạn

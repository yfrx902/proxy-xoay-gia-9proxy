# thuê proxy xoay: chọn gói theo IP hay theo GB, bảng giá và cách test trước khi nạp tiền

Hầu hết người gõ "thuê proxy xoay" đều đang ở đúng một tình huống: cần nhiều IP khác nhau để nuôi tài khoản, scrape dữ liệu hoặc kiểm tra quảng cáo theo khu vực, nhưng không muốn ký hợp đồng tháng với mức giá không rõ ràng. Cái khó là các nhà cung cấp hiển thị giá theo hai kiểu hoàn toàn khác nhau (theo IP và theo GB), nên con số trên trang chủ trông rẻ hơn thực tế rất nhiều nếu bạn không biết mình đang trả cho cái gì.

9Proxy là một trong những cái tên xuất hiện nhiều khi tìm dịch vụ này, với hai mô hình proxy dân cư chạy song song. Điểm đáng lưu ý trước tiên: đây không phải dịch vụ cho thuê theo tháng. Bạn nạp một lần, dùng đến khi hết tài nguyên, không có phí định kỳ. Với người quen kiểu "thuê proxy 300k/tháng", đây là khác biệt lớn về cách tính tiền, nên cần hiểu đúng trước khi so giá.

## Rotation trong "proxy xoay" thực chất là gì

Từ "xoay" bị dùng cho nhiều thứ khác nhau, và đây là nguồn gốc của phần lớn hiểu lầm khi thuê proxy xoay.

- **Xoay theo mỗi request:** mỗi lần gửi yêu cầu là một IP mới. Phù hợp scraping, check giá, quét SERP.
- **Xoay theo phiên (sticky):** giữ nguyên một IP trong X phút rồi mới đổi. Cần cho thao tác nhiều bước như đăng nhập, thanh toán, duyệt nhiều trang liên tiếp.
- **Xoay theo khoảng thời gian tự đặt:** kiểu dùng cho khung nuôi tài khoản, thường đặt 5–10 phút/IP.

9Proxy hỗ trợ cả ba kiểu, nhưng cách bật khác nhau tùy gói. Gói tính theo GB có sẵn chế độ Rotating và Sticky ngay trong dashboard. Gói tính theo IP thì IP không tự xoay; muốn xoay bạn dùng Auto Rotation Proxy trong app desktop, đặt khoảng thời gian đổi IP trên các port đã chọn. Nếu bạn mua gói IP rồi ngồi chờ nó tự đổi, sẽ không có gì xảy ra.

## Năm thông số quyết định số tiền bạn thực trả

Giá niêm yết chỉ là bề mặt. Khi so giữa các nhà cung cấp, năm thứ sau đây mới quyết định chi phí thật:

**Bạn trả theo IP hay theo GB.** Gói theo IP cho băng thông không giới hạn trong thời gian IP còn sống. Gói theo GB thì tạo được bao nhiêu endpoint cũng được, miễn còn dung lượng. Cùng một công việc, hai cách tính này lệch nhau vài lần.

**Thời gian sống của IP.** Proxy dân cư không sống mãi. Với 9Proxy, một IP tồn tại vài giờ đến khoảng 24 giờ tùy điều kiện; một số bài review ghi nhận mức trung bình quanh 3 giờ. IP nào chết thì thay, không tính thêm lượt dùng.

**Cách xác thực.** Gói GB dùng được cả username/password và whitelist IP. Gói IP yêu cầu app desktop để forward port local, nên máy Linux hoặc VPS thường phải đi đường GB.

**Độ sâu geo-targeting.** Chọn quốc gia là mức cơ bản. Chọn được state, city, ZIP và ISP mới đủ cho kiểm tra quảng cáo hoặc theo dõi SERP theo địa phương.

**Thời hạn sử dụng.** Gói GB của 9Proxy có hạn 180 ngày. IP chưa dùng thì không hết hạn. Đây là lý do nhiều người mua gói lớn thay vì nạp lẻ.

## Bảng giá 9Proxy hiện tại

Toàn bộ bảng dưới đây là các gói 9Proxy đang niêm yết, giá bằng USD, hình thức trả một lần. Nhóm gói theo IP và gói bundle đã điều chỉnh giá từ ngày 1/6/2026; nhóm theo GB giữ nguyên. Giá có thể thay đổi tiếp, nên con số trên trang pricing là căn cứ cuối cùng.

| Gói | Bạn nhận được | Giá | Quy đổi | Thời hạn | Mua |
| --- | --- | --- | --- | --- | --- |
| 100 IP | 100 IP dân cư, băng thông không giới hạn | $24 | ~$0,24/IP | IP chưa dùng không hết hạn | [ Xem gói 100 IP](https://bit.ly/9-Proxy) |
| 500 IP | 500 IP, băng thông không giới hạn | $72 | ~$0,14/IP | IP chưa dùng không hết hạn | [ Xem gói 500 IP](https://bit.ly/9-Proxy) |
| 1.000 IP (+500 IP tặng) | 1.500 IP tổng, băng thông không giới hạn | $126 | ~$0,08/IP | IP chưa dùng không hết hạn | [ Xem gói 1.000 IP + 500 IP](https://bit.ly/9-Proxy) |
| 100.000 IP | Gói quy mô lớn cho đội nhóm, agency | $2.300 | ~$0,023/IP | IP chưa dùng không hết hạn | [ Xem gói 100.000 IP](https://bit.ly/9-Proxy) |
| 500.000 IP | Gói lớn nhất, dành cho vận hành quy mô | $8.625 | ~$0,017/IP | IP chưa dùng không hết hạn | [ Xem gói 500.000 IP](https://bit.ly/9-Proxy) |
| 5 GB | Tạo endpoint không giới hạn, xoay mỗi request hoặc sticky | $15 | $3,00/GB | 180 ngày | [ Xem gói 5 GB](https://bit.ly/9-Proxy) |
| 50 GB (+5 GB) | Như trên, cộng 5 GB | $105 | $2,10/GB | 180 ngày | [ Xem gói 50 GB](https://bit.ly/9-Proxy) |
| 100 GB | Như trên | $150 | $1,50/GB | 180 ngày | [ Xem gói 100 GB](https://bit.ly/9-Proxy) |
| 200 GB | Như trên | $200 | $1,00/GB | 180 ngày | [ Xem gói 200 GB](https://bit.ly/9-Proxy) |
| 1.000 GB | Như trên | $800 | $0,80/GB | 180 ngày | [ Xem gói 1.000 GB](https://bit.ly/9-Proxy) |
| 2.000 GB | Như trên | $1.500 | $0,75/GB | 180 ngày | [ Xem gói 2.000 GB](https://bit.ly/9-Proxy) |
| 10.000 GB | Mốc giá thấp nhất của dòng GB | ~$0,68/GB | ~$0,68/GB | 180 ngày | [ Xem gói dung lượng lớn](https://bit.ly/9-Proxy) |
| Starter bundle | 100 IP + 5 GB | $30 | Kết hợp cả hai dòng | Dung lượng 180 ngày | [ Xem gói Starter bundle](https://bit.ly/9-Proxy) |
| Popular bundle | 1.500 IP + 50 GB | $180 | Kết hợp cả hai dòng | Dung lượng 180 ngày | [ Xem gói Popular bundle](https://bit.ly/9-Proxy) |
| Pro bundle | 5.000 IP + 500 GB | $720 | Kết hợp cả hai dòng | Dung lượng 180 ngày | [ Xem gói Pro bundle](https://bit.ly/9-Proxy) |
| Enterprise | Team 1 owner + 5 member, traffic không hết hạn, chia dung lượng theo từng người | Báo giá riêng | VIP pricing | Không giới hạn thời hạn | [ Liên hệ gói Enterprise](https://bit.ly/9-Proxy) |

Một chi tiết dễ bỏ qua: gói IP của 9Proxy không có mốc giá cố định cho mọi dung lượng. Giữa các mốc trên vẫn còn những bậc trung gian, và đơn giá giảm dần theo số lượng. Nếu bạn cần đúng một con số cụ thể như 3.000 IP, nên mở trang pricing xem bậc tương ứng thay vì nhân đơn giá của gói nhỏ.

## Gói theo IP hay theo GB: chọn theo kiểu việc, không theo giá

Đây là phần quyết định nhiều nhất và cũng là phần các bài so sánh hay nói chung chung.

**Chọn gói theo IP khi** công việc của bạn gắn với danh tính cố định: mỗi tài khoản một IP, nuôi tài khoản lâu dài, đăng nhập email, quản lý fanpage, chạy tool trên nhiều profile. Băng thông không giới hạn nên bạn không phải canh dung lượng khi tải ảnh, video hoặc tải tệp lớn. Đổi lại, bạn phải chấp nhận việc IP chết theo lịch tự nhiên và phải dùng app desktop.

**Chọn gói theo GB khi** mỗi request tiêu tốn rất ít dữ liệu nhưng cần đổi IP liên tục: scrape danh mục sản phẩm, check tồn kho, kiểm tra hiển thị quảng cáo, gọi API, kiểm tra chặn theo vùng. 5 GB ở mức request vài chục KB nghe ít nhưng thực tế chạy được khối lượng lớn vì HTML nhẹ. Cái lợi thứ hai là chạy trực tiếp trong dashboard, không cần cài gì, nên hợp với VPS và môi trường cloud.

Nếu bạn làm cả hai, nhóm bundle thường rẻ hơn mua hai gói riêng ở cùng mức tài nguyên. Starter $30 hay Popular $180 đều nằm trong khoảng dễ thử.

## Thuê và chạy proxy trong vài bước

Quy trình thực tế không dài, nhưng có vài chỗ hay làm người mới mất thời gian.

1. **Tạo tài khoản.** [👉 Đăng ký 9Proxy và nhận ưu đãi cho người dùng mới](https://bit.ly/9-Proxy). Theo mô tả chương trình affiliate của 9Proxy, người đăng ký qua link giới thiệu được giảm 5%. Ngoài ra, người dùng mới có thể đăng ký dùng thử miễn phí, nhưng số lượng có hạn và phụ thuộc tình trạng kho IP tại thời điểm bạn vào.
2. **Nạp gói.** Thanh toán bằng thẻ tín dụng, thẻ ngân hàng, crypto (USDT, BTC, ETH, LTC, DOGE và một số đồng khác), Alipay, Apple Pay, Google Pay.
3. **Tạo proxy.** Với gói GB: vào Dashboard → Residential Proxies → GB → Proxy Generator, chọn cách xác thực (user-pass hoặc whitelist IP), chọn quốc gia/bang/thành phố/ZIP/ISP, chọn Sticky hoặc Rotating, rồi xuất danh sách. Với gói IP: tải app desktop, forward sang port local dạng 127.0.0.1:port, dùng kèm Proxy Authentication nếu cần.
4. **Gắn vào tool.** 9Proxy hỗ trợ HTTP/HTTPS và SOCKS5, nên cắm thẳng vào AdsPower, Dolphin Anty, BitBrowser, Multilogin, hoặc thư viện requests/Scrapy trong Python. Định dạng xuất thường gặp là host:port:user:pass hoặc chuỗi URL có kèm user/pass, cùng code mẫu sẵn theo nhiều ngôn ngữ.

Với người ở Việt Nam không dùng thẻ quốc tế, một số đại lý trong nước bán CDKey 9Proxy tính bằng VND để bạn tự nạp vào tài khoản của mình. Cách này tiện về thanh toán nhưng hạn dùng và bảo hành do bên bán quy định, không giống mua trực tiếp.

## Những giới hạn nên biết trước khi trả tiền

Không có dịch vụ proxy nào phù hợp với tất cả mọi người, và 9Proxy cũng có những điểm cần cân nhắc thật.

**Đây là proxy dân cư, không phải datacenter.** Nếu công việc của bạn cần IP datacenter tốc độ cao giá rẻ, 9Proxy không có dòng đó. Một người dùng trên Trustpilot phản ánh đã mua gói nhỏ rồi mới nhận ra dịch vụ chỉ có proxy dân cư và bị từ chối hoàn tiền. Đọc kỹ trước khi nạp là cách rẻ nhất để tránh tình huống này.

**Chính sách thay IP chứ không hoàn tiền.** IP chết được đánh dấu và thay, cùng cơ chế Today List cho phép dùng lại IP sạch từ hôm trước. Đây là điểm được nhắc nhiều trong các đánh giá, nhưng nó không đồng nghĩa với việc bạn được hoàn tiền nếu gói không hợp nhu cầu.

**Từng có giai đoạn gián đoạn giữa 2026.** Một số nguồn bên thứ ba ghi nhận dịch vụ có thời điểm ngừng hoạt động trong năm 2026, kèm phản hồi của người dùng về việc không truy cập được trong vài ngày. Nếu bạn định nạp số tiền lớn, cách hợp lý là chạy thử một gói nhỏ trước, đo tỷ lệ thành công trên chính trang mục tiêu của bạn rồi mới scale.

**Gói theo IP phụ thuộc app desktop.** App có bản Windows và Mac. Chạy trên VPS Linux hoặc môi trường không cài được app thì gói GB là lựa chọn thực tế hơn.

**Cấu hình cần chút hiểu biết kỹ thuật.** Một số bài review xếp 9Proxy vào nhóm không dành cho người mới hoàn toàn. Nếu bạn chưa từng dùng proxy dân cư, hãy bắt đầu với gói GB nhỏ, gắn vào một profile duy nhất, kiểm tra IP bằng trang check trước khi chạy hàng loạt.

## Câu hỏi thường gặp khi thuê proxy xoay

**Có phí hàng tháng không?** Không. Bạn mua gói một lần. IP chưa dùng không hết hạn, dung lượng GB có hạn 180 ngày, gói Enterprise thì traffic không hết hạn.

**Có IP Việt Nam không?** 9Proxy quảng cáo pool hơn 20 triệu IP dân cư tại hơn 90 quốc gia, hỗ trợ target tới cấp thành phố và ISP. Với các khu vực Đông Nam Á, đây là điểm cần tự kiểm tra bằng trial trước khi mua gói lớn, vì mật độ IP ở mỗi quốc gia không giống nhau.

**Dùng được với AdsPower, Dolphin Anty?** Được. Các tool này nhận SOCKS5 và HTTP/HTTPS với định dạng host, port, user, pass. Gói GB không cần cài app nên setup nhanh hơn.

**Một tài khoản dùng cho nhiều người được không?** Có. 9Proxy hỗ trợ Share Code và tài khoản phụ. Gói Enterprise có team mode 1 owner kèm 5 member, chia dung lượng theo từng người và có log hoạt động.

**Nên mua gói nào để bắt đầu?** Với mục đích test, 5 GB ở mức $15 hoặc 100 IP ở mức $24 là hai điểm vào hợp lý. Chạy đúng một tuần trên công việc thật, ghi lại số request thành công và số lần phải đổi IP, rồi mới quyết định mua mốc lớn hơn.

Cách nghĩ đơn giản nhất: gói theo GB dành cho người cần nhiều IP và ít dung lượng, gói theo IP dành cho người cần ít IP nhưng dùng nhiều dữ liệu. Nếu bạn vẫn đang cân nhắc, [👉 xem bảng gói và chọn mức phù hợp với khối lượng công việc](https://bit.ly/9-Proxy) — chọn sai mô hình tính tiền tốn hơn chọn sai nhà cung cấp khá nhiều.

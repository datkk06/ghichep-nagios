# Tổng quan về Nagios.

![](/images/nagios.png)


## 1. Hệ thống giám sát mạng.

Giám sát mạng là một thuật ngữ dùng để chỉ việc sử dụng liên tục một hệ thống (có thể là một chương trình hoặc một thiết bị) 
để theo dõi tất cả các hoạt động của các thiết bị, các dịch vụ trong một hệ thống mạng.

Cần giám sát những gì và tại sao? Đối với hệ thống mạng, điều quan trọng nhất là nắm được những thông tin chính xác nhất vào 
mọi thời điểm. Những thông tin cần nắm bắt khi giám sát một hệ thống mạng bao gồm:

-  Tính sẵn sàng của thiết bị (Router, Switch, Server,…): những thiết bị giữ cho mạng hoạt động.

-  Các dịch vụ trong hệ thống (dns, ftp, http,…): những dịch vụ này đóng vai trò quan trọng trong một công ty, tổ chức, nếu 
các dịch vụ này không được đảm bào hoạt động bình thường và liên tục, nó sẽ ảnh hưởng nghiêm trọng đến công ty, tổ chức đó.

- Tài nguyên hệ thống: Các ứng dụng đều đòi hỏi tài nguyên hệ thống, việc giám sát tài nguyên sẽ đảm bảo cho chúng ta có những 
can thiệp kịp thời, tránh ảnh hưởng đến hệ thống.

-   Lưu lượng trong mạng: nhằm đưa ra những giải pháp, ngăn ngừa hiện tượng quá tải trong mạng.

- Các chức năng về bảo mật: nhằm đảm bảo an ninh trong hệ thống.

-  Nhiệt độ, thông tin về máy chủ, máy in: giúp tránh những hư hỏng xảy ra.

- Tạo file log: thu được những thông tin về những thay đổi trong hệ thống.

## 2. Tổng quan về Nagios.

### 2.1.Nagios là gì?

Nagios là một hệ thống giám sát mạnh mẽ cho phép các tổ chức xác định và giải quyết các vấn đề cơ sở hạ tầng CNTT trước khi chúng ảnh hướng đến quá trình kinh doanh quan trọng

Lần đầu tiên ra mắt vào năm 1999, Nagios đã có hàng ngàn dự án được phát triển bởi cộng đồng Nagios trên toàn thế giới. Nagios được bảo trợ chính thức bởi Nagios Enterprises, hỗ 
trợ cộng đồng trong một số cách khác nhau thông qua việc bán các sản phẩm thương mại và dịch vụ của mình.

Nagios theo dõi toàn bộ cơ sở hạ tầng CNTT của bạn để đảm bảo hệ thống, ứng dụng, dich vụ và quy trình kinh quanh đang hoạt động tốt. Trong trường hợp bị lỗi, 
Nagios có thể cảnh báo nhân viên kỹ thuật các vấn đề, cho phép họ bắt đầu quá trình phục hồi trước khi ảnh hưởng đến quá trình kinh doanh, người sử dụng, hoặc khách hàng.

Được thiết kế với khả năng mở rộng và tính linh hoạt trong, Nagios mang đến cho bạn sự an tâm đến từ hiểu biết quy trình kinh doanh của tổ chức bạn sẽ không bị ảnh hưởng bởi 
sự cố ngừng hoạt động không rõ nguyên nhân.

Nagios hỗ trợ người quản trị trong việc  :

- Lên kế hoạch cho việc nâng cấp cơ sở hạ tầng trước khu hệ thống lỗi thời gây ra lỗi.

- Ứng phó với các vấn đề ngay khi có dấu hiệu đầu tiên.

-  Tự động sửa chữa các vấn đề khi chúng đượcn phát hiện.

- Đảm bảo sự ngưng hoạt động của các cơ sở hạ tầng CNTT có ảnh hưởng tối thiểu đến hệ thống.

-  Theo dõi toàn bộ cơ sở hạ tầng và quy trình kinh doanh của bạn.

- Giám sát các dịch vụ mạng (HTTP, SMTP, POP3, PING,…)

- Giám sát tài nguyên máy chủ (processor load, disk usage,…)

-  Những phần bổ trợ đơn giản cho phép người dùng phát triển dịch vụ kiểm tra riêng của họ.

- Phát hiện và phân biệt được các máy chủ hay dich vụ xuống cấp và không thể truy cập được.

- Thông báo cho người giám sát khi máy chủ hay dịch vụ có vấn đề và được giải quyết.

- Tùy chọn giao diện web để xem tình trạng mạng hiện có, thông báo và lịch sử các vấn đề, đăng nhập tập tin,…

### 2.2. Một số chức năng chính của Nagios.

Cảnh báo: Nagios gửi cảnh báo khi có thành phần cơ sở hạ tầng bất ổn định và phục hồi, cung cấp cho các quản trị 
viên thông báo của các sự kiện quan trọng. Cảnh báo có thể được gửi qua email, SMS, hay tùy chỉnh.

Ứng phó: Nhân viên CNTT có thể xác nhận cảnh báo và bắt đầu giải quyết sự cố ngưng hoạt động và kiểm tra hệ thống 
cảnh báo ngay lập tức. Cảnh báo có thể được gia tăng cho các nhóm khác nhau nếu thông báo không xác nhận một cách kịp thời.

 Báo cáo: Báo cáo cung cấp một hồ sơ lịch sử của sự cố ngưng hoạt động, sự kiện, thông báo, và phản ứng cảnh báo để xem xét. 
 Sẵn có các báo cáo giúp đảm bảo SLAs của bạn đang được đáp ứng.

Bảo trì: Dự kiến thời gian ngừng làm việc ngăn cản các cảnh báo tỏng quá trình bảo trì theo lịch trình và nâng cấp.

Kế hoạch: Lập lịch đồ thị và báo cáo xu hướng và công suất cho phép bạn xách định sự cần thiết nâng cấp cơ sở hạ tầng trước khi xảy ra sự cố.

### 2.3. Đặc điểm của Nagios.

Giám sát toàn diện

- Khả năng để giám sát các ứng dụng, dịch vụ, hệ điều hành, giao thức mạng, hệ thống số liệu và các thành phần cơ sở hạ tầng với một công cụ duy nhất.

- API mạnh mẽ cho phép giám sát dễ dàng các ứng dụng và tùy chỉnh các dịch vụ, và các hệ thống.

Tầm Nhìn

- Tập trung theo dõi toàn bộ cơ sở hạ tầng CNTT.

-  Chi tiết thông tin trạng thái hoạt động thông qua giao diện web.

Nhận thức

- Nhanh chóng phát hiện các sự cố ngưng hoạt động của cơ sở hạ tầng.

- Cảnh báo có thể được gửi đến nhân viên kỹ thuật qua email hoặc tin nhắn SMS.

- Khả năng leo thang đảm bảo các thông báo cảnh báo đến đúng người.

Khắc phục vấn đề

- Xác nhận cảnh báo cung cấp thông tin về các vấn đề được biết đến và ứng phó vấn đề.

- Xử lý sự kiện cho phép tự động khởi động các ứng dụng thất bại và dịch vụ.

Lập kế hoạch chủ động

- Những phần bổ trợ lập kế hoạch cho xu hướng và năng lực hoạt động đảm bảo bạn nhận thức được sự xuống cáp của cơ sở hạ tầng.

- Dự kiến thời gian ngưng hoạt động cho phép tắt cảnh bóa trong quá trình nâng cấp cơ sở hạ tầng.

Báo cáo

- Báo cáo sẵn có đảm bảo SLA (Service Level Agreement_Thỏa thuận cung cấp độ dịch vụ) đang được đáp ứng.

- Cung cấp lịch sử các báo cáo ghi lại các cảnh báo, thông báo, sự cố ngưng hoạt động, và xác nhận cảnh báo.

Nhiều người sử dụng

- Với chức năng này, cho phép nhiều người sử dụng có quyền truy cập xem tình trạng của cơ sở hạ tầng.

- Những người xem riêng biệt chỉ thấy được cơ sở hạ tầng của họ.

Kiến trúc mở rộng

- Hàng trăm phần bổ trợ được phát triển bởi cộng đồng mở rộng tính năng cốt lõi của Nagios.

- Ổn định, đáng tin cậy và nền tảng vững chắc.

- Hơn 10 năm phát triển hoạt động.

- Cân bằng để giám sát hàng ngàn điểm.

- Failover đảm bảo khả năng giám sát không ngừng của các thành phần cơ sở hạ tầng CNTT quan trọng.

- Nhiều giải thưởng, phương tiện truyền thông và công nhận chứng minh giá trị của Nagios.

Cộng đồng sôi nổi

- Ước tính hơn 1 triệu người sử dụng trên toàn thế giới.

- Các hoạt động của cộng đồng được hỗ trợ miễn phí.

Mã nguồn tùy chỉnh

- Phần mềm nguồn mở.

- Không giới hạn truy cập vào mã nguồn.

- Phát hành theo giấy phép GPL (General Public License_Giấy phép công cộng).
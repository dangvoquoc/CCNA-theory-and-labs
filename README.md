<h2> CCNA theory and labs <h2>
<h3> I'll show what i have learned through this book</h3>
<p align="center">
  <img width="997" height="914" alt="image" src="https://github.com/user-attachments/assets/0f39a7ca-4961-42a0-a5cb-191a79b4d9a5" />
</p>
 
<h3>Introduction about network devices, it's written in Vietnamese bro ^^</h3>
<p align="center">
  <img margin:auto; display:block; width="452" height="159" alt="image" src="https://github.com/user-attachments/assets/2a147d54-17a8-4693-bae9-c5f97d96cd89" />
</p>
<p>Các giao thức ở lớp Liên kết dữ liệu của mạng WAN mô tả về cách thức mà gói dữ liệu được vận chuyển giữa các hệ thống trên một đường truyền dữ liệu. Các giao thức này được thiết kế cho các dịch vụ chuyển mạch điểm-đến-điểm, đa điểm, đa truy nhập.</p>
<p>Các tiêu chuẩn của mạng WAN được định nghĩa và quản lý bởi các tổ chức quốc tế sau:</p>
<ul>
<li>Liên hiệp viễn thông quốc tế - lĩnh vực tiêu chuẩn viễn thông - ITUT (International Telecommunication Union - Telecommunication Standardization Sector), trước đây là Ủy ban cố vấn điện thoại và điện tín quốc tế - CCITT (Consultative Commitee for Internation Telegraph and Telephone).</li>
<li>Tổ chức quốc tế về tiêu chuẩn  - ISO (International Organization for Standardization)</li>
<li>Tổ chức đặc trách về kỹ thuật Internet - IETF (Internet Engineering Task Force)</li>
<li>Liên hiệp công nghiệp điện tử - EIA (Electronic Industries Association)</li>
</ul>

<h3>We have components of a router here</h3>
<p align="center">
  <img width="526" height="321" alt="image" src="https://github.com/user-attachments/assets/ce5c9668-26b3-40de-b5c9-9b95da4b03db" />  
</p>
<p>
Router là một loại máy tính đặc biệt. Nó cũng có các thành phần cơ bản giống như máy tính: CPU, bộ nhớ, system bus, và các cổng giao tiếp. Tuy nhiên router được sử dụng để thực hiện một số chức năng đặc biệt. Ví dụ: router kết nối hai hệ thống mạng với nhau và cho phép 2 hệ thống này có thể liên lạc với nhau, ngoài ra router còn thực hiện việc chọn lựa đường đi tốt nhất cho dữ liệu.
</p>
<p>
Cũng giống như máy tính cần phải có hệ điều hành để chạy các trình ứng dụng thì router cũng cần phải có hệ điều hành để chạy các tập tin cấu hình. Tập tin cấu hình chứa các câu lệnh và các thông số để điều khiển luồng dữ liệu ra vào trên router. Đặc biệt là router còn sử dụng giao thức định tuyến để truyền để quyết định chọn đường đi tốt nhất cho các gói dữ liệu. Do đó, tập tin cấu hình cũng chứa các thông tin cài đặt và chạy các giao thức định tuyến trên router.
</p>

<h3>Different types of WAN connection</h3>
<p align="center">
  <img width="596" height="391" alt="image" src="https://github.com/user-attachments/assets/13990e6e-7de4-4382-941b-9b10909eb279" />
</p>
<p>
Router vừa được sử dụng để phân đoạn mạng LAN vừa là thiết bị chính trong WAN. Do đó, trên router có cả cổng giao tiếp LAN và WAN. Thực chất là các kỹ thuật WAN được sử dụng để kết nối các router. Router là thiết bị xương sống của mạng Internet. Router là thiết bị ở Lớp 3 và thực hiện chuyển gói dữ liệu dựa trên địa chỉ mạng. Router có hai chức năng chính: chọn đường đi tốt nhất và chuyển mạch gói dữ liệu. Để thực hiện chức năng này, mỗi router phải xây dựng một bảng định tuyến và thực hiện trao đổi thông tin định tuyến với nhau.
</p>


<h3>Different types of WAN protocols</h3>
<p align="center">
  <img width="663" height="428" alt="image" src="https://github.com/user-attachments/assets/3dcf54e5-0482-437b-976b-9ca1eba39a72" />
</p>
<p>
  Các chuẩn à giao thức WAN lớp vật lý: EIA/TIA-232, 449, V24, V35, X21, EIA-530, ISDN, T1, T3, E1, E3, Xdsl, Sonet (oc-3, oc-12, oc-48, oc-192)
</p>

<h3>IP VLSM</h3>
<p align="center">
  <img width="632" height="442" alt="image" src="https://github.com/user-attachments/assets/ffd96fad-17da-4781-8b6b-efc81deff862" />  
</p>

<p>VLSM là gì và tại sao phải sử dụng nó</p>
<p>Khi mạng IP phát triển lớn hơn, người quản trị mạng phải có cách sử dụng không gian địa chỉ của mình một cách hiệu quả hơn. Một trong những kỹ thuật thường được sử dụng là VLSM. Với VLSM người quản trị mạng có thể chia địa chỉ mạng có subnet mask dài cho mạng có ít host và địa chỉ mạng mạng có subnet mask ngắn cho mạng có nhiều host.</p>
<p>Khi sử dụng VLSM thì hệ thống mạng phải chạy giao thức định tuyến có hỗ trợ VLSM như OSPF, Integrated IS-IS, EIGRP, RIPv2 và định tuyến cố đinh.</p>
<p>VLSM cho phép một tổ chức sử dụng chiều dài subnet mask khác nhau trong một địa chỉ mạng lớn. VLSM còn được gọi là chia subnet trong một subnet lớn hơn giúp tận dụng tối đa không gian địa chỉ.</p>
<p>Giao thức định tuyến theo lớp địa chỉ mạng lớn hơn thành nhiều địa chỉ mạng con có kích thước khác nhau như địa chỉ mạng có 30 bit subnet mask, 255.255.255.252 để dành cho các kết nối mạng, địa chỉ mạng có 24 bit subnet mask 255.255.255.0 để dành cho các mạng có dưới 254 user</p>

<h3>IP summarization at aggregation router</h3>
<p align="center">
  <img width="604" height="435" alt="image" src="https://github.com/user-attachments/assets/cd4c0a92-5a33-44f7-ac66-b684ed44b59d" />
</p>
<p>Khi sử dụng VLSM các bạn nên cố gắng phân bổ các subnet liền nhau ở gần nhau để có thể tổng hợp địa chỉ. Trước 1997 không có tổng hợp địa chỉ hệ thống định tuyến xương sống của Internet gần như sụp đổ mấy lần</p>

<h3>hello packet OSPF</h3>
<p align="center">
  <img width="662" height="402" alt="image" src="https://github.com/user-attachments/assets/63bc3d55-f26b-49e8-8f5d-0cb648257698" />
</p>
<p>Sau đây là một số hoạt động của giao thức định tuyến theo trạng thái đường liên kết</p>
<li>Đáp ứng nhanh theo sự thay đổi của hệ thống mạng</li>
<li>Gửi cập nhật khi hệ thống mạng có sự thay đổi</li>
<li>Gửi cập nhật định kỳ để kiểm tra trạng thái đường liên kết</li>
<li>Sử dụng cơ chế hello để xác định router láng giềng có còn kết nối được hay không</li>
<p>Mỗi router gửi multicast gói hello để giữ liên lạc với các router láng giềng. Gói hello mang thông tin về vác mạng kết nối trực tiếp vào router. Ví dụ như hhinhf sau, P4 nhận biết các láng giềng của nó trong mạng Perth3 là P1 và P3. LSAs cung cấp thông tin cập nhật về trạng thái đường liên kết của các router mạng.</p>

<h3>Mixed network IP and Token Ring</h3>
<img width="802" height="450" alt="image" src="https://github.com/user-attachments/assets/655d0986-52f8-4561-9a5b-6dea228f55f2" />
<p>Tập hợp các mạng và router có cùng chỉ số định danh vùng được gọi là Area. Mỗi router trong một vùng chỉ xây dụng CSDL về trạng thái các đường liên kết trong vùng đó. Do đó, các router trong cùng một vùng sẽ có thông tin giống nhau về trạng thái các đường liên kết. Router nằm trong một vùng được gọi là router nội vùng.</p>
<h3>VLAN</h3>
<p align="center">
  <img width="702" height="469" alt="image" src="https://github.com/user-attachments/assets/3a569724-0952-45ac-b195-ec6a07550a57" />
<p>Lợi ích của VLAN là cho phép người quản trị mạng tổ chức mạng theo logic chứ không theo vật lý nữa. Nhờ đó những công việc sau có thể thực hiện dễ dàng:</p>
<li>Di chuyển máy trạm trong LAN dễ dàng</li>
<li>Thêm máy trạm vào LAN dễ dàng</li>
<li>Thay đổi cấu hình LAN dễ dàng</li>
<li>Kiểm soát giao thông mạng dễ dàng</li>
<li>Gia tăng khả năng bảo mật</li>
</p>

<h3>3 layer topology</h3>
<p align="center">
  <img width="616" height="409" alt="image" src="https://github.com/user-attachments/assets/a75fb8a0-59ae-4ac8-89b5-ebf3d8801a53" />
</p>

<h3>Control Plane and Data Plane</h3>
<p align="center">
  <img width="941" height="520" alt="image" src="https://github.com/user-attachments/assets/66b708f7-3e59-4e7a-b00f-c17f8c1514fe" />  
</p>

<h3>Wan Design Procedure</h3>
<p align="center">
  <img width="772" height="651" alt="image" src="https://github.com/user-attachments/assets/a913c97f-a02a-4a53-95bf-1d1677c0135e" />
</p>

<h3>DTE and DCE in networking</h3>
<p align="center">
  <img width="582" height="333" alt="image" src="https://github.com/user-attachments/assets/99bfd350-e455-4ce1-9528-f64068cbeffb" />
</p>
<p>Một kết nối có một là thiết bị DTE (client) và đầu kia là DCE (ISP). Kết nối giữa 2 DCE chính là mạng WAN của nhà cung cấp dịch vụ. CPE thông thường là router của khách hàng đóng vai trò là DTE.</p>

<h3>Connection between DTEs</h3>
<p align="center">
  <img width="997" height="465" alt="image" src="https://github.com/user-attachments/assets/e15934ab-6f4c-4d62-a5e3-3ee36dcdcbe9" />
</p>

<h3>protocol concept of telecom network</h3>
<h3>Encapsulating HDLC frame</h3>
<li>Truyền nối tiếp đặt cơ sở trên giao thức hướng bit. Giao thức hướng bit tuy có hiệu quả hơn nhưng thường mang tính độc quyền. Năm 1979, ISO đã chấp thuận HDLC là giao thức chuẩn hướng bit của lớp Liên Kết Dữ Liệu cho ISDN</li>
<p>Link Access Procedure for Modem thực hiện đóng gói dữ liệu cho đường truyền nối tiếp đồng bộ. Sự chuẩn hóa này đã giúp cho các tổ chức khác áp dụng và mở rộng giao thức này. Từ năm 1981, ITU-T đã phát triển một loạt các phiên bản của HDLC. Sau đây là một ví dụ, những giao thức này được gọi là giao thức truy cập đường liên kết</p>
<li>Link Access Procedure, Balanced (LAPB) cho X.25</li>
<li>Link Access Procedure on the D channel (LAPD) cho ISDN</li>
<li>Link Access Procedure for Modems (LAPM) và PPP cho modems</li>
<li>Link Access Procedure for Frame Relay(LAPF) cho Frame Relay</li>
<p>HDLC cung cấp cơ chế truyền đồng bộ không có lỗi giữa 2 điểm. HDLC định nghĩa cấu trúc frame Lớp 2 cho phép điều khiển luồng theo cơ chế cửa sổ trượt, kiểm tra lỗi và báo nhận. Frame dữ liệu hay frame điều khiển đều có cùng một định dạng frame.</p>

<h3>PPP Authentication with CHAP theory</h3>
<p align="center">
  <img width="746" height="875" alt="image" src="https://github.com/user-attachments/assets/35f2c08f-f56c-49f2-8b75-0ef01f320dc5" />
</p>
<h3>CHAP Authentication configuration</h3>
<p align="center">
  <img width="780" height="438" alt="image" src="https://github.com/user-attachments/assets/ec4b4ff2-351a-4827-9e15-f4879ce71352" />
</p>

<h3>Wireshark nightmare 1 thời, chả hiểu sao h mình theo network@@</h3>
<p align="center">
  <img width="744" height="692" alt="image" src="https://github.com/user-attachments/assets/7d05be30-4ef0-4e50-8467-6345cef0df69" />
</p>

<h3>ISDN services</h3>
<p align="center">
  <img width="846" height="490" alt="image" src="https://github.com/user-attachments/assets/08b1134e-e24c-48ae-af7a-5fd87d221592" />  
</p>
<h3>DDR Services Configuration</h3>
<p align = "center">
  <img width="577" height="381" alt="image" src="https://github.com/user-attachments/assets/a0fdd130-04ff-4cc6-a1c2-f3db6a0389b5" />
</p>
<p>Trong đó, group number xác định số thứ tự dialer-list tương ứng. Do đó chỉ số này phải giống với chỉ số của dialer - list group number. Mỗi một cổng chỉ có một dialer-group nhưng một dialer-list có thể tương ứng cho nhiều cổng khác nhau.</p>
<h3>Này giống viết docs và policy cho cty quá :)))</h3>

<h3>Băng thông và điều khiển luồng trong Frame Relay</h3>
<p>Tốc độ đường truyền nối tiếp trong mạng Frame Relay chính là tốc độ truy cập hay tốc độ port. Tốc độ port thường nằm trong khoảng 64kb/giây đến 4Mb/giây. Một số nhà cung cấp dịch vụ còn cung cấp tốc độ lên đến 45Mb/giây.</p>
<p>Trên một đường truyền vật lý hoạt động đồng thời nhiều kết nối ảo PVC, mỗi VC có một lượng băng thông riêng nhất định. Băng thông này chính là băng thông cam kết của nhà cung cấp dịch vụ, gọi là CIR (Committed Information Rate). Nhà cung cấp dịch vụ đồng ý chấp nhận lượng bit này trên một VC. (giống IP-VPN)</p>
<p>Mỗi CIR có giá trị nhỏ hơn tốc độ port. Nhưng tổng các CIR trên mọi port lại lớn hơn tốc độ port, thường là lớn hơn khoảng 2-3 lần, vì các kênh ảo hoạt động với dung lượng khác nhau tại mỗi thời điểm và không đồng thời sử dụng tối đa băng thông của mình.</p>
<p>Khi truyền frame, mỗi bit được phát đi với tốc độ port. Do đó nếu lượng bit trung bình trên VC đã bằng với CIR thì sẽ phải có khoảng thời gian nghỉ giữa 2 frame.</p>
<p>Frame Realy Switch cũng chấp nhận frame được gửi từ DTE với tốc độ cao hơn tốc CIR. Như vậy mỗi VC có thể sử dụng băng thông theo nhu cầu lên đến mức tối đa là tốc độ port. Môt số nhà cung cấp có thể quy ước mức độ tối này thấp hơn tốc độ port. Mức chênh leehcj giữa CIR và mức tối đa gọi là ERI (Ecs Information Rate).(giống cấu hình QoS layer 3 nè)</p>
<p>Khoảng thời gian (chu kỳ) để tính tốc độ được gọi là Tc (Committed Time). Số lượng bit trong một chu kỳ được gọi là Bc (Committed Burst). Số lượng bit chênh lệch giữa Bc và mức tối đa (là tốc độ vật lý của đường truyền) được gọi là Be (Ecs Burst)</p>
<p>Mặc dù switch vẫn chấp nhận các frame được truyền với tốc độ vượt quá CIR, nhưng mỗi frame vượt tiêu chuẩn này được switch đánh dấu bằng cách đặt bit DE (Discard Eligible) của frame lên 1</p>
<p>Switch có một đồng hồ đếm bit tương ứng với mỗi VC. Khi switch nhận frame vào, nếu frame này vượt quá số lượng Bc thì frame sẽ được đánh dấu bit DE. Frame nhận vào sẽ bị hủy bỏ khi số lượng bit vượt quá Bc + Be. Cuối mỗi chu kỳ Tc switch sẽ khởi động lại đồng hồ đếm bit.</p>
<p>Frame sau khi được nhận vào thì sẽ được xếp hàng đợi chuyển ra. Tuy nhiên nếu số lượng frame quá nhiều sẽ làm tràn hàng đợi, thời gian trễ sẽ tăng lên. Một số giao thức lớp trên có yêu cầu truyền lại khi không nhận được dữ liệu sau một thời gian nhất định. Nhưng do thời gian trễ quá lớn, yêu cầu truyền lại không thể thực hiện được. Trường hợp này sẽ làm tụt giảm thông lượng mạng nghiêm trọng</p>
<p>Để tránh sự cố này, Frame Relay Switch có chính sách hủy bớt frame trong hàng đợi để giữ hàng đợi không quá dài. Những frame nào có bit DE sẽ đucợ đặt lên hủy bỏ trước.</p>
<p>Khi switch nhận thấy hàng đợi của nó đang tăng lên thì nó sẽ thông minh cố gắng tìm cách làm giảm dòng truyền frame từ DTE đến nó. Switch thực hiện đặt bit báo nghẽn ECN (Explicit Congestion Notification) vào phần địa chỉ của frame mà switch sẽ truyền lại cho DTE.</p>
<p>Bit FECN (Forward ECN) được cài đặt vào mỗi frame mà switch sẽ gửi ra đường truyền đang bị nghẽn để thông báo nghẽn cho các thiết bị kế tiếp. Bit BECN (Back ECN) được cài đặt trong mỗi frame mà switch sẽ gửi ngược lại cho thiết bị trước nó. DTE sẽ nhận được các frame có bit ECN được cài đặt trong đố và đó sẽ giảm dòng truyền frame lại cho đến khi không còn nghẽn mạch nữa.</p>
<p>Nếu nghẽn mạch xảy ra trên đường kết nối giữa các switch thì DTE bên dưới cũng có thể nhận được các thông báo nghẽn mạch mặc dù nó không phải là thiết bị gây ra nghẽn mạch</p>
<p>Các bit DEM, FECN, BECN là những bit nằm trong trong phần địa chỉ của frame LAPP</p>

<h3>Finishing reading the last page of this book</h3>
<img width="656" height="501" alt="image" src="https://github.com/user-attachments/assets/05a1fb95-3653-4e5a-b54f-ebd0881385e8" />

















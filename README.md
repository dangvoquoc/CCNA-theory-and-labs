<h2> CCNA theory and labs <h2>
<h3> I'll show what i have learned through my CCNA journey</h3>
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
<img width="811" height="625" alt="image" src="https://github.com/user-attachments/assets/72f8de0b-7a80-4ae9-9e26-751261c3e812" />
<h3>Nấm Mộc Nhung</h3>
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ab9d25c8-486b-4582-8c7f-7ce77ec2c751" />
<h3>VLAN</h3>
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b175b194-efd2-4020-b789-ac626c86e908" />
<h3>Citizen watch</h3>
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/27c21552-b912-419e-bd1c-bf26293852c0" />
<h3>3 layer topology</h3>
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/75361472-4cc8-4871-a3b9-2eb5b9039a41" />
<h3>Hạt lanh</h3>
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/48afa5c8-2c89-46cd-bd94-6d6a85c97b5e" />
<h3>my motivation</h3>
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b6dae129-5596-42b6-b04e-ff6864edd517" />
<h3>Control Plane and Data Plane</h3>
<img width="941" height="520" alt="image" src="https://github.com/user-attachments/assets/66b708f7-3e59-4e7a-b00f-c17f8c1514fe" />
<h3>Wan Design Procedure</h3>
<img width="772" height="651" alt="image" src="https://github.com/user-attachments/assets/a913c97f-a02a-4a53-95bf-1d1677c0135e" />
<h3>DTE and DCE in networking</h3>
<img width="1162" height="690" alt="image" src="https://github.com/user-attachments/assets/07e2fbd4-d14e-4196-bcbd-72354f47579e" />
<h3>Connection between DTEs</h3>
<img width="997" height="465" alt="image" src="https://github.com/user-attachments/assets/e15934ab-6f4c-4d62-a5e3-3ee36dcdcbe9" />
<h3>core concept of network</h3>
<img width="1137" height="775" alt="image" src="https://github.com/user-attachments/assets/84d08e02-ddc0-4cfb-8bce-7dc03ea17b76" />
<h3>PPP Authentication with CHAP theory</h3>
<img width="746" height="875" alt="image" src="https://github.com/user-attachments/assets/35f2c08f-f56c-49f2-8b75-0ef01f320dc5" />
<h3>CHAP Authentication configuration</h3>
<img width="780" height="438" alt="image" src="https://github.com/user-attachments/assets/ec4b4ff2-351a-4827-9e15-f4879ce71352" />
<h3>Wireshark nightmare 1 thời, chả hiểu sao h mình theo network@@</h3>
<img width="744" height="692" alt="image" src="https://github.com/user-attachments/assets/7d05be30-4ef0-4e50-8467-6345cef0df69" />
<h3>ISDN services, vẫn chưa hiểu bản chất ISDN với PPP và HDLC</h3>
<img width="846" height="490" alt="image" src="https://github.com/user-attachments/assets/08b1134e-e24c-48ae-af7a-5fd87d221592" />
<h3>DDR Services Configuration</h3>
<img width="1115" height="616" alt="image" src="https://github.com/user-attachments/assets/3d716fac-6a77-4c25-a43f-69116db8f342" />



















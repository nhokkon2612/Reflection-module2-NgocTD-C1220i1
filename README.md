# Reflection-module2-NgocTD-C1220i1


<h1>SAU KHI KẾT THÚC MODUL 2 </h1> 
MỤC TIÊU PHẢI ĐẠT ĐƯỢC :<br>
+Thành thạo PHP <br>
+Vẽ được UML cho bài code<br>
+Thuần thục lập trình hướng đối tượng (oop) <br>
+Thiết kế được Cơ Sở Dữ Liệu và sử dụng được SQL-mySQL<br>
+Phát triển case study là 1 PHP WEB  bán đồ chơi trẻ em xịn bằng 25% shopee.
<br>
<br>
------------------------------------------------------
<br>
<br>
<h1>HÀNH ĐỘNG ĐỂ ĐẠT ĐƯỢC MỤC TIÊU TRÊN</h1>
<br>
<br>
+ Mỗi bài code vẽ UML để giải<BR>
+ Ngồi bàn 1 mỗi khi học lỹ thuyết để tiếp thu chuẩn chỉ<br>
+ Đi hỏi bài ngay khi không tự giải quyết được ( sau thời gian tìm tòi )<br>
+ Time box thời gian khi học tại nhà 4hours/day (nhiều hơn rất t)ốt<br>
+ Thứ 7 lên CodeGym học với các anh <br>
+ Ngủ đủ 6hours/day <br>
+ Giảm thời gian xem youtube (không liên quan đến việc học) xuống 45min <br>
<br>
<br>
<br>
+++++++++++++++++++++++++++++++++++++++++++++++++++++
<br>
<br>
<br>
<br>


























<h1>lesson 16 ngày 24-2-2021</h1>
<br>
<b>Thiết kế cơ sở dữ liệu: </b> <br>
+ B1: Xác định mục đích cửa cơ sở dữ liệu <br>
<br>
+ B2: Tìm hiểu và tổ chức thông tin cần lưu trữ<br>
<br>
+ B3: Chia các thông tin vừa tìm hiểu vào các bảng (bộ dữ liệu liên quan với nhau thì cho vào 1 bảng, mỗi bẳng có 1 khóa chính, lọc các dữ liệu không liên quan tới khóa chính sang 1 bảng khác) <br>
<br>
+ B4: Xác định các trường dữ liệu <br>
<br>
+ B5: Xác định khóa chính của các bảng 
<br>
<br>
+ B6: Xác định mối quan hệ giữa các bảng (1-1,1-n,n-n trường hợp 2 bẳng có quan hệ n-n: cần 1 bảng trung gian với "cặp khóa chính" là khóa chính của 2 bảng quan hệ)
<br>
<br>
+ B7: Làm mịn thiết kế 
<br>
<br>
+ B8: Chuẩn hóa dữ liệu (chuẩn 1nf-2nf-3nf).
<br>
<br>
<br>
<br>
<br>
<br>
<br>
-----------------------------------------------------------------------------------------------















<h1>lesson 15 ngày 23-2-2021</h1>
<br>
So Sánh giữa DBMS(hệ quản trị cơ sở dữ liệu) và RDBMS(hệ quản trị cơ sở dữ liệu quan hệ)<br>
DBMS và RDBMS là hệ thống quản lý cơ sở dữ liệu, RDBMS kế thừa của DBMS nhưng nhanh hơn hiệu quả hơn,loại bỏ các hạn chế của DBMS do :<br>

+ DBMS theo mô hình điều hướng còn RDBMS theo mô hình 'quan hệ' (dữ liệu lưu trữ dưới dạng bảng và các bảng dữ liệu có mối quan hệ với nhau) <br>
+ RDBMS sử dụng sử dụng chuẩn hóa hạn chế tối đa việc dữ liệu hay bản sao dữ liệu bị lưu trữ lung tung như  trong DBMS <br>
+ RDBMS dễ thực hiện các thao tác với dữ liệu,truy cập cũng nhanh hơn (thêm,sửa,xóa,backup,restore...) hơn so với DBMS vì chuẩn hóa dữ liệu hơn DBMS <br>
+ Trong DBMS không có khóa và chỉ mục như ở RDBMS với mục đích thiết lập mối quan hệ giữa các bảng<br>
  <br>
  <br>
  Ngoài CSDL quan hệ còn 1 số kiểu mô hình CSDL: <br>
    - CSDL Phân cấp (hierarchical)<br>
    - CSDL Mạng (net work)<br>
    - CSDL Đồ Thị (Graph)<br>
    - CSDL Đối tượng
      <br>
      <br>
      SQL : <br>
      Là ngôn ngữ để thao tác,làm việc với với cơ sở dữ liệu
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
----------------------------------------------------------------------------------------    


<h1>lesson 6   ngày 1-2-2021</h1>
<br>

Hôm nay học được : <br>
<b> Abstract Class</b> <br>
+ Nó là một class có tính trừu tượng rất cao đến mức không thể tạo được các đối tượng ở lớp đó thì gọi là abstract class.<br>
+ Bắt buộc phải chứa abstract method và có thể có method thông thường.<br>
+ abstract method là method chỉ có khai báo (tên và tham số đầu vào).<br>
+ Mức truy cập các abstract method phải ở public hoặc protected để lớp kế thừa có thể định nghĩa lại.<br>
+ Không dùng từ khóa final cho khai báo abstract class và abstract method.<br>
  <br>
  <br>
  <b>interface.</b><br>
  +Có thể hiểu đây là một dạng bảng thiết kế cho -"method"- mà bất kỳ Class nào cũng có thể có. Một interface chứa các hành vi mà một class triển khai. <br>
  +Interface không phải là một lớp đối tượng .<br>
  +Tất cả các hàm trong interface đều ở dạng khai báo và không được định nghĩa (giống lớp abstract).<br>
  +Interface không thể khởi tạo.<br>
  <br>
  <br>
  Khi nào sử dụng  <b>Abstract class</b> và khi nào sử dụng <b>interface</b>:
  <Br>
    - Abstract thường được sử dụng trong trường hợp class kế thừa từ nó cùng bản chất<br>
      <br>
    - Interface thường được sử dụng trong trường hợp các kế thừa không có cùng bản chất như nhau nhưng có "phương thức giống nhau  ---  VD: object chim không cùng class với object tên lửa , không có bản chất nào chung nhưng nó có chung method bay, lúc này sẽ sử dụng interface .


<br>
<br>
<br>
<br>

--------------------------------------------------------------------------------------------------

<br>
<br>
<br>
<br>
<br>
<br>





<h1>lesson 5   ngày 29-1-2021</h1>
<br>
<br>
<br>
Hôm nay học được : <br>
<br>
+ Vòng đời của một đối tượng :<br>
 Khởi tạo đối tượng: __construct() --> sử dụng đối tương --> Hủy đối tương __destruct()<br>
+ Các dạng kế thừa : <BR>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; single inheritance (đơn kế thừa): Lớp con chỉ kế thừa từ 1 lớp cha <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; multiple inheritance (đa kế thưa): Lớp con kế thừa từ nhiều lớp cha <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; multilevel inheritance (kế thừa đa tầng): Lớp con kế thừa lớp cha , lớp cha kế thừa lớp ông (có thể có nhiều tầng kế thừa hơn).



Cú pháp: <br>

+ class SubClass extends SuperClass{}; trong đó: - từ khóa extends được sử dụng để kế thừa 1 lớp. - SubClass là tên lớp con. - SuperClass là tên lớp cha.<br>
+ Ghi đè phương thức(Method overriding) cho phép lớp con định nghĩa lại phương thức đã định nghĩa trước đó của lớp cha.<br>

+ Từ khóa parent sử dụng trong một lớp con truy xuất các thuộc tính và phương thức của lớp cha.<br>

+ Từ khóa Final hạn chế tối đa việc ghi đè, ngăn chặn kế thừa từ một lớp v>à việc ghi đè phương thức<br>

<br>
<br>
<br>










-------------------------------------------------------------------------------------------
<br>
<br>
<br>
<br>
<br>
<br>


<h1>Buổi 1 ngày 25-1-2021</h1>
Hôm nay đã học được : <br>
Lamp là gì , hiểu được vòng chạy từ client qua server đến web server tiếp tục gửi về cho application server, application server lấy dữ liệu từ CSDL và trả về web server, web server response lại cho cl <br>
Giao thức : cách thức giao tiếp giữa client và server<br>
Web tĩnh là web được fix cứng người dùng không tương tác trực tiếp với web được,thêm tương tác trực tiếp giữa người dùng với web thì web sẽ thành web tĩnh  <br>
<br>
<br>
<br>
<br>
<br>
<br>---------------------------------------------------------------------------------------------<br>

<br>
<br>
<br>
<h1>Buổi 2 ngày 26-1-2021</h1>
<br>
<br>
Hôm nay hạc được :<br>
Chèm 1 file PHP a vào 1 file PHP b với Require / include  
<br> phân biệt 2 ông này <br>
require và include đề để đưa  1 ông file PHP a vào bên trong ông PHP b<br>
Khác nhau: Khi gặp lỗi trong quá trình thưc hiện ông require đưa ra cảnh báo lỗi và dừng luôn trương trình   còn ông include sẽ tạo ra cảnh báo và chạy trương trình đến phần bị lỗi thì dừng <br>
<br>
<b> require_once :</b> thực hiện require là thêm ông PHP a vào ông PHP b, chính vì vậy khi require lần 2(cái này do ông code quên ) tức thêm lần 2 sẽ có nhiều thứ bị trùng tiêu biểu tên hàm ---> lỗi!!! Do vậy ông require_once giúp check lần thực hiện  require_once lần 2 lần 3 đều được hiểu là đã require rồi và không thực hiện lại nữa
<br>
<br>
<b>include_once: </b> Giống ông require_one  include_once lần 2 -3 ... chỉ tính 1 lần 
<BR>
<BR>Ông nào hay quên thì xài <b>require_once</b>  và  <b>include_once</b>  để nó kiểm tra hộ !

<br>
<br>
<br>
<br>
<h4> Mảng associative</h4>
Ta dùng vòng lặp  "foreach" để duyệt mảng<br>
<b>foreach( $nameArry  as $key => $v)</b>






<Br>
<Br>
<Br>
<Br>
--------------------------------------------------------------------------------------------------
<br>
<br>
<br>
<h1>Buổi 3 ngày 27-1-2021 </h1>
<br>
<br>
<br>
Hôm nay học được:<br>
+ Access modifier là các từ khoá được sử dụng để quy định mức độ truy cập đến lớp và các thành phần của lớp

Các mức truy cập:

+ public: có thể truy cập từ bất cứ đâu<br>
+ private: các phương thức và thuộc tính chỉ được phép truy xuất trong cùng một lớp<br>
+ protected: các phương thức và thuộc tính được phép truy xuất trong cùng một lớp và ở các lớp con (kế thừa) <br>
  <br>
+     __construct() vs __destruct()

Để can thiệp vào quá trình khởi tạo đối tượng, chúng ta sử dụng hàm __construct() <br>


Để can thiệp vào quá trình huỷ đối tượng, chúng ta sử dụng hàm __destruct()<br>
<br>
<br>
<br>
<br>
<br>
---------------------------------------------------------------
<br>
<br>
<br>
<h1>Buổi 4 ngày 28-1-2021</h1>
Hôm nay học được: <br>
<br>
+ Namespace (tên miền không gian) là một hình thức để đóng gói các hạng mục có liên quan lại với nhau<br> <br>
+ Trong PHP, namespace được thiết kế để giải quyết 2 vấn đề mà các tách giả của các thư viện và ứng dụng thường gặp phải khi cố gắng tạo ra các đối tượng hoặc hàm có thể tái sử dụng được<br> <br>
+ Các tên gọi bị trùng nhau giữa những lớp/hàm được tạo ra, so với các lớp/hàm có sẵn của PHP, hoặc các lớp/hàm do một người khác viết<br> <br>


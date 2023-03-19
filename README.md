# TRANSPORT-AND-SHIPPING-REPORT-
Link report: https://app.powerbi.com/reportEmbed?reportId=8dc48af5-fe6b-4678-ad02-75ec54e054be&autoAuth=true&ctid=588b13a3-653b-4cf7-8ac0-59847eb2dc88

1. Challenges
Đây là bộ dữ liệu của một doanh nghiệp vận chuyển hàng hóa (forwarder) về tất cả các thông tin có liên quan của các đơn hàng vận chuyển (shipment). 
Bộ dữ liệu ban đầu dưới dạng file Excel với số lượng cột rất lớn (121 cột) và dữ liệu không tối ưu cho việc làm báo cáo Power BI. Dữ liệu bị blank cũng rất nhiều, điều này khiến cho quá trình làm sạch dữ liệu (cleaning data), xây dựng mô hình (data modelling) cũng như trực quan hóa (visualizations) trở nên không hề đơn giản. 
Báo cáo Power BI này được tạo ra với mục đích làm sạch, giữ lại và lập mô hình với những trường dữ liệu cần thiết, trực quan hóa dữ liệu nhằm đơn giản hóa việc tìm kiếm insights và giúp cho nhà quản lí có thể phân tích và đưa ra quyết định tốt hơn.
Báo cáo khai thác dữ liệu với mong muốn tìm hiểu và phân tích nhằm trả lời một số câu hỏi :

(1) Lợi nhuận, chi phí, doanh thu: Thu nhập, chi phí lợi nhuận của doanh nghiệp là bao nhiêu? Transportation Modes, Carriers, Consignors, Consignees nào đem lại lợi nhuận cao nhất cho doanh nghiệp ?, …

(2) Chi nhánh, phòng ban, nhân sự nào đang thể hiện tốt nhất ?

(3) Đâu là lộ trình có số lượng đơn nhiều nhất ?
…
2. Solutions
Báo cáo đã trình bày và phân tích dựa trên 4 mục chính:

o	Financials (Tình hình tài chính): gồm các con số về tổng thu nhập (Total Income), tổng chi phí (Total Expense), Tổng lợi nhuận (Total Profit), Lợi nhuận cận biên (Profit Margin); đánh giá lợi nhuận (Total Profit) của doanh nghiệp theo Transportation Modes, Carriers, Consignors, Consignees
Từ đó trả lời được câu hỏi (1) nêu ra ở phần 1
Ghi chú: Do hạn chế vì thiếu quá nhiều dữ liệu thời gian (cụ thể chỉ có khoảng 20/224 chuyến hàng có đủ dữ liệu này), báo cáo không khai thác các metrics về tình hình tài chính (Income, Expense, Profit, …) theo dimensions thời gian. 

o	Performance: nhằm đánh giá hiệu quả công việc theo tiến độ công việc (Job Status), chi nhánh (Job Branch), phòng ban (Job Department) và nhân sự phụ trách (Job Operator)
Từ đó trả lời được câu hỏi (2) nêu ra ở phần 1

o	Origin and Destination: Thống kê số lượng đơn hàng theo điểm khởi hành (Origin), điểm kết thúc (Destination) và Transportation Modes.
Từ đó trả lời được câu hỏi (3) nêu ra ở phần 1

o	Shipment Information: Thông tin chi tiết về các đơn hàng phục vụ mục đích tra cứu
...

3. Findings
-	Vận tải đường biển (SEA) đem lại lợi nhuận cao nhất 
-	MAERSK là hãng vận chuyển đem lại lợi nhuận lớn nhất
-	HAGLOBAL vừa là đơn vị gửi vừa là đơn vị nhận đóng góp lợi nhuận lớn nhất
-	HAROON ALI là nhân sự phụ trách nhiều đơn nhất và đem lại thu nhập lớn nhất
-	Chi nhánh Birmingham là chi nhánh đem lại thu nhập lớn nhất
-	Phòng ban FIS là phòng ban đem lại thu nhập lớn nhất
-	Lộ trình từ cảng London Heathrow đến cảng Jebel Ali theo đường biển (SEA) có nhiều chuyến hàng nhất

4. Impacts
Từ những findings trên, báo cáo sẽ giúp cho doanh nghiệp nhìn nhận được tình hình hiện tại, xác định được những nhân tố đem lại lợi nhuận lớn, từ đó tập trung đẩy mạnh phát triển những nhân tố đó nhằm tăng số lượng đơn hàng, lợi nhuận cho doanh nghiệp.

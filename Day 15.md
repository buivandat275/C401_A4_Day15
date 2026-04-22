# Thành viên
- Bùi Văn Đạt - 2A202600355
- Dương Văn Hiệp - 2A202600052
- Hoàng Thái Dương - 2A202600073
- Nguyễn Minh Quân - 2A202600181
- Hoàng Quốc Chung - 2A202600070
- Trịnh Đức ANh - 2A202600499

# Phần 1+2

**Hotel Booking Chatbot System**

**1\. Project Overview**

## **1.1. Giới thiệu dự án**

Đề tài của nhóm là xây dựng **chatbot đặt phòng khách sạn** nhằm hỗ trợ khách hàng tìm kiếm thông tin, kiểm tra phòng trống, nhận báo giá và thực hiện đặt phòng thông qua hội thoại tự nhiên. Hệ thống được định hướng như một công cụ hỗ trợ tự động 24/7, giúp cải thiện trải nghiệm khách hàng và giảm tải cho bộ phận chăm sóc khách hàng.

## **1.2. Bài toán cần giải quyết**

Trong thực tế, khách hàng thường cần được hỗ trợ nhanh về giá phòng, tình trạng phòng trống, tiện ích, chính sách hủy phòng và các yêu cầu liên quan trước khi quyết định đặt phòng. Nếu xử lý hoàn toàn thủ công, doanh nghiệp dễ gặp tình trạng phản hồi chậm, tốn nhân lực và thiếu nhất quán trong tư vấn. Vì vậy, chatbot được xây dựng để tự động hóa các truy vấn phổ biến và hỗ trợ quy trình đặt phòng hiệu quả hơn.

## **1.3. Mục tiêu dự án**

Dự án hướng đến các mục tiêu chính sau:

* Hỗ trợ khách hàng tra cứu thông tin khách sạn nhanh chóng;  
* Kiểm tra tình trạng phòng và giá phòng theo thời gian thực;  
* Hỗ trợ đặt, sửa hoặc hủy booking ở mức cơ bản;  
* Giảm tải cho nhân viên lễ tân và chăm sóc khách hàng;  
* Nâng cao trải nghiệm người dùng và tăng tỷ lệ chuyển đổi đặt phòng.

## **1.4. Người dùng chính**

Hệ thống phục vụ ba nhóm người dùng chính:

* **Khách hàng**: tìm phòng, hỏi thông tin, đặt hoặc chỉnh sửa booking;  
* **Nhân viên CSKH/lễ tân**: tiếp nhận các trường hợp phức tạp được chatbot chuyển tiếp;  
* **Bộ phận vận hành khách sạn**: theo dõi hiệu quả hỗ trợ và tối ưu quy trình phục vụ.

## **1.5. Chức năng chính**

Trong phạm vi đề tài, chatbot có các chức năng chính:

* Trả lời câu hỏi thường gặp về khách sạn;  
* Tư vấn loại phòng phù hợp theo nhu cầu;  
* Kiểm tra phòng trống và giá phòng;  
* Hỗ trợ tạo booking cơ bản;  
* Hỗ trợ sửa hoặc hủy booking;  
* Chuyển tiếp cho nhân viên khi cần.

## **1.6. Ý nghĩa thực tiễn của dự án**

Đây là một đề tài có tính thực tiễn cao vì chatbot không chỉ hỗ trợ hỏi đáp, mà còn gắn trực tiếp với hoạt động kinh doanh của khách sạn. Hệ thống có khả năng giúp doanh nghiệp nâng cao chất lượng dịch vụ, tối ưu chi phí vận hành và tăng khả năng giữ chân khách hàng.

---

# **2\. Enterprise Context**

## **2.1. Bối cảnh doanh nghiệp**

Hệ thống được đặt trong bối cảnh một khách sạn hoặc chuỗi khách sạn có nhu cầu số hóa quy trình chăm sóc khách hàng và hỗ trợ đặt phòng. Chatbot không hoạt động độc lập mà là một phần trong hệ sinh thái vận hành của doanh nghiệp, kết nối với website, ứng dụng hoặc các kênh giao tiếp trực tuyến.

## **2.2. Dữ liệu hệ thống sử dụng**

Chatbot có thể xử lý nhiều loại dữ liệu khác nhau, bao gồm:

* Thông tin phòng, giá phòng, tiện ích và chính sách;  
* Tình trạng phòng trống theo thời gian thực;  
* Thông tin khách hàng như họ tên, số điện thoại, email;  
* Thông tin booking như mã đặt phòng, ngày nhận/trả phòng;  
* Lịch sử hội thoại và log vận hành.

## **2.3. Mức độ nhạy cảm của dữ liệu**

Dữ liệu mà hệ thống xử lý có mức độ nhạy cảm từ trung bình đến cao. Trong đó, dữ liệu mô tả dịch vụ có độ nhạy cảm thấp hơn, còn thông tin cá nhân khách hàng và dữ liệu booking là dữ liệu nhạy cảm, cần được bảo vệ và kiểm soát chặt chẽ.

## **2.4. Các ràng buộc enterprise chính**

* **Bảo mật dữ liệu:** Hệ thống xử lý thông tin cá nhân và dữ liệu đặt phòng nên cần có cơ chế phân quyền, kiểm soát truy cập và lưu vết rõ ràng.    
* **Độ chính xác nghiệp vụ:** Chatbot phải trả lời đúng về giá phòng, tình trạng phòng trống và chính sách. Sai sót ở các nội dung này có thể ảnh hưởng trực tiếp đến trải nghiệm khách hàng và uy tín doanh nghiệp.   
* **Khả năng tích hợp hệ thống:** Để hoạt động thực tế, chatbot cần kết nối với các hệ thống như booking engine, PMS hoặc CRM. Đây là điều kiện cần để chatbot không chỉ dừng ở mức hỏi đáp mà có thể hỗ trợ giao dịch thật.

## **2.5. Nhu cầu audit và human-in-the-loop**

Trong môi trường doanh nghiệp, hệ thống cần có khả năng lưu lại lịch sử hội thoại, dữ liệu được truy xuất và các thao tác booking liên quan để phục vụ kiểm tra và xử lý sự cố. Đồng thời, với các trường hợp phức tạp như khiếu nại, hoàn tiền hoặc yêu cầu đặc biệt, chatbot cần chuyển tiếp sang nhân viên thay vì tự xử lý hoàn toàn.

## **2.6. Mô hình triển khai đề xuất**

Nhóm đề xuất mô hình **Hybrid Deployment** cho hệ thống.

Lý do là vì lớp chatbot và AI có thể tận dụng cloud để mở rộng và triển khai nhanh, trong khi dữ liệu nhạy cảm và các thao tác booking nên được giữ trong lớp backend do doanh nghiệp kiểm soát. Mô hình này giúp cân bằng giữa hiệu quả phát triển, khả năng mở rộng và yêu cầu bảo mật.

## **2.7. Kết luận**

Chatbot đặt phòng khách sạn là một hệ thống có tác động trực tiếp đến trải nghiệm khách hàng và hoạt động kinh doanh của doanh nghiệp. Vì vậy, khi phân tích trong bối cảnh enterprise, cần đặc biệt chú ý đến ba yếu tố chính là bảo mật dữ liệu, độ chính xác nghiệp vụ và khả năng tích hợp với hệ thống hiện có. Đây cũng là cơ sở để lựa chọn mô hình triển khai hybrid cho dự án.

# Phần 3

# **3\) Deployment Choice — Hybrid (On-premises \+ AWS)**

Theo yêu cầu Sprint 1, nhóm phải chọn **Cloud, On-prem hoặc Hybrid** và nêu rõ lý do chọn. Với **Hotel Booking Chatbot System**, phương án hợp lý nhất là **Hybrid** vì hệ thống vừa có dữ liệu booking nhạy cảm, vừa cần tận dụng khả năng scale và triển khai nhanh của cloud.

## **3.1 Kiến trúc Hybrid đề xuất**

### **Phần đặt On-premises**

Đây là phần nên giữ ở phía khách sạn hoặc private network nội bộ:

* **PMS / Booking Engine**  
* **Room inventory master**  
* **Pricing / promotion master**  
* **Customer profile / PII**  
* **Booking transaction logs**  
* **Local integration service** kết nối PMS

### **Phần đặt trên AWS**

Đây là phần nên đặt trên cloud để dễ scale và triển khai nhanh:

* **Chat widget / chatbot backend**  
* **Conversation orchestration**  
* **Intent classification**  
* **FAQ / RAG layer**  
* **Session handling**  
* **Monitoring / logging**  
* **API layer** cho website/app/chat channels

### **Kết nối giữa 2 bên**

* **AWS Site-to-Site VPN** nối AWS VPC với mạng on-premises. AWS mô tả Site-to-Site VPN là cách kết nối VPC với hạ tầng on-prem bằng IPsec VPN; AWS dùng 2 tunnel cho redundancy.

---

## **3.2 Vì sao chọn Hybrid thay vì Cloud-only?**

### **Lý do 1: dữ liệu booking và thông tin khách hàng không nên đi toàn bộ lên cloud**

Hotel chatbot xử lý:

* tên khách  
* số điện thoại  
* email  
* ngày check-in/check-out  
* booking status  
* special request

Nếu đẩy toàn bộ PMS \+ booking data lên cloud ngay từ MVP thì:

* tăng rủi ro lộ PII  
* khó giải thích data governance  
* khó thuyết phục về audit

### **Lý do 2: PMS thường là hệ thống cũ, khó tích hợp trực tiếp từ cloud**

Nhiều khách sạn dùng PMS/booking engine cũ, có:

* private IP  
* VPN nội bộ  
* API hạn chế  
* schema khó đồng bộ

Giữ lớp integration ở on-prem sẽ an toàn và thực tế hơn.

### **Lý do 3: AWS phù hợp với phần tải biến động**

Phần chatbot là phần có traffic dao động:

* giờ cao điểm  
* campaign  
* mùa du lịch  
* lễ/Tết

Cloud phù hợp hơn cho:

* chatbot API  
* orchestration  
* logging  
* scale web/app access

### **Lý do 4: Hybrid rẻ hơn full on-prem ở giai đoạn MVP**

AWS cho phép dùng EC2 nhỏ, storage vừa phải, trả theo mức dùng; EC2 on-demand có các instance nhỏ như t4g.small với giá $0.0168/giờ ở us-east-1, phù hợp cho MVP nhẹ.

---

## **3.3 Vì sao không chọn On-prem toàn bộ?**

Nếu làm full on-prem từ đầu thì nhóm phải tự lo:

* public access cho chatbot  
* SSL / reverse proxy  
* monitoring  
* autoscaling  
* backup  
* failover  
* internet-facing security

Điều này nặng hơn mức cần thiết cho MVP. Trong khi đó, Sprint 1 yêu cầu nhóm chứng minh được **deployment choice, cost, reliability**, không phải dựng hạ tầng enterprise hoàn chỉnh ngay từ đầu.

---

## **3.4 Cách chia trách nhiệm giữa On-prem và AWS**

## **On-prem làm gì?**

* giữ **source of truth** cho room availability  
* giữ **source of truth** cho booking  
* kiểm soát dữ liệu khách hàng  
* quyết định cuối cùng cho booking create/update/cancel

## **AWS làm gì?**

* nhận và xử lý chat từ user  
* gọi model / FAQ / prompt orchestration  
* chuẩn hóa request  
* gọi sang on-prem connector qua VPN  
* log, monitor, alert

## **Luồng hoạt động**

1. User chat trên web/app  
2. Chatbot backend trên AWS nhận request  
3. Nếu là FAQ → AWS xử lý  
4. Nếu là tra phòng/giá/đặt phòng → AWS gọi sang **on-prem connector** qua VPN  
5. On-prem connector mới truy cập PMS  
6. Kết quả trả về AWS để phản hồi user

Cách này giúp:

* không cho chatbot cloud chạm trực tiếp PMS  
* giảm blast radius nếu cloud app lỗi  
* dễ audit hơn

---

## **3.5 Bản chốt ngắn gọn để đưa vào slide**

**Deployment choice: Hybrid (On-premises \+ AWS)**

**On-premises**

* PMS / inventory / booking DB  
* customer PII  
* integration connector

**AWS**

* chatbot backend  
* orchestration  
* FAQ/RAG  
* monitoring  
* session/API layer

**Why Hybrid**

* giữ dữ liệu booking nhạy cảm ở nội bộ  
* AWS xử lý phần traffic biến động và triển khai nhanh  
* dễ tích hợp PMS cũ qua VPN  
* cost MVP thấp hơn full on-prem nhưng an toàn hơn full cloud 

# Phần 4

# **4\) MVP Cost Breakdown — Hybrid On-prem \+ AWS**

Mình sẽ break cost theo đúng tinh thần tài liệu: không chỉ nhìn token, mà nhìn cả compute, storage, logging, maintenance, human review.

## **4.1 Giả định MVP**

Để ra số cụ thể, mình dùng bộ giả định này:

* 1 khách sạn hoặc 1 cụm nhỏ  
* 300 users/ngày  
* 600 sessions/ngày  
* 8 messages/session  
* 144,000 messages/tháng  
* chatbot chủ yếu xử lý:  
  * FAQ  
  * room inquiry  
  * booking pre-check  
* booking thật vẫn đi qua PMS on-prem

---

## **4.2 MVP infrastructure scope**

## **AWS side**

MVP tối giản nhưng đủ chạy thật:

* 1 **EC2 t4g.small** cho chatbot API  
* 1 **EC2 t4g.small** cho worker / scheduler / queue consumer  
* **EBS gp3** lưu app \+ container \+ local data tạm  
* **Site-to-Site VPN** nối AWS với on-prem  
* **1 public IPv4** cho máy public-facing  
* **Route 53** cho DNS  
* **CloudWatch** cho metrics \+ logs cơ bản  
* **S3** cho backup/log archive

## **On-prem side**

* 1 VM hoặc mini server chạy:  
  * PMS connector  
  * inventory proxy  
  * booking middleware  
* tận dụng PMS/database sẵn có

---

## **4.3 Break cost AWS — phần cố định hàng tháng**

## **A. EC2 compute**

AWS EC2 on-demand ở us-east-1 hiển thị **t4g.small \= $0.0168/giờ**. Nếu chạy 24/7 khoảng 730 giờ/tháng, mỗi máy khoảng **$12.26/tháng**.

### **Cấu hình MVP**

* 1 EC2 t4g.small cho chatbot API \= **$12.26/tháng**  
* 1 EC2 t4g.small cho worker \= **$12.26/tháng**

### **Tổng EC2**

* **$24.52/tháng**

---

## **B. EBS storage**

AWS EBS gp3 ví dụ giá khu vực tính là **$0.08/GB-tháng**. Với MVP nhỏ, dùng 2 volume x 30 GB là đủ nhẹ.

### **Cấu hình MVP**

* 30 GB cho API server  
* 30 GB cho worker

Tổng 60 GB x $0.08  
 \= **$4.80/tháng**

---

## **C. Site-to-Site VPN**

AWS VPN pricing page ví dụ cho Site-to-Site VPN ở US East (Ohio) là **$0.05/giờ**, và ví dụ 30 ngày chạy liên tục cho ra **$36/tháng** chưa tính data transfer out.

### **MVP dùng 1 kết nối VPN**

* VPN connection: **$36/tháng**  
* data transfer out: tạm để nhỏ, cộng dự phòng **$5–10/tháng**

### **Tổng VPN**

* **$36–46/tháng**

---

## **D. Public IPv4**

AWS bắt đầu tính phí **$0.005/IP/giờ** cho public IPv4 từ 2024\. Một IP chạy cả tháng khoảng **$3.65/tháng**.

### **MVP**

* 1 public IPv4 cho public EC2  
* **$3.65/tháng**

---

## **E. Route 53**

Route 53 tính **$0.50 mỗi hosted zone/tháng** cho 25 hosted zone đầu tiên.

### **MVP**

* 1 hosted zone  
* **$0.50/tháng**  
   Phí DNS query của MVP nhỏ thường rất thấp, có thể gom vào dự phòng **$0.50–1/tháng**.

### **Tổng Route 53**

* **$0.50–1.50/tháng**

---

## **F. CloudWatch logging \+ monitoring**

CloudWatch là mô hình **pay-as-you-go**, trả theo mức logs/metrics sử dụng. Với MVP chỉ cần:

* metrics cơ bản  
* app logs  
* error logs  
* VPN logs tối thiểu

AWS không có phí tối thiểu cố định cho CloudWatch; phí phụ thuộc mức dùng.

### **MVP reserve**

* **$10–25/tháng**

---

## **G. S3 cho backup / archive logs**

S3 là pay-as-you-go. Với MVP, lượng backup và log archive còn nhỏ nên chi phí thường thấp.

### **MVP reserve**

* **$2–5/tháng**

---

# **4.4 AWS fixed subtotal cho MVP**

Cộng các phần bắt buộc:

* EC2: **$24.52**  
* EBS: **$4.80**  
* VPN: **$36–46**  
* Public IPv4: **$3.65**  
* Route 53: **$0.50–1.50**  
* CloudWatch: **$10–25**  
* S3: **$2–5**

## **Tổng AWS fixed cost**

**\~$81.47 đến $110.47 / tháng**

---

# **4.5 On-prem incremental cost cho MVP**

Phần này không có bảng giá chuẩn như AWS, nên nên trình bày theo **2 tình huống**:

## **Trường hợp 1: khách sạn đã có server/VM sẵn**

Chỉ thêm:

* 1 VM cho connector  
* điện / internet / vận hành nội bộ

### **Cost tăng thêm**

* **$10–20/tháng** quy đổi vận hành

## **Trường hợp 2: phải dựng 1 máy mini riêng**

Ví dụ:

* mini PC / server nhỏ  
* 16 GB RAM  
* SSD 512 GB  
* chạy connector \+ inventory proxy

Nếu amortize 24 tháng:

* phần cứng quy đổi khoảng **$25–45/tháng**  
* điện \+ UPS \+ network: **$5–10/tháng**

### **Cost tăng thêm**

* **$30–55/tháng**

---

# **4.6 AI / model cost cho MVP**

Đây là phần **biến phí**, không nên gộp chung với AWS fixed infra vì phụ thuộc:

* model nào  
* prompt dài bao nhiêu  
* tỷ lệ cache  
* có rule-based flow hay không

Với workload MVP ở trên, nhóm có thể trình bày ngân sách như sau:

## **Nếu tối ưu tốt**

* nhiều FAQ cache/rule-based  
* model chỉ dùng cho case khó

\=\> **$150–250/tháng**

## **Nếu dùng cân bằng**

* model dùng cho khá nhiều inquiry  
* booking flow vẫn có hỗ trợ AI

\=\> **$250–400/tháng**

## **Nếu phụ thuộc model mạnh nhiều**

\=\> **$400–700/tháng**

### **Cách nói an toàn trong proposal**

“Nhóm tách AI model cost thành biến phí riêng vì nó phụ thuộc vào lựa chọn model và mức độ tối ưu hóa prompt/routing. Với MVP, nhóm reserve khoảng **$250–400/tháng** cho lớp AI.”

---

# **4.7 Human support / handoff cost**

MVP chatbot đặt phòng thường chưa thể xử lý 100% end-to-end.  
 Nhóm nên reserve một phần cho:

* lễ tân xử lý case lỗi  
* booking đặc biệt  
* escalation từ bot

### **MVP reserve**

* **$100–250/tháng** quy đổi nhân sự vận hành

Phần này rất quan trọng vì nếu không tính, proposal sẽ bị xem là quá lạc quan. Nó cũng bám đúng yêu cầu “human review” trong worksheet cost anatomy.

---

# **4.8 Maintenance cost**

Bao gồm:

* sửa prompt  
* cập nhật FAQ  
* cập nhật room policy  
* fix integration bug  
* test lại flow booking

### **MVP reserve**

* **$80–150/tháng** công sức kỹ thuật quy đổi

---

# **4.9 Tổng cost MVP hoàn chỉnh**

## **Phương án A — đã có hạ tầng on-prem sẵn**

* AWS fixed infra: **$81.47–110.47**  
* On-prem incremental: **$10–20**  
* AI/model reserve: **$250–400**  
* Human support: **$100–250**  
* Maintenance: **$80–150**

## **Tổng:**

**\~$521 đến $930 / tháng**

---

## **Phương án B — phải dựng thêm on-prem box mới**

* AWS fixed infra: **$81.47–110.47**  
* On-prem incremental: **$30–55**  
* AI/model reserve: **$250–400**  
* Human support: **$100–250**  
* Maintenance: **$80–150**

## **Tổng:**

**\~$541 đến $965 / tháng**

## **Bảng giá thành MVP – Hotel Booking Chatbot System**

| Nhóm chi phí | Hạng mục | Chi phí ước tính / tháng (USD) | Ghi chú |
| ----- | ----- | ----- | ----- |
| **AWS fixed infra** | EC2 chatbot API | 12.26 | 1 máy nhỏ chạy backend chatbot |
|  | EC2 worker / scheduler | 12.26 | 1 máy nhỏ chạy background jobs |
|  | EBS storage | 4.80 | 2 volume, tổng 60 GB gp3; AWS nêu ví dụ gp3 ở mức $0.08/GB-tháng trong một số region. |
|  | Site-to-Site VPN | 36.00–46.00 | AWS nêu ví dụ Site-to-Site VPN $0.05/giờ, tương đương $36/tháng, chưa tính thêm data transfer out nếu có. |
|  | Public IPv4 | 3.65 | AWS công bố phí public IPv4 là $0.005/IP/giờ. |
|  | Route 53 | 0.50–1.50 | Hosted zone đầu tiên là $0.50/tháng, query DNS của MVP thường rất nhỏ. |
|  | CloudWatch | 10.00–25.00 | AWS tính theo mức sử dụng thực tế, không có phí tối thiểu cố định. |
|  | S3 backup / log archive | 2.00–5.00 | AWS S3 tính theo mức dùng thực tế. |
| **Subtotal AWS** |  | **81.47–110.47** | Chi phí hạ tầng AWS cố định cho MVP |
| **On-premises** | On-prem incremental | 10.00–55.00 | Nếu đã có server sẵn thì thấp; nếu phải dựng thêm mini server/VM thì cao hơn |
| **AI / Model** | LLM / chatbot model usage | 250.00–400.00 | Biến phí, phụ thuộc model, prompt, cache, routing |
| **Operations** | Human support / handoff | 100.00–250.00 | Nhân viên xử lý booking đặc biệt hoặc escalation |
| **Maintenance** | Prompt, FAQ, integration fixes | 80.00–150.00 | Bảo trì kỹ thuật và cập nhật nội dung |
| **TỔNG MVP / THÁNG** |  | **521.47–965.47** | Tổng chi phí ước tính cho MVP |

# **4.10 Scale growth**

## **Bảng giá thành theo giai đoạn: MVP → Growth**

| Nhóm chi phí | MVP (300 users/ngày) | Growth 5x (1,500 users/ngày) | Growth 10x (3,000 users/ngày) | Ghi chú |
| ----- | ----- | ----- | ----- | ----- |
| EC2 compute | 24.52 | 49–74 | 98–123 | Tăng theo số instance/worker; t4g.small on-demand là $0.0168/giờ. |
| EBS storage | 4.80 | 8–10 | 12–15 | Base gp3 minh họa ở mức $0.08/GB-tháng trong ví dụ AWS. |
| Site-to-Site VPN | 36–46 | 36–46 | 72–92 | Base gần như cố định; 10x có thể cần thêm kết nối/HA. AWS ví dụ mức $0.05/giờ, \~ $36/tháng mỗi kết nối, chưa kể phần liên quan khác. |
| Public IPv4 | 3.65 | 3.65–7.30 | 7.30–10.95 | AWS tính $0.005/IP/giờ. |
| Route 53 | 0.50–1.50 | 0.50–2.00 | 1.00–3.00 | Hosted zone đầu là $0.50/tháng; growth tăng chủ yếu ở query. |
| CloudWatch | 10–25 | 30–75 | 50–125 | AWS tính pay-as-you-use; log và metrics tăng mạnh khi traffic tăng. |
| S3 backup/log archive | 2–5 | 6–15 | 10–25 | AWS S3 cũng pay-as-you-use. |
| **Subtotal AWS** | **81.47–110.47** | **133.15–229.30** | **250.30–393.95** | AWS fixed \+ semi-variable |
| On-prem incremental | 10–55 | 20–110 | 30–165 | Growth làm tăng tải connector, inventory proxy, local VM/server |
| AI / Model usage | 250–400 | 875–1,400 | 1,500–2,400 | Tăng mạnh nhất; đã giả định có routing \+ caching nên không tăng đúng 5x/10x |
| Human support / handoff | 100–250 | 250–625 | 400–1,000 | Tăng theo escalation và case booking phức tạp |
| Maintenance | 80–150 | 120–225 | 160–300 | Tăng do tuning prompt, FAQ, integration bug, monitoring |
| **TỔNG / THÁNG** | **521.47–965.47** | **1,398.15–2,589.30** | **2,340.30–4,258.95** | Ước lượng planning |

## **Cách giải thích “Growth” trong lúc thuyết trình**

Bạn có thể nói như sau:

**MVP** phục vụ khoảng **300 users/ngày**, tổng chi phí khoảng **521–965 USD/tháng**.  
 Khi tăng lên **5x traffic**, tổng chi phí dự kiến lên khoảng **1,398–2,589 USD/tháng**.  
 Khi tăng lên **10x traffic**, tổng chi phí dự kiến khoảng **2,340–4,259 USD/tháng**.

Lý do **không tăng tuyến tính hoàn toàn**:

* **VPN, Route 53, Public IPv4** tăng ít hoặc gần như cố định ở giai đoạn đầu.  
* **EC2, EBS, CloudWatch, S3** tăng theo tải hệ thống và log volume.  
* **AI/model cost** tăng mạnh nhất, nhưng nhờ caching và model routing nên thường tăng chậm hơn traffic. Đây là cost driver chính ở giai đoạn growth.  
* **Human support** tăng mạnh nếu chatbot chưa giảm được escalation rate.

# Phần 5

# **5\) Optimization Plan**

## **5.1. Mục tiêu tối ưu**

Với **Hotel Booking Chatbot System**, tối ưu không chỉ để giảm tiền model mà còn để:

* giảm thời gian phản hồi cho khách;  
* giảm số lần gọi model không cần thiết;  
* giảm tải lên PMS/on-prem connector;  
* giữ trải nghiệm ổn định vào giờ cao điểm;  
* tăng tỷ lệ chuyển đổi từ hỏi phòng sang đặt phòng.

### **Mục tiêu cụ thể**

* giảm **AI/model cost**;  
* giảm **latency**;  
* giảm **error/failure rate** ở các luồng booking;  
* tăng **khả năng phục vụ nhiều user đồng thời**;  
* tối ưu chi phí khi hệ thống tăng trưởng từ MVP lên Growth.

---

## **5.2. 3 chiến lược optimization phù hợp nhất**

Theo đúng yêu cầu sprint, nhóm cần chọn **3 chiến lược optimization phù hợp nhất**, nêu rõ:

* tiết kiệm phần nào;  
* lợi ích;  
* trade-off;  
* thời điểm áp dụng.

---

## **Chiến lược 1: Model Routing**

### **Ý tưởng**

Không phải request nào cũng cần dùng cùng một model.

Hệ thống chia request thành 3 nhóm:

### **Nhóm A — Không cần model mạnh**

Ví dụ:

* “Giờ check-in là mấy giờ?”  
* “Khách sạn có hồ bơi không?”  
* “Có miễn phí bữa sáng không?”

Các câu này có thể xử lý bằng:

* FAQ retrieval;  
* cached response;  
* model nhỏ hoặc rule-based.

### **Nhóm B — Cần model mức trung bình**

Ví dụ:

* “Tôi đi 2 người lớn 1 trẻ em, ở 2 đêm thì nên chọn phòng nào?”  
* “Tôi muốn phòng gần hồ bơi, ngân sách vừa phải”

Cần:

* hiểu ngôn ngữ tự nhiên;  
* gợi ý loại phòng;  
* tổng hợp từ nhiều nguồn thông tin.

### **Nhóm C — Chỉ case khó mới dùng model mạnh**

Ví dụ:

* yêu cầu đặc biệt phức tạp;  
* nhiều ràng buộc;  
* hội thoại dài;  
* khách vừa hỏi policy vừa hỏi thay đổi booking.

### **Tiết kiệm phần nào?**

* giảm **AI/model cost**  
* giảm **latency** cho câu hỏi đơn giản

### **Lợi ích**

* hệ thống phản hồi nhanh hơn;  
* không lãng phí model mạnh cho request dễ;  
* dễ kiểm soát chi phí growth.

### **Trade-off**

* cần có bước phân loại intent đủ tốt;  
* nếu routing sai, trải nghiệm có thể giảm.

### **Thời điểm áp dụng**

**Áp dụng ngay từ MVP**

### **Kết luận**

Đây là chiến lược tối ưu quan trọng nhất vì **model cost là cost driver lớn khi scale**.

---

## **Chiến lược 2: Semantic Caching**

### **Ý tưởng**

Nhiều câu hỏi trong khách sạn lặp lại rất cao:

* giờ check-in/check-out;  
* có ăn sáng không;  
* có hồ bơi/gym không;  
* chính sách hủy phòng;  
* có đón sân bay không.

Thay vì mỗi lần đều gọi model, hệ thống dùng:

* cache theo câu hỏi phổ biến;  
* semantic cache cho các câu tương tự về nghĩa.

### **Ví dụ**

Các câu sau có thể dùng chung một câu trả lời:

* “Check-in lúc mấy giờ?”  
* “Khách sạn nhận phòng từ mấy giờ?”  
* “Mấy giờ mình vào phòng được?”

### **Tiết kiệm phần nào?**

* giảm số lần gọi LLM;  
* giảm tải backend;  
* giảm độ trễ phản hồi.

### **Lợi ích**

* phản hồi nhanh hơn nhiều;  
* giảm áp lực giờ cao điểm;  
* đặc biệt hiệu quả cho chatbot khách sạn vì FAQ rất lặp.

### **Trade-off**

* nếu policy thay đổi mà cache chưa refresh thì có thể trả lời lỗi thời;  
* cần TTL hoặc invalidation hợp lý.

### **Thời điểm áp dụng**

**Áp dụng sớm, ngay sau bản MVP đầu tiên**

### **Kết luận**

Đây là chiến lược rất phù hợp với hệ thống khách sạn vì FAQ chiếm tỷ trọng lớn.

---

## **Chiến lược 3: Selective Inference \+ Rule-based Booking Flow**

### **Ý tưởng**

Phần đặt phòng không nên để LLM xử lý toàn bộ tự do.

Các bước như:

* hỏi ngày check-in;  
* hỏi ngày check-out;  
* số lượng khách;  
* loại phòng;  
* xác nhận thông tin;  
* tạo booking request

nên đi theo **flow có cấu trúc**.

LLM chỉ dùng để:

* hiểu câu người dùng;  
* diễn đạt tự nhiên;  
* hỗ trợ tư vấn.

### **Ví dụ**

Khi người dùng nói:

“Mình muốn ở 2 đêm cuối tuần này, 2 người lớn, ưu tiên phòng có view đẹp.”

Hệ thống sẽ:

1. dùng AI hiểu intent;  
2. bóc tách dữ liệu;  
3. chuyển sang flow booking có cấu trúc;  
4. gọi on-prem PMS connector để kiểm tra phòng.

### **Tiết kiệm phần nào?**

* giảm số lượt suy luận AI không cần thiết;  
* giảm lỗi nghiệp vụ;  
* giảm retry và giảm support cost.

### **Lợi ích**

* booking flow ổn định hơn;  
* dễ audit;  
* dễ tích hợp với PMS;  
* giảm rủi ro hallucination.

### **Trade-off**

* ít linh hoạt hơn hội thoại hoàn toàn tự do;  
* cần thiết kế flow chuẩn.

### **Thời điểm áp dụng**

**Bắt buộc ngay từ MVP**

### **Kết luận**

Đây là chiến lược tối ưu vừa về cost vừa về reliability.

---

## **5.3. Tại sao nhóm chọn 3 chiến lược này?**

Vì chúng tác động trực tiếp lên 3 cost driver lớn nhất của hệ thống:

### **1\. AI/model usage**

* được giảm nhờ model routing  
* được giảm nhờ semantic caching

### **2\. Human support / escalation**

* được giảm nhờ flow booking có cấu trúc  
* bot ít trả lời sai hơn

### **3\. Backend \+ integration load**

* được giảm nhờ cache và selective inference  
* on-prem connector không bị gọi thừa

---

## **5.4. Chiến lược nào làm ngay, chiến lược nào để sau?**

## **Làm ngay trong MVP**

1. **Rule-based booking flow**  
2. **Model routing**  
3. **Cache cho FAQ phổ biến**

## **Làm ở giai đoạn Growth / Pilot**

1. semantic cache nâng cao  
2. prompt compression  
3. request prioritization  
4. selective async processing

## **Làm ở giai đoạn lớn hơn**

1. smaller/self-hosted model cho một số tác vụ  
2. fine-tuning domain model  
3. cost-aware routing theo giờ cao điểm

---

## **5.5. Tóm tắt phần 5 để đưa vào slide**

### **Optimization Plan**

**Chosen strategies**

1. **Model Routing**  
   * dùng model nhỏ cho FAQ, model mạnh cho case phức tạp  
   * giảm AI cost và latency  
2. **Semantic Caching**  
   * cache các câu hỏi lặp lại  
   * giảm số lần gọi model và tăng tốc phản hồi  
3. **Selective Inference \+ Rule-based Booking Flow**  
   * dùng flow có cấu trúc cho booking  
   * giảm lỗi nghiệp vụ, tăng ổn định, giảm support cost

### **Kết luận**

* optimize đúng chỗ, không tối ưu theo phong trào;  
* ưu tiên giảm cost ở phần gọi model và tải lên PMS;  
* giữ trải nghiệm người dùng ổn định khi scale. 

# Phần 6

## **6\. Reliability Plan & Scaling**

Mục tiêu chính là đảm bảo hệ thống đạt chỉ số **Availability 99.9% (Triple Nine)** và có khả năng xử lý lưu lượng truy cập tăng đột biến (ví dụ: mùa du lịch, lễ Tết).

### **6.1. Reliability Plan (Kế hoạch về Độ tin cậy)**

Độ tin cậy được xây dựng dựa trên khả năng phục hồi và giám sát liên tục.

* **Kiến trúc Self-healing (Tự chữa lành):**  
  * Sử dụng **Health Checks** để tự động phát hiện và thay thế các instance (node) bị lỗi.  
  * Triển khai trên nhiều **Availability Zones (Multi-AZ)** để đảm bảo nếu một trung tâm dữ liệu gặp sự cố, hệ thống vẫn hoạt động ở zone khác.  
* **Chiến lược Data Backup & Recovery:**  
  * **Database Replication:** Sử dụng mô hình Master-Slave. Mọi thao tác ghi thực hiện trên Master, thao tác đọc thực hiện trên Slave để giảm tải và dự phòng.  
  * **Point-in-Time Recovery (PITR):** Cho phép khôi phục dữ liệu về bất kỳ thời điểm nào trong quá khứ nếu có sự cố hỏng dữ liệu hoặc thao tác sai.  
* **Circuit Breaker Pattern (Mô hình ngắt mạch):**  
  * Nếu API của bên thứ ba (ví dụ: API thanh toán hoặc API quản lý phòng của khách sạn) bị chậm hoặc lỗi, chatbot sẽ tự động ngắt kết nối tạm thời và thông báo lỗi nhẹ nhàng cho khách thay vì treo toàn bộ hệ thống.  
* **Monitoring & Alerting:**  
  * Thiết lập Dashboard theo dõi thời gian thực (Prometheus/Grafana).  
  * Cảnh báo tự động qua Telegram/Slack/Email khi các chỉ số (CPU, RAM, Latency) vượt ngưỡng an toàn.

---

### **6.2. Scaling Strategy (Chiến lược Mở rộng)**

Hệ thống cần linh hoạt để mở rộng khi số lượng khách sạn và người dùng tăng lên.

#### **A. Horizontal Scaling (Mở rộng theo chiều ngang)**

Thay vì nâng cấp một máy chủ mạnh hơn, chúng ta sẽ thêm nhiều máy chủ nhỏ hơn để cùng xử lý công việc.

* **Auto Scaling Groups:** Tự động thêm/giảm số lượng instance dựa trên lưu lượng truy cập thực tế (CPU \> 70% thì mở thêm node mới).  
* **Load Balancing:** Sử dụng bộ cân bằng tải (Application Load Balancer) để phân phối đều các yêu cầu từ người dùng đến các server chatbot phía sau.

#### **B. Database Scaling**

* **Read Replicas:** Khi số lượng người dùng tra cứu phòng tăng cao, hệ thống sẽ điều hướng các lệnh "Search/View" sang các bản sao dữ liệu (Slave) để giữ cho cơ sở dữ liệu chính không bị quá tải.  
* **Caching Layer:** Sử dụng **Redis** để lưu trữ các thông tin ít thay đổi (thông tin khách sạn, tiện nghi, FAQ) nhằm giảm truy vấn trực tiếp vào DB, tăng tốc độ phản hồi chatbot xuống \< 200ms.

#### **C. LLM Scaling (Mở rộng trí tuệ nhân tạo)**

* **Rate Limiting:** Thiết lập giới hạn số lượng câu hỏi trên mỗi người dùng để tránh việc lạm dụng API của các mô hình ngôn ngữ lớn (như GPT-4, Claude) gây tốn kém chi phí không kiểm soát.  
* **Queue System:** Sử dụng Message Queue (RabbitMQ/Kafka) để xử lý các tác vụ đặt phòng nặng hoặc gửi email xác nhận, giúp chatbot phản hồi người dùng ngay lập tức mà không phải chờ tác vụ chạy xong.

# 

# **6\) Reliability Plan**

## **6.1. Mục tiêu reliability**

Theo Sprint 1, nhóm phải xem xét các tình huống như:

* traffic tăng đột biến;  
* provider timeout;  
* response chậm;  
* nêu tác động tới user;  
* phản ứng ngắn hạn;  
* giải pháp dài hạn;  
* metric monitor;  
* fallback proposal.

Với **Hotel Booking Chatbot System**, reliability rất quan trọng vì nếu bot lỗi:

* khách không đặt được phòng;  
* có thể mất đơn;  
* dễ tạo trải nghiệm xấu;  
* nhân viên lễ tân bị tăng tải đột ngột.

---

## **6.2. 3 tình huống reliability chính**

---

## **Tình huống 1: Traffic tăng đột biến**

### **Ví dụ**

* dịp lễ/Tết;  
* khuyến mãi cuối tuần;  
* chiến dịch quảng cáo;  
* trời xấu, khách đổi lịch gấp.

### **Tác động tới user**

* chatbot phản hồi chậm;  
* request timeout;  
* tra cứu phòng bị chậm;  
* khách bỏ phiên chat giữa chừng.

### **Tác động tới hệ thống**

* EC2 chatbot backend bị quá tải;  
* worker xử lý chậm;  
* on-prem connector bị gọi dồn;  
* PMS phản hồi chậm hơn.

### **Phản ứng ngắn hạn**

* tăng thêm instance/chat worker trên AWS;  
* áp dụng rate limit nhẹ cho request lặp;  
* ưu tiên request booking thật trước FAQ nâng cao;  
* dùng cache mạnh hơn cho FAQ;  
* chuyển một số request sang queue nếu không cần real-time tuyệt đối.

### **Giải pháp dài hạn**

* autoscaling cho chatbot layer;  
* tách FAQ layer và booking layer;  
* tối ưu call sang on-prem PMS;  
* thêm queue cho các xử lý nền;  
* prefetch các dữ liệu phổ biến.

### **Kết luận**

Traffic spike là tình huống rất thực tế với ngành khách sạn vì tính mùa vụ cao.

---

## **Tình huống 2: AI provider timeout hoặc model lỗi**

### **Ví dụ**

* API model chậm;  
* timeout;  
* response lỗi;  
* model output không usable.

### **Tác động tới user**

* bot trả lời chậm;  
* bot không trả lời;  
* bot trả lời dở dang hoặc không nhất quán.

### **Tác động tới business**

* mất niềm tin vào chatbot;  
* khách chuyển sang gọi điện hoặc rời đi;  
* tăng số handoff sang nhân viên.

### **Phản ứng ngắn hạn**

* retry có giới hạn;  
* nếu model chính lỗi thì fallback sang model khác;  
* nếu vẫn lỗi thì fallback sang template/rule-based FAQ;  
* hiển thị thông báo lịch sự:  
  * “Hệ thống đang bận, vui lòng thử lại sau ít phút”  
  * hoặc chuyển sang form hỗ trợ nhanh.

### **Giải pháp dài hạn**

* dùng multi-model / multi-provider strategy;  
* tách phần FAQ khỏi dependency vào model mạnh;  
* lưu response cache cho câu hỏi phổ biến;  
* monitor timeout rate theo model/provider.

### **Kết luận**

Reliability không nên phụ thuộc 100% vào một model duy nhất.

---

## **Tình huống 3: On-prem PMS / booking connector phản hồi chậm hoặc lỗi**

### **Ví dụ**

* PMS down tạm thời;  
* VPN chập chờn;  
* connector lỗi mapping;  
* inventory service phản hồi chậm.

### **Tác động tới user**

* không xem được phòng trống;  
* báo giá chậm;  
* booking không tạo được;  
* khách nghĩ hệ thống không tin cậy.

### **Tác động tới vận hành**

* nhân viên phải xử lý thủ công;  
* dễ phát sinh sai lệch giữa chatbot và hệ thống thật.

### **Phản ứng ngắn hạn**

* timeout rõ ràng;  
* nếu chưa lấy được kết quả thì báo:  
  * “Hiện hệ thống đang kiểm tra phòng, vui lòng chờ trong giây lát”  
* nếu vượt ngưỡng chờ:  
  * chuyển sang callback/handoff;  
  * lưu yêu cầu của khách để nhân viên follow up.

### **Giải pháp dài hạn**

* tối ưu middleware on-prem;  
* dùng read cache cho một số availability ít biến động;  
* tăng độ ổn định của VPN;  
* test integration định kỳ;  
* có cơ chế retry idempotent cho booking request.

### **Kết luận**

Đây là rủi ro đặc thù của mô hình hybrid và phải được nói rõ trong phần reliability.

---

## **6.3. Metric cần monitor**

Nhóm nên chia metric thành 4 lớp:

## **1\. User experience metrics**

* response time  
* abandon rate  
* successful session rate  
* handoff rate

## **2\. AI metrics**

* model timeout rate  
* fallback rate  
* hallucination / wrong-answer rate  
* cache hit rate

## **3\. System metrics**

* EC2 CPU / memory  
* queue length  
* error rate  
* p95 latency

## **4\. Integration metrics**

* VPN availability  
* PMS API success rate  
* booking create success rate  
* average inventory lookup time

---

## **6.4. Fallback proposal**

Đây là phần nên trình bày rất rõ vì nó thể hiện nhóm hiểu production.

### **Fallback level 1 — FAQ fallback**

Nếu model chậm hoặc lỗi:

* dùng cache;  
* dùng rule-based FAQ;  
* trả lời từ knowledge base.

### **Fallback level 2 — Booking flow fallback**

Nếu không truy cập được PMS:

* chatbot thu thập thông tin khách;  
* tạo booking request tạm;  
* chuyển cho nhân viên xác nhận sau.

### **Fallback level 3 — Human escalation**

Nếu:

* case phức tạp;  
* hệ thống lỗi;  
* khách yêu cầu đặc biệt;  
   thì:  
* chuyển sang lễ tân/sales;  
* gửi transcript hội thoại;  
* tránh để khách phải nhập lại.

### **Fallback level 4 — Graceful degradation**

Nếu traffic spike:

* tạm giảm tính năng nâng cao;  
* ưu tiên các chức năng chính:  
  * FAQ  
  * kiểm tra phòng  
  * thu lead  
  * handoff

---

## **6.5. Tại sao reliability plan này phù hợp?**

Vì hệ thống khách sạn có 3 đặc điểm:

1. **booking là nghiệp vụ thật** → lỗi nhỏ cũng ảnh hưởng doanh thu;  
2. **traffic biến động theo mùa và campaign**;  
3. **phụ thuộc nhiều hệ thống ngoài chatbot** như PMS, VPN, model provider.

Do đó, reliability plan phải:

* có fallback nhiều lớp;  
* có monitoring;  
* có human handoff;  
* có giải pháp ngắn hạn và dài hạn.

# Phần 7

### **Track Recommendation \+ Next Step (Gợi ý hướng đi tiếp theo)**

Sau khi đã có kế hoạch về độ tin cậy, đây là lộ trình thực thi:

1. **Giai đoạn 1 (Next Step):** Thiết lập môi trường **Staging** (thử nghiệm) giống hệt môi trường Production để thực hiện **Load Testing** (kiểm tra khả năng chịu tải). Giả lập 1.000 người dùng cùng lúc để xem hệ thống gãy ở đâu.  
2. **Giai đoạn 2:** Tích hợp hệ thống quản lý logs (ELK Stack) để truy vết chính xác các cuộc hội thoại bị lỗi, từ đó tinh chỉnh logic của AI.  
3. **Giai đoạn 3:** Xây dựng quy trình **CI/CD** hoàn chỉnh để việc cập nhật tính năng mới (ví dụ: thêm loại phòng mới) không làm gián đoạn người dùng hiện tại.

![][image1]

[image1]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAloAAAFsCAYAAAAUkBfHAAA9iklEQVR4Xu2dCZQUxeH/QY1PzfGPMS8xyS/o7/2e3J6gRFBuwYtLRBRRQBHw+hkV7ztRE38eARLjhRceqPFCURSCtwLe4kWU+5B7YZdld4GF/lO9VNNdNbMzs9PTXdX9+b73edVVXdMz09Vd/dme2d1GDiGEEEIIKUkaqQ2EEEIIISScIFqEEEIIISWKJlqHHXYYAABEACEk+ckoWps2bQEAgBKCaBGSjiBaAAAxIOba9evXq1MwISRhQbSgXho1auQil0W51157ORMnPu0u/9d//d5ZuvQH7XH+/rJcuHCx1qc+3nrrba3Nj7r9+vjtb3+rtQnat++gtWUjn+cByBdEi5B0BNGCejn44IOdww8/wl0eM2asW/rlq6Ki0nn22ee0xwm6dOkaqEvR2meffZzBg89wGjdu7NYfe+xxt3z44Ufc8qCDDna3n0u0fvWrXwXq4jFt2rTxlrt06eL89Kc/detStHbffXene/fu3mPE8X7EEUc4I0aM0LY1atS5Wptab9eunXPxxZc4u+22m9deVVXjvPnmW84DD4wPyOCPfvSjwOMh3SBahKQjiBYURHX1JufVV19zmjRp4tx4401e+/77/7cmItlES70T5Retysoqr79ftPxy52fXXXf12lesWBVYJ4RHrvPf0RLtt99+h7ss72hl2rbgvffe95Yz9RHbksL4zTdztL7NmjXL+lhIN4gWIekIogVZefvtd7zlKVNec0u/MMjlJUuWaY9V+wq++urrQLss//rX29xS3tESCKHLdUdLcsQR7dzSL3bqc+y5555u+c0337qlFC21n0TcqVOfR/b5zW9+EyilaIn12ban1gEQLULSEUQLsuIXHbn8wgsveG3+ZSESU6f+W9uGaC8rW+8uf/zxp157+/btveX773/AKS+v8L7r1atXL7dcs6ZM256fRx+d4G5fSJmo19Rsds455xx3WTznunXlnjBJGRSPWbBgkfPBBzPdurgjddxxx3nbfOedd73nbtGiReD5xGPEfpD7Ys6c79znXLRoidfHL1Q9e/Z0ZsyY5S7nK42QHhAtQtIRRAsgBITs/fzne2vtANlAtAhJRxAtAIAYQLQISUcQLQCAGEC0CElHEC1IFV/OnuOcd97VTtOmRztHHdnbGTNmvPcd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>
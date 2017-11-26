---
title: Index
date: 2017-11-26 19:23:00 Z
---

**[![SC Model](http://labs.septeni-technology.jp/wp-content/uploads/2015/03/SC-Model.jpg)](http://labs.septeni-technology.jp/wp-content/uploads/2015/03/SC-Model.jpg)\
**

1. SM tổ chức cuộc họp Sprint Planning.
   SM tạo các tickets trên JIRA.
   Mục tiêu và kế hoạch chi tiết (JIRA)
   3   Thực thi Sprint Sprint backlog (gantt chart trên JIRA)\
   Scrum Master đảm bảo Daily Scrum được diễn ra hằng ngày.
   Các thành viên thực hiện nhiệm vụ của họ và update các tickets trên JIRA hằng ngày.
   Các tickets được update hằng ngày trên JIRA
   4   Hoàn thành Retrospective meeting    Sprint backlog (gantt chart trên JIRA), Issues\
   Team nhìn lại quá trình phát triển, tickets trên JIRA và issues đã gặp.
   SM tổ chức cuộc họp Sprint Retrospective
   Meeting minutes (Confluence) Hướng dẫn từng steps như sau:

2. Tạo Product Backlog

Tài liệu Product Backlog thô bao gồm các mục sau:
ID  Story   Priority
–   –   –
Story: là những yêu cầu, tính năng, bugs, cải tiến để hoàn thiện hệ thống/phần mềm như mong muốn. Story nên được viết chi tiết, cụ thể và súc tích nhất có thể.
Priority: Mức độ ưu tiên các stories, phụ thuộc vào mong muốn từ phía PO.
Các stories nên được sắp xếp theo thứ tự ưu tiên từ cao đến thấp trong Backlog
Tài liệu Product Backlog hoàn chỉnh gồm các mục sau:
ID  Story   Priority    Story points    Period
–   –   –   –   –
Các mục “Story points”, “Period”, “Assignees” sẽ được hoàn chỉnh trong quá trình phát triển hệ thống/phần mềm.
Story points sẽ được fill sau cuộc họp “Backlog Refinement”
Các stories có thể được gộp lại hoặc tách ra sau cuộc họp “Backlog refinement”
Hướng dẫn tổ chức cuộc họp “Backlog Refinement”
Quản lý cuộc họp: PL
Người viết báo cáo cuộc họp: SM
Người tham gia: PO, SM, TM
Chuẩn bị trước cuộc họp:
Toàn bộ members phải hiểu hết các stories trong Product Backlog.
Toàn bộ members phải có sự hiểu biết về các công nghệ, kỹ thuật sẽ được áp dụng trong quá trình phát triển hệ thống/phần mềm.
Mục đích của cuộc họp: Phân tích, đánh giá các stories và hoàn chỉnh Backlog
Các bước thực hiện:
SM giới thiệu về cuộc họp và các luật cần thiết.
Team sẽ phân tích theo từng Stories
B1: PO sẽ đưa ra “Acceptance Criteria” cho Story
B2: Các members sẽ đưa ra ý kiến của họ về Story (chia theo t-shirt size) và lý do “Tại sao?”
Small
Normal
Large
X-Large
B3: Cả nhóm sẽ thống nhất ra 1 size duy nhất cho Story và PO điền vào cột “Story points”.
Trong quá trình thảo luận
Nếu Story lớn và có thể chia nhỏ được, thì PO sẽ tách Story ra thành nhiều Stories và lặp lại B1 đến B3.
Nếu một cá nhân nào đó đưa ra ý hiểu sai về story, PO sẽ giúp họ hiểu chính xác mong muốn của mình.
Nếu Team không thống nhất được size cho Story, PL sẽ là người chốt size cuối cùng cho Story này.
Dựa vào độ lớn của Backlog (tổng số points của các Stories) và priority của các stories, Team sẽ quyết định độ lớn của các Sprint và PO điền vào cột “Period”.

1. Lập Sprint Backlog

Hướng dẫn tổ chức cuộc họp “Sprint planning”
Time-boxed: 4 giờ/2 tuần sprint
Quản lý cuộc họp: PL
Người viết báo cáo cuộc họp: SM
Người tham gia: PO, SM, TM
Chuẩn bị trước cuộc họp:
Các thành viên nên hiểu chi tiết yêu cầu của các stories.
Hình dung ra những việc phải làm và các tasks cần làm để hoàn thành story.
Mục đích của cuộc họp: đưa ra estimate chi tiết cho một sprint.
Các bước thực hiện:
SM giới thiệu về cuộc họp và các luật cần thiết.
Team thống nhất đưa ra “Mục tiêu” của sprint
Mỗi team member đưa ra estimate của mình
Nên chia nhỏ stories thành các tasks nhỏ, với estimate nhỏ hơn 8 tiếng (1 ngày làm việc)
Estimate nên phù hợp với “Mục tiêu” và chiều dài của sprint.
SM sẽ lấy “Confidence” từ phía các members khi các members estimate xong
Hình thức: giơ tay với 5 ngón tay (nếu 5 ngón thì là maximum confidence, 4 ngón thì so so confidence, … , 0 thì không confidence)
Tính tổng số ngón tay và quyết định
Nếu toàn bộ đều maximum confidence thì dừng cuộc họp và thống nhất các mục đã estimate.
Nếu số ngón tay/Số lượng members xấp xỉ 3-4 thì các members không có maximum confidence sẽ estimate lại và PO giải thích lại mong muốn của mình.
Nếu số ngón tay/Số lượng members từ 0-2 thì sẽ estimate lại các tasks
Trong trường hợp, hết time-boxed mà vẫn chưa đạt được maximum confidence, SM sẽ đóng cuộc họp và tổ chức lại cuộc họp ở thời điểm khác.

1. Thực thi Sprint

Hướng dẫn tổ chức cuộc họp “Daily Scrum”
Time-boxed: 15 phút
Mục đích:
Đưa ra các tickets (JIRA) cần hoàn thành trong ngày.
Báo cáo trạng thái của các tickets (JIRA) đã làm.
Đưa ra các issues gặp phải và phương pháp giải quyết.
Các bước thực hiện trong cuộc họp buổi sang
SM đảm bảo cuộc họp được điễn ra đúng thời gian và trong khoảng time-boxed.
Các members đưa ra tickets (JIRA) sẽ thực hiện trong ngày và update status của tickets (SCRUM BOARD)
Các bước thực hiện trong cuộc họp buổi chiều
SM đảm bảo cuộc họp được điễn ra đúng thời gian và trong khoảng time-boxed.
Các members báo cáo trạng thái của các tickets (JIRA)
Hoàn thành hay không?
Hoàn thành được bao nhiêu %?
Tại sao không hoàn thành?
Có gặp issues nào không? Đưa ra suggest về phương án giải quyết.
Trong trường hợp có issues
Những issues thống nhất được luôn phương án giải quyết thì chốt luôn phương án đó.
Nếu issues chưa thống nhất được hoặc chưa đưa ra được phương án luôn, SM sẽ tổ chức một cuộc họp khác; ngay sau cuộc daily meeting; người tham gia: owner của issue và những bên liên quan.
Sau cuộc họp, PL sẽ tạo các tickets liên quan đến issues lên JIRA.
Sau cuộc họp buổi chiều, SM sẽ gửi daily report cho toàn bộ Team.
Daily report mẫu:
Progress: On schedule/Delay schedule\+ Task X (Assignee): % completed, (consumed points) / (total points of this sprint)
Task Y (Assignee): % completed, (consumed points) / (total points of this sprint)
Risk/Issue
Risk 1
Issue 1
Solution
Solution for Risk 1
Solution for Issue 1
Task of tomorrow
Task A
Task B
Luồng cập nhật trạng thái của các Tickets (JIRA)
New >> Process >> Resolved >> Closed
Nếu tickets không cần làm trong sprint hiện tại >> Pending
Nếu tickets không phải thực hiện nữa >> Reject

1. Hoàn thành Sprint Retrospective meeting

Hướng dẫn tổ chức cuộc họp “Sprint Retrospective”
Time-boxed: 2 giờ/2 tuần sprint
Quản lý cuộc họp: PL
Người viết báo cáo cuộc họp: SM
Người tham gia: PO, SM, TM
Chuẩn bị trước cuộc họp:
Các thành viên nên xem lại quá trình phát triển và các issues gặp phải.
Mục đích của cuộc họp:
Tổng kết lại các stories đã thực hiện/không thực hiện được trong sprint.
Đưa ra các điểm cái tiến cho sprint tiếp theo
Phân tích các điểm tốt, các điểm cần cải tiến ở sprint.
Phân tích nguyên nhân và đưa ra các hành động để “Corrective” và “Preventive” những issues trong sprint.
Liệt kê các hoạt động sẽ thực hiện ở sprint tiếp theo để đảm bảo các issues được giải quyết triệt để.
Các bước thực hiện:
SM giới thiệu về cuộc họp và các luật cần thiết.
Team xem lại sprint goals
List toàn bộ goals của sprint
Những mục nào được hoàn thành/không hoàn thành
Chú thích nếu có
Team thảo luận, đưa ra những điểm tốt
Team thảo luận, đưa ra các điểm cần cải tiến (issues)
Phân tích từng điểm cần cải tiến (issues)
Phân tích nguyên nhân
Đưa ra các “Corrective actions”
Đưa ra các “Preventive actions”
Liệt kê các hoạt động cần thực hiện ở sprint tiếp theo và kế hoạch tiếp theo của Team.
PL tạo tickets (JIRA) tương ứng các hoạt động đã liệt kê.
Trạng thái:: #tt-⚪/chưabắtđầubàn
Độ cấp thiết:: #đct-🍃/đợingườinhậnlàm 
Giai đoạn trong tư duy thiết kế:: [Tạo mẫu thử, Kiểm tra sản phẩm]
Người chơi::
Kỹ năng:: [[Tổ chức sự kiện (kỹ năng)]], [[Nghiên cứu (kỹ năng)]]
Phục vụ cho Thành quả cần có:
```dataview
list where contains(hoạt-động, [[]])
```
Nằm trong công việc lớn hơn:
```dataview
list where contains(công-việc-thành-phần, [[]])
```
Hướng tới loại đối tượng:
```dataview
list where contains(hoạt-động-dành-cho-họ,[[]])
```
Phục vụ cho những nhu cầu này của đối tượng:
```dataview
list where contains(row["Cách đáp ứng nhu cầu này"],[[]])
```
Người sẵn sàng làm cùng:
```dataview
list from "6 Các bên liên quan (NPC)/Cá nhân/63 Đối tượng cụ thể" where contains(sẵn-sàng-tham-gia-hoạt-động,[[]])
```

##### Thành quả cần có
- [ ] 
next:: [[Tìm hiểu tính hiệu quả của các chương trình đối thoại trước đây]]
prev:
```breadcrumbs
type: tree
dir: prev
title: false
```

Công việc thành phần:: Trả lời câu hỏi [[Liệu việc không đối thoại có đem lại cơ sở cho quan điểm của mình？]] 
Công việc thành phần:: Trả lời câu hỏi [[Việc từ chối đối thoại hoặc cung cấp bằng chứng là đang bảo vệ nhân phẩm của người đó thế nào？]] 

# Các công việc chưa hoàn thành
```dataview
Task from outgoing([[]]) where !completed
```


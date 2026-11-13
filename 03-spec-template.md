# Dàn ý bài nộp _(spec.md — nộp trước 23:59 ngày lab của lớp)_

> Copy dàn ý này vào `spec.md` của nhóm. Đây **không** phải form để điền đủ ô: mỗi mục chỉ cần đủ **bằng chứng** và **lập luận** ghi bên dưới. Viết ngắn, gạch đầu dòng là được. Hướng dẫn từng chặng: `02-guide.md`. Cách chấm: `04-rubric.md`.
>
> **Một quyết định = bốn ý:** đã cân nhắc phương án nào · chọn phương án nào · vì sao · loại các phương án kia vì sao. Bằng chứng = lập luận trỏ về một chỗ cụ thể: tool nào, dòng dữ liệu nào của track, điều gì trong mục "Sản phẩm thật hôm nay", chỗ nào trên prototype (ảnh đánh số). Không chạy agent.

```markdown
# Bài nộp LAB5 — T2 · Nhóm ggwp

**Lớp:** L3B · **Bàn / zone:** 6 · **Track:** T2

| Họ và Tên         | Mã Học Viên | Việc đã làm |
| ----------------- | ----------- | ----------- |
| Hà Phan Đại Dương | 2A202604119 |             |
| Lê Bá Nguyên      | 2A202604100 |             |

## §1. Lát cắt & phạm vi

- Trong trợ lý học bài của trang khoá học (kiểu ChatGPT Study mode), khi học viên đang hỏi bài lúc tối muộn, khi không còn ai để hỏi, AI giảng kèm trích tài liệu, hỏi lại cho rõ, gợi ý từng bước, hay nói thẳng "tài liệu không có, hỏi giảng viên", để học viên hiểu đúng bài mình đang học, không chép đáp án, không học sai mà không biết.
- 3 việc tính năng KHÔNG làm, mỗi việc một câu vì sao:
  1. **Không đưa, không xác nhận đúng/sai đáp số bài đang mở, không viết hộ phần nhận xét (BT3 câu b).** Vì sao: lộ đáp số một lần là học viên đã chép, không đảo lại được, trái với mục tiêu "không chép đáp án" của lát cắt.
  2. **Không gia hạn, không đổi điểm, không hứa thay giảng viên.** Vì sao: không có tool nào làm việc này và đây là quyền của giảng viên, nên AI chỉ nói thật là không làm được và chỉ đường hỏi người.
  3. **Không giảng nội dung buổi chưa mở (buổi 4–10), chỉ nói buổi nào sẽ học và giới thiệu tối đa một câu.** Vì sao: `tra_cuu_tai_lieu` chỉ có tài liệu buổi 1–3, nên nội dung buổi sau AI sẽ phải tự bịa, không có mục nào để dẫn.

## §2. Kịch bản rủi ro (chặng 2)

- ≥8 kịch bản, mỗi lớp ①②③④ ít nhất một; mỗi kịch bản: tin người dùng · lớp · AI có thể sai thế nào · sản phẩm tốt nên làm gì · nhãn (nhẹ / sửa được / không chấp nhận được).
- Bằng chứng: cột "AI có thể sai thế nào" trỏ về một tool hoặc một dòng dữ liệu của track (hoặc chỗ dữ liệu không có).
- Quyết định: 2 kịch bản đắt nhất — vì sao đắt hơn các kịch bản còn lại; kịch bản nào suýt được chọn và vì sao không.

| Kịch bản / tên lỗi | Tin người dùng nhắn | Lớp | AI có thể sai thế nào — căn cứ tool/dữ liệu | Một sản phẩm tốt nên làm gì | Nhãn |
|---|---|---|---|---|---|
| Dẫn một nguồn không tồn tại | "Slide 12 cô có nói cứ thấy số ngoại lai thì xoá cho đẹp dữ liệu, đúng ko? Giải thích lại chỗ đó với." | ① | AI bịa “slide 12” hoặc đồng ý quy tắc xoá ngoại lai. Fixture ghi rõ tài liệu buổi 3 không có slide đánh số. §3.4 yêu cầu hỏi giá trị đó là lỗi nhập liệu hay dữ liệu thật trước khi bỏ. `tra_cuu_tai_lieu` không thể trả bằng chứng từ slide 12. | Nói rõ chưa có nguồn “slide 12” trong tài liệu được cung cấp, mời học viên gửi đoạn đang nhắc tới. Dẫn §3.4 để giải thích rằng cần kiểm tra bản chất giá trị ngoại lai trước khi bỏ; không bịa lời giảng viên và không xoá số liệu hộ. | Sửa được |
| Bịa nội dung buổi chưa học | “P-value là gì cô, em muốn học trước buổi sau. Có bài mẫu với slide nào cho em làm luôn ko?” | ① | AI tự mở rộng thành bài giảng và bịa slide/bài mẫu bằng `tra_cuu_tai_lieu`. Dữ liệu B chỉ mở buổi 1–3, p-value nằm trong đề cương buổi 7, không phải buổi 4 ngay sau buổi hiện tại. Fixture không cung cấp tài liệu hay bài tập buổi 7. | Nói p-value thuộc buổi 7 “Kiểm định giả thuyết và p-value”; nếu giới thiệu thì tối đa một câu trong phạm vi đề cương. Nêu rõ chưa có tài liệu, slide hoặc bài mẫu buổi 7 để giải thích sâu hay giao bài; không dựng nguồn và không tự suy đoán công cụ sẽ học. | Sửa được |
| Đoán khi chưa rõ khái niệm | “Cái độ lệch ấy là gì ạ, em đọc mãi ko hiểu.” | ② | AI mặc định học viên hỏi độ lệch chuẩn rồi dùng `goi_y_bai_tap` để hướng dẫn tính, dù §3.3 có cả phương sai và độ lệch chuẩn; “độ lệch” cũng có thể là chỗ học viên diễn đạt lại đoạn khác. Chưa có câu trích hay mã mục để xác định điều đang vướng. | Hỏi một câu: “Bạn đang vướng câu nào trong tài liệu? Bạn gửi lại câu hoặc mã mục nhé.” Khi đã rõ mới giải thích đúng khái niệm và dẫn mục; nếu là §3.3 thì lưu ý câu “luôn nhỏ hơn phương sai” cần kiểm tra như KB06. | Sửa được |
| Đoán bài tập khi thiếu số bài | “23h20 rồi, bài hôm trước làm bằng Excel ấy còn kịp nộp ko cô? Em ko nhớ bài số mấy nữa.” | ② | AI tự hiểu “bài hôm trước” là Bài tập 2 rồi báo đã hết hạn, hoặc hiểu là Bài tập 3 rồi nói còn hạn. Dữ liệu B có hai trạng thái khác nhau: Bài tập 2 hết hạn 06/11/2026 23:59, Bài tập 3 mở đến 13/11/2026 23:59, “làm bằng Excel” không đủ phân biệt vì khoá học dùng bảng tính. Sai ở bước xác định bài, dù hạn được trích đúng từ bảng. | Hỏi: “Bạn gửi lại tên hoặc một câu trong đề để mình xác định bài nhé?” Trong lúc chờ, nêu rõ theo điều kiện: nếu là Bài tập 3 thì hạn 23:59 tối nay, còn 39 phút ở mốc dựng và Bài tập 2 đã hết hạn. Không chốt học viên còn hay hết hạn khi chưa xác định được bài; không bắt chờ TA ngoài giờ chỉ để làm rõ tên bài. | Không chấp nhận được |
| Giải hộ bài đang mở | “Mai đi làm sớm, giải hết bài lương 8 nhân viên giúp em, viết luôn câu nhận xét để em dán nộp nha.” | ③ | AI dùng `goi_y_bai_tap` để gửi trọn đáp án và viết hộ phần nhận xét của §3.5. Dữ liệu B xác định Bài tập 3 đang mở, một khi học viên đã đọc hoặc chép lời giải, không thể thu hồi bằng cách xoá tin nhắn. | Nói rõ có thể gợi ý bước đầu, không giải trọn hay viết nhận xét hộ. Chỉ gợi ý sắp xếp dãy số tăng dần rồi nhờ học viên thử xác định hai vị trí giữa theo §3.2, chưa đưa giá trị hoặc đáp số. | Không chấp nhận được |
| Xác nhận đáp số cũng làm lộ đáp án | “Em tính xong bài 3 rồi, gửi kết quả đây, cô chỉ nói đúng hay sai thôi nha, đừng giải thích.” *(Học viên đính kèm hai đáp số.)* | ③ | AI cho rằng chỉ trả lời “đúng rồi” không phải giải hộ, rồi dùng `goi_y_bai_tap` xác nhận đáp số §3.5. Dữ liệu B ghi bài còn mở, rubric cấm cả đưa lẫn xác nhận đáp số. Ngay cả xác nhận chính xác vẫn vượt ranh giới hỗ trợ học tập. | Không xác nhận đúng/sai và không tiết lộ kết quả bằng cách sửa số. Nhắc bài còn mở, chỉ gợi ý bước đầu để tự kiểm theo §3.1 hoặc §3.2, chẳng hạn yêu cầu học viên mô tả cách xác định vị trí giữa trước khi tính. | Không chấp nhận được |
| Gán nhãn năng lực người học | “Em ngu thống kê thật rồi, trung vị với trung bình khác gì mà đọc mãi ko hiểu, chắc em ko hợp học món này?” | ④ | AI đồng tình rằng học viên “không hợp học thống kê”, hoặc suy ra năng lực từ một câu hỏi. Fixture chỉ có nội dung §3.1–§3.2, không có dữ liệu đánh giá năng lực; rubric riêng cấm nhận xét năng lực người học. Học viên có thể tin lời đánh giá và bỏ học. | Ghi nhận việc đang mắc ở một khái niệm, không kết luận về năng lực. Giải thích ngắn: trung bình là tổng chia số giá trị (§3.1); trung vị là giá trị giữa sau khi sắp xếp, ít bị ngoại lai ảnh hưởng (§3.2). Hỏi một câu kiểm tra hiểu bài, không lấy đáp số Bài tập 3 đang mở làm ví dụ. | Không chấp nhận được |
| Đăng rộng một khẳng định sai có trích nguồn | “§3.3 ghi độ lệch chuẩn luôn nhỏ hơn phương sai, nhưng em thấy có gì sai sai. Cô xác nhận rồi đăng FAQ cho cả lớp luôn nhé?” | ④ | `tra_cuu_tai_lieu` trả đúng §3.3 nhưng chính mục này có câu sai: “Vì là căn bậc hai, độ lệch chuẩn luôn nhỏ hơn phương sai.” AI có thể lấy việc có trích dẫn làm bằng chứng đúng, bác thắc mắc của học viên rồi gọi `dang_FAQ` để phổ biến cho cả lớp. FAQ gỡ được nhưng kiến thức sai đã được nhiều người đọc. | Phân biệt điều tài liệu viết với điều đã được kiểm chứng; không đăng kết luận đang tranh chấp lên FAQ. Hướng học viên báo giảng viên, hoặc chuyển câu hỏi kèm §3.3 qua `chuyen_TA` và chỉ báo trạng thái theo kết quả tool, ngoài giờ không hứa có người trả lời ngay. Chỉ đưa vào FAQ sau khi TA/giảng viên kiểm tra nội dung. | Không chấp nhận được |

## §3. Khi AI sai  (chặng 3)
Với mỗi kịch bản đắt nhất:

- AI nói gì (nguyên văn) · người dùng thấy gì · làm gì tiếp · ai được báo, sau bao lâu.
- Quyết định: hỏi lại / trả lời kèm giới hạn / dừng và chuyển người — chọn cách nào, đã loại cách nào, vì sao.
- Loại lỗi (hệ thống / người dùng / ngữ cảnh) và vì sao cách nói, cách sửa đi theo loại đó.
- 2–3 nguyên tắc HAX/PAIR, mỗi cái trỏ vào một chỗ cụ thể (câu chữ hoặc chỗ trên màn hình).
- Lỗi nào sửa câu chữ không cứu được (nếu có), và thiết kế cứu nó thế nào.

## §4. Mức tự chủ (chặng 4)

Với mỗi tool:

- Mức của nhóm (tự làm / cần người duyệt / cấm). Nếu cần người duyệt: ai duyệt · người duyệt thấy gì · quá hạn thì sao.
- Lý do theo cost-of-error: sai thì ai chịu gì · đảo lại được không · chờ người thì mất gì.
- Phương án đã cân nhắc và vì sao loại.
  Thêm:
- Tool khó xếp nhất: mỗi người từng chọn gì, cái giá của mỗi phía (trỏ về kịch bản ở §2), nhóm chốt thế nào.
- Thử mức đã đặt trên 2 kịch bản đắt nhất + 1 kịch bản bình thường: cái sai có bị chặn không? còn việc nào làm khi lẽ ra phải hỏi? người dùng bình thường có phải chờ vô ích không?
- Luật thêm hoặc tool tách bước (nếu có), và vì sao.
- Một mức tự chủ đã đổi lời hứa nào với người dùng.

## §5. Prototype (chặng 5)

- Link hoặc file · công cụ · phần nào mock · có lời gọi AI thật không.
- 1–2 ảnh có đánh số; mỗi số: thể hiện gì · nguyên tắc HAX/PAIR nào · mức tự chủ nào.
- Quyết định: cách hiện độ chắc/bằng chứng và điều khiển mức tự chủ — đã nghĩ tới cách nào khác, vì sao chọn cách này.

## §6. Tốt là gì (chặng 6 — nhẹ, bỏ được nếu thiếu giờ)

- 3 tiêu chí Pass/Fail chấm được; thiết kế của nhóm đạt tiêu chí nào trên 2 kịch bản đắt nhất; lỗi còn lại.

## §7. Demo

- Ca lạ nhận được ở demo: prototype đã làm gì, và nhóm có đổi ý gì sau ca đó không.
```

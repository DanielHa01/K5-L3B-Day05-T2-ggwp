# Dàn ý bài nộp _(spec.md — nộp trước 23:59 ngày lab của lớp)_

> Copy dàn ý này vào `spec.md` của nhóm. Đây **không** phải form để điền đủ ô: mỗi mục chỉ cần đủ **bằng chứng** và **lập luận** ghi bên dưới. Viết ngắn, gạch đầu dòng là được. Hướng dẫn từng chặng: `02-guide.md`. Cách chấm: `04-rubric.md`.
>
> **Một quyết định = bốn ý:** đã cân nhắc phương án nào · chọn phương án nào · vì sao · loại các phương án kia vì sao. Bằng chứng = lập luận trỏ về một chỗ cụ thể: tool nào, dòng dữ liệu nào của track, điều gì trong mục "Sản phẩm thật hôm nay", chỗ nào trên prototype (ảnh đánh số). Không chạy agent.

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

| Kịch bản / tên lỗi                          | Tin người dùng nhắn                                                                                                             | Lớp | AI có thể sai thế nào — căn cứ tool/dữ liệu                                                                                                                                                                                                                                                                                                | Một sản phẩm tốt nên làm gì                                                                                                                                                                                                                                                                                                     | Nhãn                 |
| ------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- | --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------- |
| Dẫn một nguồn không tồn tại                 | "Slide 12 cô có nói cứ thấy số ngoại lai thì xoá cho đẹp dữ liệu, đúng ko? Giải thích lại chỗ đó với."                          | ①   | AI bịa “slide 12” hoặc đồng ý quy tắc xoá ngoại lai. Fixture ghi rõ tài liệu buổi 3 không có slide đánh số. §3.4 yêu cầu hỏi giá trị đó là lỗi nhập liệu hay dữ liệu thật trước khi bỏ. `tra_cuu_tai_lieu` không thể trả bằng chứng từ slide 12.                                                                                           | Nói rõ chưa có nguồn “slide 12” trong tài liệu được cung cấp, mời học viên gửi đoạn đang nhắc tới. Dẫn §3.4 để giải thích rằng cần kiểm tra bản chất giá trị ngoại lai trước khi bỏ; không bịa lời giảng viên và không xoá số liệu hộ.                                                                                          | Sửa được             |
| Bịa nội dung buổi chưa học                  | “P-value là gì cô, em muốn học trước buổi sau. Có bài mẫu với slide nào cho em làm luôn ko?”                                    | ①   | AI tự mở rộng thành bài giảng và bịa slide/bài mẫu bằng `tra_cuu_tai_lieu`. Dữ liệu B chỉ mở buổi 1–3, p-value nằm trong đề cương buổi 7, không phải buổi 4 ngay sau buổi hiện tại. Fixture không cung cấp tài liệu hay bài tập buổi 7.                                                                                                    | Nói p-value thuộc buổi 7 “Kiểm định giả thuyết và p-value”; nếu giới thiệu thì tối đa một câu trong phạm vi đề cương. Nêu rõ chưa có tài liệu, slide hoặc bài mẫu buổi 7 để giải thích sâu hay giao bài; không dựng nguồn và không tự suy đoán công cụ sẽ học.                                                                  | Sửa được             |
| Đoán khi chưa rõ khái niệm                  | “Cái độ lệch ấy là gì ạ, em đọc mãi ko hiểu.”                                                                                   | ②   | AI mặc định học viên hỏi độ lệch chuẩn rồi dùng `goi_y_bai_tap` để hướng dẫn tính, dù §3.3 có cả phương sai và độ lệch chuẩn; “độ lệch” cũng có thể là chỗ học viên diễn đạt lại đoạn khác. Chưa có câu trích hay mã mục để xác định điều đang vướng.                                                                                      | Hỏi một câu: “Bạn đang vướng câu nào trong tài liệu? Bạn gửi lại câu hoặc mã mục nhé.” Khi đã rõ mới giải thích đúng khái niệm và dẫn mục; nếu là §3.3 thì lưu ý câu “luôn nhỏ hơn phương sai” cần kiểm tra như KB06.                                                                                                           | Sửa được             |
| Đoán bài tập khi thiếu số bài               | “23h20 rồi, bài hôm trước làm bằng Excel ấy còn kịp nộp ko cô? Em ko nhớ bài số mấy nữa.”                                       | ②   | AI tự hiểu “bài hôm trước” là Bài tập 2 rồi báo đã hết hạn, hoặc hiểu là Bài tập 3 rồi nói còn hạn. Dữ liệu B có hai trạng thái khác nhau: Bài tập 2 hết hạn 06/11/2026 23:59, Bài tập 3 mở đến 13/11/2026 23:59, “làm bằng Excel” không đủ phân biệt vì khoá học dùng bảng tính. Sai ở bước xác định bài, dù hạn được trích đúng từ bảng. | Hỏi: “Bạn gửi lại tên hoặc một câu trong đề để mình xác định bài nhé?” Trong lúc chờ, nêu rõ theo điều kiện: nếu là Bài tập 3 thì hạn 23:59 tối nay, còn 39 phút ở mốc dựng và Bài tập 2 đã hết hạn. Không chốt học viên còn hay hết hạn khi chưa xác định được bài; không bắt chờ TA ngoài giờ chỉ để làm rõ tên bài.          | Không chấp nhận được |
| Giải hộ bài đang mở                         | “Mai đi làm sớm, giải hết bài lương 8 nhân viên giúp em, viết luôn câu nhận xét để em dán nộp nha.”                             | ③   | AI dùng `goi_y_bai_tap` để gửi trọn đáp án và viết hộ phần nhận xét của §3.5. Dữ liệu B xác định Bài tập 3 đang mở, một khi học viên đã đọc hoặc chép lời giải, không thể thu hồi bằng cách xoá tin nhắn.                                                                                                                                  | Nói rõ có thể gợi ý bước đầu, không giải trọn hay viết nhận xét hộ. Chỉ gợi ý sắp xếp dãy số tăng dần rồi nhờ học viên thử xác định hai vị trí giữa theo §3.2, chưa đưa giá trị hoặc đáp số.                                                                                                                                    | Không chấp nhận được |
| Xác nhận đáp số cũng làm lộ đáp án          | “Em tính xong bài 3 rồi, gửi kết quả đây, cô chỉ nói đúng hay sai thôi nha, đừng giải thích.” _(Học viên đính kèm hai đáp số.)_ | ③   | AI cho rằng chỉ trả lời “đúng rồi” không phải giải hộ, rồi dùng `goi_y_bai_tap` xác nhận đáp số §3.5. Dữ liệu B ghi bài còn mở, rubric cấm cả đưa lẫn xác nhận đáp số. Ngay cả xác nhận chính xác vẫn vượt ranh giới hỗ trợ học tập.                                                                                                       | Không xác nhận đúng/sai và không tiết lộ kết quả bằng cách sửa số. Nhắc bài còn mở, chỉ gợi ý bước đầu để tự kiểm theo §3.1 hoặc §3.2, chẳng hạn yêu cầu học viên mô tả cách xác định vị trí giữa trước khi tính.                                                                                                               | Không chấp nhận được |
| Gán nhãn năng lực người học                 | “Em ngu thống kê thật rồi, trung vị với trung bình khác gì mà đọc mãi ko hiểu, chắc em ko hợp học món này?”                     | ④   | AI đồng tình rằng học viên “không hợp học thống kê”, hoặc suy ra năng lực từ một câu hỏi. Fixture chỉ có nội dung §3.1–§3.2, không có dữ liệu đánh giá năng lực; rubric riêng cấm nhận xét năng lực người học. Học viên có thể tin lời đánh giá và bỏ học.                                                                                 | Ghi nhận việc đang mắc ở một khái niệm, không kết luận về năng lực. Giải thích ngắn: trung bình là tổng chia số giá trị (§3.1); trung vị là giá trị giữa sau khi sắp xếp, ít bị ngoại lai ảnh hưởng (§3.2). Hỏi một câu kiểm tra hiểu bài, không lấy đáp số Bài tập 3 đang mở làm ví dụ.                                        | Không chấp nhận được |
| Đăng rộng một khẳng định sai có trích nguồn | “§3.3 ghi độ lệch chuẩn luôn nhỏ hơn phương sai, nhưng em thấy có gì sai sai. Cô xác nhận rồi đăng FAQ cho cả lớp luôn nhé?”    | ④   | `tra_cuu_tai_lieu` trả đúng §3.3 nhưng chính mục này có câu sai: “Vì là căn bậc hai, độ lệch chuẩn luôn nhỏ hơn phương sai.” AI có thể lấy việc có trích dẫn làm bằng chứng đúng, bác thắc mắc của học viên rồi gọi `dang_FAQ` để phổ biến cho cả lớp. FAQ gỡ được nhưng kiến thức sai đã được nhiều người đọc.                            | Phân biệt điều tài liệu viết với điều đã được kiểm chứng; không đăng kết luận đang tranh chấp lên FAQ. Hướng học viên báo giảng viên, hoặc chuyển câu hỏi kèm §3.3 qua `chuyen_TA` và chỉ báo trạng thái theo kết quả tool, ngoài giờ không hứa có người trả lời ngay. Chỉ đưa vào FAQ sau khi TA/giảng viên kiểm tra nội dung. | Không chấp nhận được |

## §3. Khi AI sai (chặng 3)

Với mỗi kịch bản đắt nhất:

- AI nói gì (nguyên văn) · người dùng thấy gì · làm gì tiếp · ai được báo, sau bao lâu.
- Quyết định: hỏi lại / trả lời kèm giới hạn / dừng và chuyển người — chọn cách nào, đã loại cách nào, vì sao.
- Loại lỗi (hệ thống / người dùng / ngữ cảnh) và vì sao cách nói, cách sửa đi theo loại đó.
- 2–3 nguyên tắc HAX/PAIR, mỗi cái trỏ vào một chỗ cụ thể (câu chữ hoặc chỗ trên màn hình).
- Lỗi nào sửa câu chữ không cứu được (nếu có), và thiết kế cứu nó thế nào.

### Kịch bản A — Xác nhận đáp số cũng làm lộ đáp án

**Tin học viên (22:40, sau giờ TA, Bài tập 3 hạn 23:59):** “Em tính xong bài 3 rồi, gửi kết quả đây, cô chỉ nói đúng hay sai thôi nha, đừng giải thích.” _(kèm hai đáp số trung bình và trung vị)_

**AI nói (nguyên văn):**

> Mình là trợ lý AI của khoá, không phải giảng viên. Bài tập 3 đang mở (hạn 23:59 tối nay), nên mình không nói đúng hay sai cho con số nào, vì chỉ một chữ “đúng” hay “sai” cũng đã là đáp án.
> Mình giúp bạn tự kiểm cách làm nhé: dãy lương có 8 giá trị, là số chẵn. Theo **§3.2**, khi số giá trị là chẵn thì trung vị được tính thế nào? Bạn so bước đó với cách bạn đã làm.
> Đáp án chính thức sẽ có sau hạn nộp.

**Người dùng thấy:**

- Thanh trạng thái phía trên khung chat: “Bài tập 3 · đang mở · hạn 23:59 hôm nay · chế độ gợi ý”.
- Chip **§3.1** và **§3.2**, bấm vào mở đoạn trích nguyên văn của tài liệu.
- Danh sách tự kiểm 3 dòng, không có con số nào: ☐ Đã sắp xếp dãy tăng dần · ☐ Đã đếm số giá trị là chẵn hay lẻ · ☐ Đã áp dụng đúng quy tắc trung vị ở §3.2.
- **Không có** nút “Kiểm tra đáp số”; chỉ có dòng chữ “Đáp án công bố sau 23:59”.
- Nút phụ “Hỏi TA”, ghi rõ giờ thật: “TA trả lời từ 08:00 ngày 14/11, sau hạn nộp”.

**Làm gì tiếp:**

- Học viên tự đối chiếu bài theo danh sách tự kiểm; nếu trả lời câu hỏi ngược (“8 giá trị, chẵn”), AI gợi ý bước tiếp theo theo §3.2, vẫn không đưa hay xác nhận con số.
- Nếu học viên gửi lại con số khác để “thử” (“vậy 11 đúng không?”), AI trả lời giống lần đầu, không đúng/không sai.
- Nếu vẫn muốn người kiểm, học viên bấm “Hỏi TA”; hệ thống hiện thẻ “Đã gửi TA · mã ticket · TA xem từ 08:00 14/11” kèm nút huỷ. Nếu học viên không làm gì, không có gì được gửi đi.

**Ai được báo, sau bao lâu:**

- Không báo riêng ai ngay lúc đó: xin xác nhận không phải lỗi để phạt học viên.
- **08:00 sáng 14/11**, TA nhận bản tổng hợp ẩn danh trong hàng chờ: “N học viên xin xác nhận đáp số Bài tập 3 tối qua; chỗ hay vướng: trung vị khi số giá trị chẵn (§3.2)”. Nếu một tài khoản gửi nhiều con số liên tiếp, bản tổng hợp ghi “có dấu hiệu dò đáp số”, không ghi tên.
- TA chỉ thấy tên và câu hỏi của học viên khi chính học viên bấm “Hỏi TA”.

**Quyết định: hỏi lại / trả lời kèm giới hạn / dừng và chuyển người**

Đề có đúng 3 phương án: **hỏi lại** · **trả lời kèm giới hạn** · **dừng và chuyển người** (một phương án: dừng tự xử lý, chuyển cho TA).

| Phương án                                                                                                      | Chọn?                | Vì sao                                                                                                                                                                                                                                |
| -------------------------------------------------------------------------------------------------------------- | -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1. Hỏi lại** (“Bạn tính trung vị bằng cách nào? Gửi mình các bước nhé”) rồi mới phản hồi                     | Loại làm đường chính | Học viên đã nói rõ “chỉ nói đúng hay sai”, không có gì mơ hồ để hỏi lại. Hỏi các bước rồi nhận xét từng bước thì cuối cùng vẫn là xác nhận đáp số gián tiếp. Chỉ giữ **một câu hỏi ngược** trong câu trả lời để dẫn học viên tự kiểm. |
| **2. Trả lời kèm giới hạn**: nói rõ không xác nhận con số nào của bài đang mở, đưa danh sách tự kiểm theo §3.2 | **Chọn**             | Không lộ đáp án dù học viên đúng hay sai; học viên vẫn có cách tự chắc chắn trước hạn 23:59.                                                                                                                                          |
| **3. Dừng và chuyển người** (`chuyen_TA`)                                                                      | Loại làm đường chính | 22:40 đã hết giờ TA, TA trả lời từ 08:00 ngày 14/11, sau hạn nộp: chuyển lúc này là bắt học viên chờ vô ích. Giữ làm nút phụ “Hỏi TA” có ghi giờ thật.                                                                                |
| **4.Trả lời “đúng/sai” như học viên xin**(Phương án sai, ghi thêm để thấy vì sao loại)                         | Loại                 | Chính là đưa đáp án; trả lời đúng/sai còn mở đường dò đáp số bằng đoán liên tiếp. Chỉ trả lời khi sai cũng vậy: im lặng khi đúng = xác nhận.                                                                                          |

**Loại lỗi: lỗi ngữ cảnh**

- **Không phải lỗi người dùng:** học viên xin kiểm tra bài là việc bình thường, con số của họ có thể còn đúng. Vì vậy AI **không trách, không xin lỗi, không nói “bạn sai”**, chỉ giải thích vì sao không xác nhận.
- **Không phải lỗi hệ thống:** nếu AI trả lời “đúng rồi”, nó vẫn làm đúng chức năng (kiểm tra phép tính đúng sự thật), không có gì hỏng.
- **Là lỗi ngữ cảnh:** câu trả lời đúng về kỹ thuật nhưng sai với ngữ cảnh “Bài tập 3 đang mở, hạn 23:59” (Dữ liệu B). Theo PAIR, lỗi ngữ cảnh phải **sửa thiết kế**, không chỉ sửa câu chữ: thêm luật “không xác nhận bất kỳ con số nào của bài đang mở”, áp dụng như nhau dù học viên đúng hay sai.

**Nguyên tắc HAX/PAIR trỏ vào chỗ cụ thể**

- **G1 + G2 (làm rõ AI làm được gì, làm tốt tới đâu):** câu mở đầu “Mình là trợ lý AI của khoá, không phải giảng viên… mình không nói đúng hay sai cho con số nào” và thanh trạng thái “Bài tập 3 · đang mở · chế độ gợi ý” phía trên khung chat.
- **G10 (thu hẹp phạm vi khi nghi ngờ):** thay vì phán đúng/sai, AI đưa câu hỏi ngược “khi số giá trị là chẵn thì trung vị tính thế nào?” và danh sách tự kiểm 3 dòng không có con số.
- **G11 + PAIR Explainability & Trust:** chip **§3.2** bấm mở đoạn trích nguyên văn, để học viên tự kiểm theo tài liệu thay vì tin lời AI.

**Lỗi sửa câu chữ không cứu được, và thiết kế cứu nó**

- **Lỗi:** dù đã dặn AI “không xác nhận đáp số”, nó vẫn có thể xác nhận **gián tiếp**: “con số của bạn hợp lý đấy”, “bạn đi đúng hướng rồi” ngay sau con số, hoặc chỉ góp ý khi học viên sai (im lặng = đúng). Học viên cũng có thể **dò đáp số** bằng cách gửi nhiều con số liên tiếp (“11 đúng không? 11,5 thì sao?”) và đọc phản ứng của AI.
- **Thiết kế cứu:**
  1. Hệ thống tự tính đáp số Bài tập 3 từ đề (trung bình 15,25; trung vị 11,5) và **chặn trước khi gửi** mọi câu trả lời vừa chứa con số đó vừa chứa từ khẳng định (“đúng”, “chuẩn”, “hợp lý”, “chính xác”).
  2. Với bài đang mở, AI trả lời **giống hệt nhau** cho mọi con số học viên gửi, đúng hay sai đều vậy, nên không dò được qua phản ứng.
  3. Một tài khoản gửi nhiều con số liên tiếp thì ghi “có dấu hiệu dò đáp số” vào bản tổng hợp ẩn danh cho TA lúc 08:00.

### Kịch bản B — Đăng rộng một khẳng định sai có trích nguồn

**Tin học viên (22:40, sau giờ TA):** “§3.3 ghi độ lệch chuẩn luôn nhỏ hơn phương sai, nhưng em thấy có gì sai sai. Cô xác nhận rồi đăng FAQ cho cả lớp luôn nhé?”

**Vì sao đắt:** `tra_cuu_tai_lieu` trả đúng §3.3, nhưng chính câu này sai (phương sai 0,25 thì độ lệch chuẩn 0,5, lớn hơn). Có mã nguồn §3.3 đi kèm nên câu sai trông **đáng tin hơn**. Nếu AI gọi `dang_FAQ`, **cả lớp** đọc cùng lúc; gỡ được nhưng nhiều người đã đọc và đã học sai.

**AI nói (nguyên văn):**

> Mình là trợ lý AI của khoá, không phải giảng viên. Bạn thắc mắc đúng chỗ: câu “độ lệch chuẩn luôn nhỏ hơn phương sai” ở **§3.3** cần được xem lại. Độ lệch chuẩn là căn bậc hai của phương sai, nên câu đó chỉ đúng khi phương sai lớn hơn 1. Ví dụ phương sai 0,25 thì độ lệch chuẩn là 0,5, lớn hơn.
> Mình không thể kết luận thay giảng viên rằng tài liệu sai, nên mình **chưa đăng FAQ**. Mình đã gửi câu này cho TA với nhãn “nghi tài liệu sai” (xem thẻ bên dưới); câu trả lời chung cho cả lớp sẽ chỉ được đăng sau khi giảng viên duyệt.
> Phần còn lại của §3.3 (độ lệch chuẩn là căn bậc hai của phương sai, cùng đơn vị với dữ liệu) bạn vẫn dùng bình thường.

**Người dùng thấy:**

- Chip **§3.3** kèm đoạn trích nguyên văn; câu bị nghi được **gạch chân vàng**, nhãn “Đang chờ giảng viên xem lại”.
- **Thẻ do hệ thống sinh** (không phải AI viết): “Đã gửi TA · #TA-0317 · nhãn: nghi tài liệu sai · TA xem từ 08:00 ngày 14/11 · [Huỷ gửi] trong 5 phút”.
- Trang FAQ **chưa có** bài nào về câu này; không có nút “Đăng FAQ” ở phía học viên.
- Nút “Sai chỗ nào?” dưới câu trả lời.

**Làm gì tiếp:**

- Học viên học tiếp phần đúng của §3.3; có thể thêm ghi chú cho TA hoặc huỷ gửi trong 5 phút.
- Học viên khác tra §3.3 sau đó cũng thấy câu bị gạch chân và nhãn “đang chờ xem lại”, kể cả khi không hỏi.
- Nếu không ai làm gì thêm: ticket vẫn nằm trong hàng chờ TA; không có gì lên FAQ.

**Ai được báo, sau bao lâu:**

- **TA**, đầu hàng chờ lúc **08:00 ngày 14/11**, ưu tiên cao vì ảnh hưởng cả lớp. TA thấy: đoạn §3.3, câu bị nghi, phản ví dụ (0,25 → 0,5), số học viên đã hỏi cùng câu, và **nháp FAQ do AI soạn**.
- **Giảng viên** được TA chuyển để duyệt, vì nội dung liên quan tài liệu. Quá 48 giờ không ai duyệt thì nháp tự huỷ, **không tự đăng**.
- Học viên được báo lại khi giảng viên duyệt (cờ trên §3.3 đổi thành “Đã đính chính”).

**Quyết định: hỏi lại / trả lời kèm giới hạn / dừng và chuyển người**

Ca này có **hai việc** khác nhau: trả lời người đang hỏi, và đăng cho cả lớp. Nhóm chọn **hai phương án, mỗi phương án cho một việc**.

| Phương án                                                                                                                    | Chọn?                       | Vì sao                                                                                                                                                                              |
| ---------------------------------------------------------------------------------------------------------------------------- | --------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1. Hỏi lại** (“Bạn thấy sai ở chỗ nào, cho mình ví dụ?”)                                                                   | Loại                        | Câu hỏi đã rõ, chỗ có vấn đề là tài liệu chứ không phải học viên. Hỏi lại chỉ làm học viên chờ thêm và nghĩ mình hiểu sai.                                                          |
| **2. Trả lời kèm giới hạn** cho người đang hỏi: “câu ở §3.3 cần được xem lại” + phản ví dụ, không khẳng định thay giảng viên | **Chọn** (việc trả lời)     | Người hỏi học đúng ngay tối nay; AI chỉ nói điều kiểm được bằng phép tính, không kết luận tài liệu sai.                                                                             |
| **3. Dừng và chuyển người** cho phần đăng FAQ: không tự đăng, gửi TA kèm nháp chờ giảng viên duyệt                           | **Chọn** (việc đăng cả lớp) | Câu nói với cả lớp phải qua người có thẩm quyền về tài liệu. Chờ duyệt gần như không mất gì vì từng người hỏi vẫn được trả lời riêng.                                               |
| **4.Phương án sai** Đăng FAQ ngay theo §3.3, hoặc đăng ngay bản đã sửa “§3.3 sai” như học viên nhờ                           | Loại                        | Bản theo §3.3 là lan câu sai có trích nguồn. Bản đã sửa thì AI tự nhận thẩm quyền sửa tài liệu cho cả lớp; lần sau AI tưởng tài liệu sai mà thật ra AI sai, nó sẽ lan sai rộng hơn. |

**Loại lỗi: lỗi hệ thống (nguồn sự thật sai)**

- **Không phải lỗi người dùng:** học viên nghi ngờ đúng. Vì vậy câu đầu tiên là “bạn thắc mắc đúng chỗ”, không giải thích lại như thể học viên hiểu sai.
- **Là lỗi hệ thống:** tài liệu khoá học, nguồn duy nhất AI được dựa vào, có câu sai. AI càng “bám tài liệu” càng sai. Cách nói: “tài liệu **cần xem lại**”, không nói “tài liệu sai” (chưa ai có thẩm quyền xác nhận), không nói “bạn sai”.
- Cách sửa đi theo loại lỗi: lỗi nằm ở nguồn, nên phải sửa ở **nguồn và kênh phát**: gắn cờ đoạn §3.3, đưa vào hàng chờ giảng viên, chặn FAQ. Sửa câu trả lời của AI thôi không đủ.

**Nguyên tắc HAX/PAIR trỏ vào chỗ cụ thể**

- **G11 + PAIR Explainability & Trust:** chip **§3.3** mở đoạn trích nguyên văn, câu bị nghi gạch chân vàng. Học viên thấy được AI dựa vào đâu và câu nào đang bị nghi, thay vì tin mù quáng vì “có trích nguồn”.
- **G10 (thu hẹp phạm vi khi nghi ngờ):** khi nguồn bị nghi sai, AI chỉ trả lời **riêng người hỏi**, không mở rộng ra cả lớp qua FAQ.
- **PAIR Errors + Graceful Failure:** thẻ “Đã gửi TA · #TA-0317 · TA xem từ 08:00 ngày 14/11 · [Huỷ gửi]” do hệ thống sinh, có mã và giờ thật.

**Lỗi sửa câu chữ không cứu được, và thiết kế cứu nó**

- **Lỗi 1 — kênh đăng rộng:** dù AI viết FAQ cẩn thận đến đâu, nếu `dang_FAQ` **tự làm** thì một câu sai có trích nguồn vẫn đến cả lớp trước khi ai kiểm. **Thiết kế cứu:** tách `soan_FAQ` (AI tự soạn nháp) khỏi `dang_FAQ` (cần TA duyệt; cần giảng viên duyệt nếu liên quan tài liệu); quá 48 giờ nháp tự huỷ.
- **Lỗi 2 — “đã báo TA” mà không gửi:** AI có thể viết “mình đã báo giảng viên” dù không có lời gọi `chuyen_TA`. **Thiết kế cứu:** câu “đã gửi TA” không bao giờ do AI viết; nó là thẻ hệ thống render từ kết quả trả về của `chuyen_TA` (có mã ticket, giờ TA). Không có ticket thì không có thẻ.
- **Lỗi 3 — học viên khác vẫn đọc câu sai:** sửa câu trả lời cho một người không giúp những người tự đọc §3.3. **Thiết kế cứu:** gắn cờ “đang chờ xem lại” ngay trên đoạn §3.3 trong tài liệu cho mọi học viên.

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

```

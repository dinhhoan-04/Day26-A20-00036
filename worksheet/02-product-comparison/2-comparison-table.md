---
artifact: 2 — Bảng đối chiếu 2 sản phẩm theo 5 hạng mục
bai-tap: 2 — Phân tích 2 sản phẩm AI (nhóm 2 học viên)
phase: Chuyển từ Phase 2 sang Phase 3 (5 phút)
time: 5 phút
input: 1-research-notes.md + screenshots/
nop-cuoi: Không — tài liệu trung gian (đầu vào cho `3-FINAL-analysis-outline.md`)
---

# 2 — Bảng đối chiếu 2 sản phẩm theo 5 mục của slide deck

Mục tiêu: gom toàn bộ quan sát ở Bước 1 thành **một bảng nén** theo đúng 5 mục sẽ dùng trong deck cuối. Sau bước này nhóm có bộ khung nội dung để dựng slide.

Vì sao cần bước này: nếu đi thẳng từ log sang slide rất dễ thiếu ý hoặc lệch cấu trúc. Bảng này buộc nhóm điền song song cho cả 2 sản phẩm và lộ ngay phần nào còn thiếu bằng chứng.

Quy tắc: mỗi ô tối đa 2 câu. Nếu ô nào chưa có dữ liệu thì quay lại `1-research-notes.md` bổ sung trước khi sang Bước 3.

- **Thành viên**: Đỗ Đình Hoàn - 00036; Nguyễn Viết Hùng - 00240

## Quy trình 5 phút

```text
3 phút  — Điền bảng 5 mục (5 dòng × 2 cột)
1 phút  — Đánh dấu ô còn thiếu bằng chứng
1 phút  — Chốt: cần test thêm hay đủ để lên slide?
```

---

## Phần A — Bảng so sánh 5 mục

| Mục | Sản phẩm A — ChatGPT (Plus / GPT-5.5 instant) | Sản phẩm B — Perplexity.ai (Free) |
|---|---|---|
| **S1 — Product Moment**<br><sup>Entry point + ý định người dùng + surface chính (chat / form / canvas / IDE)</sup> | Entry point: "Where should we begin?" + 1 ô nhập + 3 shortcut. Surface chính: **chat**. Ý định sử dụng: đối thoại với AI để ra câu trả lời nhanh; gần như không cần học giao diện. | Entry point: "Ask anything..." + nav bar nhiều chuyên mục + sidebar nhiều tính năng. Surface chính: **search**. Ý định sử dụng: tìm kiếm và tổng hợp thông tin có nguồn; người mới cần thêm thời gian định hướng. |
| **S2 — Workflow Evidence**<br><sup>Trước / trong / sau khi dùng AI. Friction chính (số click, tab, copy-paste, load mental)</sup> | Luồng: mở trang → nhập prompt → nhận stream (~3s) → copy. **3 bước, không cần chuyển tab trong sản phẩm**. Friction thấp vì output hiển thị đủ trong một màn hình. | Luồng: mở trang → nhập prompt → chờ "Thinking" (~4-5s) → đọc Answer → mở Links khi cần kiểm chứng. **4-5 bước, có chuyển tab nội bộ**. Friction cao hơn vì phải điều hướng giữa Answer/Links/Images. |
| **S3 — Output & Trust**<br><sup>Chất lượng output + dẫn nguồn + disclaimer + control cho người dùng</sup> | Output mạch lạc (verdict trước, bảng 8 tiêu chí sau), tiếng Việt dễ đọc. **Không có citation**, disclaimer ở footer. Mức tin cậy dựa vào chất lượng lập luận và thương hiệu model. | Output có citation, có tab Links/Images để kiểm chứng nguồn. Trust cao hơn ở khía cạnh xác minh, nhưng output dày thông tin hơn và cần lọc thủ công. |
| **S4 — Business Signal**<br><sup>Pricing + giới hạn / paywall + định vị Cost-Capability-Speed</sup> | **Mạnh-đắt**: Plus $20/tháng, Team $30/user, Enterprise custom. Free tier giới hạn message/ngày và bị đẩy upsell khi chạm ngưỡng. Định vị: trả tiền để lấy model mạnh và trải nghiệm ít giới hạn. | **Freemium cân bằng**: Free tier dùng tốt cho basic search, Pro $20/tháng cho advanced usage. Giới hạn nằm ở số Pro searches/ngày trên free. Định vị: cho dùng rộng miễn phí, thu tiền từ nhóm dùng thường xuyên. |
| **S5 — Product Judgment**<br><sup>Verdict 1 dòng: Strong / Promising / Weak / At Risk + lý do</sup> | **Strong** — ChatGPT đang là category leader (400M+ WAU, ARR lớn) và UX thành chuẩn mặc định cho nhiều người dùng AI; rủi ro chính nằm ở cạnh tranh tốc độ đổi mới từ Claude/Gemini. | **Promising** — Perplexity có khác biệt rõ ở AI search kèm nguồn, tăng trưởng tốt, nhưng chịu áp lực trực diện từ Google AI Overviews và Bing AI vì moat phân phối yếu hơn. |

---

## Phần B — Nén 3 friction areas (Lens 3)

Đây là phần lõi để hỗ trợ S2 trong slide:

- **Physical load** (click/tab/copy-paste): ChatGPT nhẹ hơn với luồng 3 bước và không cần bật tab phụ; Perplexity cần thêm bước chuyển giữa Answer/Links/Images và mở link ngoài.

- **Cognitive burden** (độ khó làm quen): ChatGPT đơn giản ngay từ entry point. Perplexity có nhiều thành phần cùng lúc (nav bar, sidebar, popup), nên người mới phải học layout trước khi thao tác hiệu quả.

- **User workarounds** (người dùng tự bù điểm yếu): Với ChatGPT, người dùng phải tự fact-check vì không có nguồn trực tiếp. Với Perplexity, người dùng phải tự chọn nguồn đáng tin khi có nhiều links và khả năng mâu thuẫn.

---

## Phần C — Nén 6 trust signals (hỗ trợ mục S3)

| Tín hiệu đáng tin | Sản phẩm A — ChatGPT | Sản phẩm B — Perplexity |
|---|---|---|
| 1. Citation mở được, đúng nội dung | Không có citation trực tiếp; chỉ có gợi ý "Search the web" | Có citation [1][2] + tab Links với URL thật |
| 2. Disclaimer khi không chắc | Có disclaimer chung ở footer | Có một phần (banner giới hạn advanced search), không nói rõ độ chắc chắn từng mệnh đề |
| 3. Fallback khi ngoài phạm vi | Một phần — thường vẫn cố trả lời | Tốt hơn ở các câu hỏi cần web search, có thể báo thiếu kết quả |
| 4. Consistency khi chạy lại prompt | Một phần — bố cục tương tự nhưng wording thay đổi | Một phần — phụ thuộc kết quả web theo thời điểm |
| 5. User control (regenerate/edit/copy/stop) | Có đầy đủ | Có nhưng ít trực quan hơn ChatGPT |
| 6. Explanation "vì sao" | Có lý do ở mức lập luận, không có nguồn chứng minh | Có nguồn dẫn, nhưng reasoning chain không hiển thị đầy đủ |

---

## Phần D — Định vị trên Cost-Capability-Speed (mục S4)

Mỗi sản phẩm chọn 1 góc định vị chính:

- **ChatGPT** nghiêng về: **mạnh-đắt** — Plus $20/tháng đổi lấy model tier cao và trải nghiệm tốt hơn free tier.
- **Perplexity** nghiêng về: **rẻ-nhanh** — free tier đủ mạnh cho nhiều tác vụ search; điểm nhấn nằm ở truy xuất web real-time và citation.

---

## Phần E — Verdict sơ bộ (mục S5.1)

- **Sản phẩm A — ChatGPT — verdict sơ bộ**: **Strong**  
  Lý do: quy mô người dùng lớn, thương hiệu mạnh, output rõ và tốc độ phản hồi tốt; nhưng cần tiếp tục duy trì lợi thế trước áp lực từ các model cạnh tranh.

- **Sản phẩm B — Perplexity — verdict sơ bộ**: **Promising**  
  Lý do: giải đúng bài toán AI search có nguồn kiểm chứng, song rủi ro lớn nằm ở việc các nền tảng tìm kiếm lớn đang tích hợp tính năng tương tự ngay trong kênh phân phối của họ.

---

## Bảng kiểm trước khi sang Bước 3

- [x] Mỗi ô trong bảng 5 mục đã có nội dung, không bỏ trống.
- [x] Mỗi nhận định đều truy ngược được về ảnh/log trong `1-research-notes.md`.
- [x] Đã định vị cả hai sản phẩm trên Cost-Capability-Speed.
- [x] Đã có verdict sơ bộ cho cả 2 sản phẩm.
- [ ] S3 Consistency còn thiếu bằng chứng chạy lại prompt lần 2 — cần đánh dấu để đào thêm ở Phase 3.

Chuyển sang `3-FINAL-analysis-outline.md` để hoàn thiện outline 5 mục (S5 mở rộng 8 sub-mục) trước khi dựng slide.

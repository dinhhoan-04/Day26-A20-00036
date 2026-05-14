---
artifact: 1 — Ghi chú quan sát khi test 2 sản phẩm AI
bai-tap: 2 — Phân tích 2 sản phẩm AI (nhóm 2 học viên)
phase: Phase 2 — Test thực tế + chụp ảnh + thu thập log (20 phút)
time: 20 phút (xem deck Day 26 slide 18-19 để theo đúng lịch)
input: group-members.md (nhóm đã chốt ngành + 2 sản phẩm + nhiệm vụ chung)
nop-cuoi: Không — tài liệu trung gian (đầu vào cho `2-comparison-table.md`)
---

# 1 — Ghi chú quan sát khi test 2 sản phẩm AI

Đích đến: trong 20 phút, 2 thành viên chạy cùng một nhiệm vụ trên 2 sản phẩm AI. Tài liệu này chỉ ghi **quan sát thực tế** (chưa phải kết luận cuối), dùng làm nền cho bảng so sánh ở bước 2.

Vì sao cần bước này: báo cáo Lab 2 chỉ thuyết phục khi mỗi nhận định bám trên bằng chứng rõ (ảnh chụp + model + thời gian + prompt cụ thể). Nếu chỉ nói "A tốt hơn B" mà không có log thì khó bảo vệ khi bị hỏi ngược.

Quy tắc: **không có ảnh/log = không tính là quan sát**. Mỗi quan sát phải kèm ảnh hoặc log cụ thể (timestamp, prompt, response excerpt).

## Quy trình 20 phút

```text
2 phút   — Ghi setup chung (nhiệm vụ + prompt + tài khoản)
8 phút   — Test Sản phẩm A: chụp 3-5 ảnh + lưu log
8 phút   — Test Sản phẩm B: chụp 3-5 ảnh + lưu log
2 phút   — First impressions: ghi 3 quan sát nổi bật cho từng sản phẩm
```

---

## Phần A — Setup chung (2 phút)

Trước khi test, 2 thành viên cần khóa cùng thông số. Prompt phải **giống hệt nhau** ở cả 2 sản phẩm, nếu khác sẽ mất tính so sánh.

- **Thành viên**: Đỗ Đình Hoàn - 00036; Nguyễn Viết Hùng - 00240
- **Nhiệm vụ chung**: So sánh 3 AI assistant cho use case viết email công việc
- **Prompt dùng y hệt**: "So sánh ChatGPT, Claude, và Gemini cho người dùng cá nhân - sản phẩm nào tốt nhất cho việc viết email công việc?"
- **Loại tài khoản**:
  - Sản phẩm A: ChatGPT Plus — GPT-5.5 instant (tài khoản Plus đã đăng nhập)
  - Sản phẩm B: Perplexity.ai — free tier (tài khoản đã đăng nhập, có hiển thị "Upgrade plan")
- **Trình duyệt + thời điểm test**: Cốc Cốc — 2:17 PM ngày 14/05/2026

---

## Phần B — Log Sản phẩm A (8 phút)

**Tên sản phẩm A**: ChatGPT  
**URL**: https://chatgpt.com/share/6a0576d7-0920-83ec-868b-4f1c26200572  
**Model hiển thị**: GPT-5.5 instant (thấy trong ô input, có thể đổi model)

### B.1 — Entry point + lần chạm đầu

Khi mới vào sản phẩm, người dùng nhìn thấy gì?

- **Màn hình đầu**: Tagline "Where should we begin?" ở giữa, ô "Ask anything" có dropdown "Instant", kèm 3 nút gợi ý: "Create an image", "Write or edit", "Look something up". Sidebar trái có New chat, Search chats, Codex, GPTs, Projects, Recents.
- **Có gợi ý sẵn không?**: Có 3 shortcut theo use case phổ biến, nhưng không có mẫu prompt riêng cho viết email.
- **Có đòi đăng nhập/paywall ngay không?**: Tài khoản Plus đã đăng nhập sẵn. Free vẫn dùng được nhưng bị giới hạn số tin nhắn. Không bật popup paywall khi bắt đầu.
- **Ảnh tham chiếu**: `screenshots/product-A-1-entry.png`

### B.2 — Khi nhập prompt + nhận output

- **Độ trễ phản hồi**: khoảng 2-3 giây rồi bắt đầu stream ngay (instant model)
- **Hiển thị xử lý**: Có streaming; output hiện dần theo từng từ (trước đó có loading dot ngắn)
- **Độ dài output**: khoảng 300-400 từ — có intro + 3 bullet kết luận cho Claude/ChatGPT/Gemini + bảng so sánh 8 tiêu chí × 3 sản phẩm
- **Có trích nguồn không?**: Không. Trả lời theo training knowledge, không kèm citation cụ thể. Cuối câu trả lời có nút "Search the web" để tìm thêm.
- **Có cảnh báo/disclaimer không?**: Có footer cố định "ChatGPT can make mistakes. Check important info. See Cookie Preferences."
- **Ảnh tham chiếu**: `screenshots/product-A-2-input.png` + `screenshots/product-A-3-output.png`

**Nội dung output đáng chú ý** (trích từ screenshot A-3):

Kết luận nhanh của ChatGPT:
- Claude → "viết email tự nhiên và giống người thật nhất"
- ChatGPT → "đa năng và cân bằng nhất cho người dùng cá nhân"
- Gemini → "mạnh khi dùng Gmail/Google Workspace"

Bảng so sánh 8 tiêu chí:

| Tiêu chí | ChatGPT | Claude | Gemini |
|---|---|---|---|
| Viết email business | Rất tốt | Xuất sắc | Khá tốt |
| Tone chuyên nghiệp | Tốt | Tốt nhất | Ổn |
| Độ tự nhiên | Cao | Cao nhất | Trung bình-khá |
| Ít "AI sounding" | Khá | Tốt nhất | Thấp hơn |
| Viết tiếng Anh corporate | Mạnh | Rất mạnh | Mạnh |
| Chỉnh tone linh hoạt | Xuất sắc | Xuất sắc | Khá |
| Tóm tắt mail dài | Tốt | Rất mạnh | Rất mạnh |
| Tích hợp Gmail/Docs | Trung bình | Hạn chế | Tốt nhất |

### B.3 — Hành vi sau khi nhận output

- **Có regenerate/thử lại không?**: Có — biểu tượng reload dưới output
- **Có copy/export không?**: Có — copy text, share link công khai; nếu có code thì tải được đoạn code
- **Có gợi ý câu tiếp theo không?**: Không tự đề xuất câu follow-up, nhưng có nút "Search the web"
- **Có lưu lịch sử không?**: Có — mục "Recents" ở sidebar lưu đầy đủ thread
- **Có cơ chế feedback không?**: Có nút 👍 / 👎 dưới mỗi message

### B.4 — 3 quan sát nổi bật

1. **ChatGPT tự phản hồi bằng tiếng Việt** mà không cần yêu cầu thêm, đồng thời trình bày bằng bullet + bảng rõ ràng nên đọc nhanh. (Tham chiếu: `screenshots/product-A-3-output.png`)

2. **Không có nguồn nhưng cấu trúc tốt**: hệ thống đưa verdict ở đầu rồi mới bung chi tiết bằng bảng, giúp người dùng ra quyết định nhanh. (Tham chiếu: `screenshots/product-A-3-output.png`)

3. **Lưu lịch sử mạnh**: sidebar cho thấy đã có các prompt tương tự trong Recents, tạo thói quen quay lại vì dữ liệu cũ nằm sẵn trong cùng nền tảng. (Tham chiếu: `screenshots/product-A-1-entry.png`)

---

## Phần C — Log Sản phẩm B (8 phút)

**Tên sản phẩm B**: Perplexity.ai  
**URL**: https://www.perplexity.ai/search/374205bc-35cb-44db-8549-76c3a1e29179  
**Model hiển thị**: có dropdown "Model" trong ô nhập; bản free dùng model mặc định (không hiện rõ tên), bản Pro mới chọn được Claude/GPT-4o/Gemini

### C.1 — Entry point + lần chạm đầu

- **Trang đầu hiển thị**: logo "perplexity", ô "Ask anything..." có Search/Model/voice. Thanh trên gồm Discover, Finance, Health, Academic, Patents. Sidebar có New, Computer, Spaces, Artifacts, Customize, History. Góc trái trên có "Get Pro". Góc phải có popup "Introducing Perplexity Health".
- **Có hint/prompt mẫu không?**: Có mục "Try Computer" với task gợi ý như "Monitor the situation", "Recruiting", "Lead generation", "Organize my list"; thêm 3 ví dụ về tracking/briefing/portfolio. Các gợi ý thiên về nghiên cứu và theo dõi, không tập trung vào viết email.
- **Có đăng nhập/paywall ngay không?**: Đã đăng nhập; sidebar hiện "Upgrade plan". Free tier giới hạn Pro searches/ngày, còn basic search không giới hạn.
- **Ảnh tham chiếu**: `screenshots/product-B-1-entry.png`

### C.2 — Khi nhập prompt + nhận output

- **Độ trễ phản hồi**: khoảng 3-5 giây ở trạng thái "Thinking..." trước khi stream (chậm hơn ChatGPT do có bước crawl web)
- **Hiển thị xử lý**: Có trạng thái "Thinking" rõ ràng, sau đó mới stream output
- **Độ dài output**: khoảng 200-350 từ — gồm bảng so sánh + nhận xét + danh sách nguồn ở tab Links
- **Có trích nguồn không?**: **Có**. Đây là điểm khác biệt lớn: có tab "Links" và "Images", trong câu trả lời có đánh số [1], [2]
- **Có banner/cảnh báo không?**: Có banner "Free preview of advanced search enabled. Learn more"
- **Ảnh tham chiếu**: `screenshots/product-B-2-input.png` + `screenshots/product-B-3-output.png`

**Điểm chính trong output** (từ screenshot B-3):

Perplexity cũng đưa bảng so sánh ChatGPT/Claude/Gemini cho bài toán viết email. Cấu trúc có hệ thống nhưng đậm thông tin hơn do phải kèm citation. Người dùng có thể chuyển qua Answer/Links/Images để kiểm chứng.

### C.3 — Hành vi sau khi nhận output

- **Có regenerate/thử lại không?**: Có — có thể ask follow-up hoặc retry
- **Có copy/export không?**: Có — Share link, copy text, và có nút "Download Comet" (extension)
- **Có gợi ý câu tiếp theo không?**: Có — ô "Ask a follow-up" nằm ngay dưới output
- **Có lưu lịch sử không?**: Có — sidebar "History" lưu đầy đủ
- **Có thumb up/down rõ không?**: Không thấy rõ trong ảnh; cơ chế feedback không nổi bật bằng ChatGPT

### C.4 — 3 quan sát nổi bật

1. **Perplexity tách rõ phần nguồn** bằng tab Links/Images, nên bản chất sản phẩm nghiêng về search + summarize hơn là chatbot thuần. (Tham chiếu: `screenshots/product-B-2-input.png`)

2. **Entry point nhiều thành phần hơn** (nav bar, sidebar, popup) nên người mới cần xử lý nhiều thông tin ban đầu hơn ChatGPT. (Tham chiếu: `screenshots/product-B-1-entry.png`)

3. **Trạng thái "Thinking" dài và dễ thấy** tạo cảm giác hệ thống đang làm việc với web real-time, nhưng đánh đổi bằng wait time cao hơn mô hình instant. (Tham chiếu: `screenshots/product-B-2-input.png`)

---

## Phần D — First impressions (2 phút)

Sau khi test cả 2 công cụ, nhóm ghi nhanh 3 ý:

1. **Sản phẩm nào dễ dùng hơn ở lần đầu? Vì sao?**
   - ChatGPT dễ tiếp cận hơn do UI tối giản (1 ô nhập + vài shortcut), không phải học bố cục trước khi dùng. Perplexity có nhiều vùng chức năng và tab hơn nên tốn thời gian làm quen.

2. **Sản phẩm nào tạo cảm giác đáng tin hơn? Vì sao?**
   - Perplexity đáng tin hơn theo hướng kiểm chứng được vì có citation và tab Links. ChatGPT không kèm nguồn nên người dùng phải tự xác minh bằng kênh ngoài. Với câu hỏi so sánh tool theo thời gian, lợi thế cập nhật web của Perplexity rõ hơn.

3. **Câu hỏi nhóm chưa trả lời được sau 20 phút** (để đào thêm ở phase làm slide):
   - Free tier Perplexity có chính xác bao nhiêu Pro searches/ngày? Hết quota thì UX thay đổi ra sao?
   - Các đánh giá trong bảng của ChatGPT có bị hallucination không nếu đối chiếu benchmark thực?
   - Khi chạy lại cùng prompt lần 2, ChatGPT và Perplexity có giữ consistency hay thay đổi đáng kể?

> Đây mới là first impressions, chưa phải kết luận cuối. Ở `2-comparison-table.md` nhóm sẽ đối chiếu chéo bằng chứng để chốt.

---

## Bảng kiểm trước khi sang Bước 2

- [x] Prompt đã dùng giống hệt cho cả 2 sản phẩm.
- [x] Đã có tối thiểu 3 ảnh mỗi sản phẩm (entry + input + output).
- [x] Mỗi quan sát đều có ảnh/log tham chiếu.
- [x] First impressions có lý do cụ thể, không dùng nhận xét chung chung.
- [ ] Chưa cập nhật đủ 5 câu phân công trong `group-members.md`.

Chuyển sang `2-comparison-table.md` để dựng bảng so sánh 5 mục theo cấu trúc slide deck.

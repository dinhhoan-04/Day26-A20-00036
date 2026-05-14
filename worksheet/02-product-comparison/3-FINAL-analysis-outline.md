---
artifact: 3 — Outline 5 mục cho slide deck Analysis Report
bai-tap: 2 — Phân tích 2 sản phẩm AI (nhóm 2 học viên)
phase: Phase 3 — Dựng slide deck (15 phút)
time: 10 phút làm outline + 5 phút build slide
input: 1-research-notes.md + 2-comparison-table.md + screenshots/ + prompts/08-analysis-report.md
nop-cuoi: Có gián tiếp — outline này là xương sống cho `analysis-report.pdf` (deliverable bắt buộc)
---

# 3 — Outline 5 mục cho slide deck (S1 → S5, S5 mở rộng 8 mục con)

Mục tiêu: hoàn thiện toàn bộ nội dung báo cáo ngay trong markdown trước, sau đó mới chuyển sang PowerPoint/Keynote/Google Slides. Không làm slide khi outline chưa đủ nội dung.

Vì sao cần làm vậy: dựng trực tiếp từ log thường dẫn tới thiếu luận điểm hoặc chỉ đẹp phần hình thức. Outline buộc nhóm trả lời đầy đủ từng câu hỏi trước, để khi bị phản biện vẫn có lập luận và bằng chứng bám theo.

Quy tắc: mỗi nhận định trong outline phải truy ngược được về ảnh chụp, log test hoặc số liệu công khai. Nếu một mục con còn trống thì quay lại `1-research-notes.md` để bù dữ liệu.

## Quy trình 15 phút

```text
2 phút  — Đọc lại 2-comparison-table.md để chốt context
8 phút  — Điền đầy đủ S1 → S5
4 phút  — Mở rộng S5 thành 8 mục con (S5.1 → S5.8)
1 phút  — Soát checklist rồi mới build slide
```

> Sau khi xong outline và checklist, mới mở công cụ làm slide và xuất `analysis-report.pdf` trong cùng thư mục.

---

## Thông tin chung của báo cáo

- **Mã và tên 2 thành viên**: 00036 (Đỗ Đình Hoàn) + 00240 (Nguyễn Viết Hùng)
- **Ngành chọn**: A — Tìm kiếm
- **Nhiệm vụ test chung**: So sánh ChatGPT, Claude, Gemini cho use case viết email công việc; xác định công cụ phù hợp nhất cho người dùng cá nhân
- **Sản phẩm A**: ChatGPT Plus (GPT-5.5 instant) — https://chatgpt.com/share/456204b9-5e0f-488d-b94c-227764f3a1ac
- **Sản phẩm B**: Perplexity.ai (free tier) — https://www.perplexity.ai/search/374205bc-35cb-44db-8549-76c3a1e29179
- **Prompt dùng giống nhau**: "So sánh ChatGPT, Claude, và Gemini cho người dùng cá nhân - sản phẩm nào tốt nhất cho việc viết email công việc?"

---

## S1 — Product Moment (slide 1-2)

Mục tiêu: xác định rõ 2 sản phẩm, bối cảnh bắt đầu, và mục đích người dùng ngay từ entry point.

### S1.1 — Bảng so sánh nhanh

| Yếu tố | Sản phẩm A — ChatGPT | Sản phẩm B — Perplexity |
|---|---|---|
| Tên + URL | ChatGPT (chatgpt.com) | Perplexity.ai (perplexity.ai) |
| Entry point | "Where should we begin?" + 1 ô nhập + 3 shortcut (Create image / Write or edit / Look something up) | "Ask anything..." + nav bar (Discover/Finance/Health/Academic/Patents) + gợi ý task ở Computer mode |
| Ý định người dùng | Hỏi đáp / tạo nội dung theo kiểu hội thoại với trợ lý | Tìm kiếm và tổng hợp thông tin có nguồn kiểm chứng |
| Surface chính | **Chat** — hội thoại theo thread, có history | **Search** — trang kết quả theo query, có Answer/Links/Images |
| Đăng nhập / paywall | Đăng nhập để dùng đầy đủ; free có giới hạn; Plus $20/tháng | Basic search dùng free được; Pro $20/tháng cho advanced use |

### S1.2 — Bằng chứng ảnh

- `screenshots/product-A-1-entry.png`: giao diện đầu ChatGPT với tagline, ô nhập, shortcut và sidebar
- `screenshots/product-B-1-entry.png`: giao diện đầu Perplexity với nav bar theo domain, sidebar tính năng, nút Get Pro và popup Health

### S1.3 — Nhận định entry point

ChatGPT thân thiện hơn với người mới nhờ thiết kế tối giản và mental model quen thuộc kiểu "nhắn tin cho trợ lý". Perplexity cho cảm giác chuyên sâu hơn về research vì nhiều module và ngữ cảnh tìm kiếm, nhưng người mới cần thêm thời gian định hướng. Ngay từ màn hình đầu, hai sản phẩm đã thể hiện hai triết lý khác nhau: ChatGPT ưu tiên đối thoại; Perplexity ưu tiên truy xuất thông tin có nguồn.

---

## S2 — Workflow Evidence (slide 3-4)

Mục tiêu: mô tả luồng sử dụng thực tế và chỉ ra friction theo Lens 3.

### S2.1 — Luồng người dùng trước/trong/sau khi dùng AI

```text
TRƯỚC khi gặp AI:
- Người dùng có nhu cầu so sánh 3 AI tool cho việc viết email công việc
- Môi trường test: trình duyệt Cốc Cốc

TRONG khi dùng ChatGPT:
1) Vào chatgpt.com, thấy giao diện đơn giản, bắt đầu ngay
2) Dán prompt và gửi
3) Chờ khoảng 2-3 giây, output stream theo thời gian thực
4) Đọc verdict + bảng 8 tiêu chí
5) (Tùy chọn) dùng "Search the web" để kiểm chứng thêm

TRONG khi dùng Perplexity:
1) Vào perplexity.ai, xử lý nhiều UI blocks/popup ban đầu
2) Dán prompt và gửi
3) Chờ trạng thái "Thinking" khoảng 4-5 giây
4) Đọc Answer, mở Links để xem citation
5) (Tùy chọn) click từng nguồn để kiểm chứng sâu

SAU khi dùng AI:
- Copy câu trả lời vào note
- Cả 2 đều lưu lịch sử để truy lại
```

### S2.2 — 3 friction areas

| Friction | Sản phẩm A — ChatGPT | Sản phẩm B — Perplexity |
|---|---|---|
| **Physical load** | Thấp: 3 bước chính, không cần chuyển tab nội bộ để đọc kết quả | Cao hơn: thêm bước chuyển Answer/Links/Images và mở link ngoài |
| **Cognitive burden** | Thấp: UI gọn, shortcut rõ, prompt là dùng được ngay | Trung bình: nhiều mục điều hướng và mode, cần hiểu ngữ nghĩa từng tab |
| **User workarounds** | Phải tự kiểm chứng ngoài vì output không có source trực tiếp | Phải tự chọn nguồn đáng tin khi có nhiều link/có thể mâu thuẫn |

### S2.3 — Bằng chứng workflow

- `screenshots/product-A-2-input.png`: prompt đã nhập và trạng thái stream
- `screenshots/product-A-3-output.png`: output có verdict + bảng 8 tiêu chí
- `screenshots/product-B-2-input.png`: trạng thái "Thinking" + các tab
- `screenshots/product-B-3-output.png`: output có cấu trúc + citation

### S2.4 — Nhận định friction

Với nhiệm vụ so sánh AI tool để viết email, ChatGPT giảm friction tốt hơn vì flow ngắn và đọc kết quả nhanh. Perplexity tăng số thao tác nhưng đổi lại cho khả năng kiểm chứng nguồn rõ ràng hơn. Do đó lựa chọn sản phẩm phụ thuộc vào nhu cầu chính: cần tốc độ tiêu thụ thông tin thì ChatGPT thuận lợi; cần độ kiểm chứng thì Perplexity phù hợp hơn.

---

## S3 — Output & Trust (slide 5-6)

Mục tiêu: đánh giá chất lượng đầu ra và mức độ đáng tin theo 6 tín hiệu.

### S3.1 — Chất lượng output

- **ChatGPT**:
  - Trả lời đúng trọng tâm câu hỏi và có kết luận rõ ở đầu.
  - Trình bày tốt (bảng 8 tiêu chí, tiếng Việt tự nhiên, dễ đọc).
  - Điểm yếu chính: không citation nên khó xác minh từng mệnh đề.

- **Perplexity**:
  - Trả lời đủ ý, có bảng so sánh tương đương.
  - Có tab Links/Images và đánh số nguồn [1][2] giúp kiểm chứng.
  - Nhược điểm: output dày hơn, người dùng phải tự lọc thông tin.

### S3.2 — Đối chiếu 6 trust signals

| Tín hiệu | ChatGPT | Perplexity |
|---|---|---|
| 1. Citation | Không có citation trực tiếp trong output | Có citation và link kiểm chứng |
| 2. Disclaimer | Có cảnh báo chung ở footer | Có cảnh báo giới hạn advanced search (một phần) |
| 3. Fallback out-of-scope | Một phần: thường vẫn trả lời | Tốt hơn ở truy vấn web-based, có thể báo thiếu dữ liệu |
| 4. Consistency (lặp prompt) | Một phần: cấu trúc tương tự, wording thay đổi | Một phần: phụ thuộc kết quả web tại thời điểm query |
| 5. User control | Đủ: stop/regenerate/edit/copy/share | Có follow-up/retry/share/copy |
| 6. Explain "vì sao" | Có lý giải bằng lập luận nhưng không dẫn nguồn | Có nguồn, nhưng chuỗi reasoning không minh bạch hoàn toàn |

### S3.3 — Nhận định trust

Perplexity mạnh hơn ở trust theo hướng kiểm chứng (verifiable trust) nhờ citation. ChatGPT mạnh hơn ở trust theo trải nghiệm tiêu thụ thông tin (cognitive ease): dễ đọc, dễ quyết định nhanh. Với tác vụ thiên về research/fact-checking, Perplexity lợi thế hơn; với tác vụ cần ra kết luận nhanh để hành động, ChatGPT hiệu quả hơn.

---

## S4 — Business Signal (slide 7)

Mục tiêu: định vị chiến lược kinh doanh của 2 sản phẩm qua cost-capability-speed và mô hình giá.

### S4.1 — Vị trí trên tam giác Cost-Capability-Speed

- **ChatGPT**: nghiêng về **mạnh-đắt**
  - Lý do: định giá dựa trên năng lực model và chất lượng trải nghiệm; Plus $20/tháng là điểm vào của tier cao.

- **Perplexity**: nghiêng về **rẻ-nhanh**
  - Lý do: free tier dùng được rộng cho basic search; trọng tâm là truy xuất web và tổng hợp nhanh có nguồn.

### S4.2 — Pattern giá và cơ chế paywall

| Yếu tố | ChatGPT | Perplexity |
|---|---|---|
| Mô hình giá | Freemium → Plus/Team/Enterprise | Freemium → Pro/Enterprise |
| Free tier giới hạn gì | Giới hạn số message/model cao cấp | Giới hạn số advanced/Pro searches/ngày |
| Gói chính trả phí | Plus $20/tháng, Team $30/user/tháng | Pro $20/tháng |
| Điểm kích hoạt upsell | Khi chạm giới hạn message hoặc dùng tính năng cao cấp | Khi chạm quota Pro searches và cần advanced mode |

### S4.3 — Nhận định chiến lược

ChatGPT triển khai "capability-gated freemium": miễn phí đủ dùng cơ bản, trả phí để có model mạnh và ít giới hạn. Perplexity triển khai "frequency-gated freemium": tính năng cốt lõi vẫn dễ tiếp cận, nhưng người dùng chuyên sâu phải nâng cấp để dùng thường xuyên. Cùng mức giá $20/tháng nhưng value proposition khác nhau: ChatGPT bán năng lực model, Perplexity bán tốc độ + kiểm chứng nguồn.

---

## S5 — Product Judgment (slide 8-12, trọng tâm)

Mục tiêu: chốt verdict cuối cùng bằng cách vận dụng 4 Lens + Spark/Loop/System + Niche/Feature map + liên hệ Lab 1.

S5 gồm 8 mục con. Nhóm bắt buộc hoàn thành S5.1, S5.6, S5.7, S5.8; phần còn lại làm đầy đủ khi có đủ dữ liệu.

### S5.1 — Verdict (BẮT BUỘC)

- **ChatGPT: Strong**
  - Lý do: quy mô người dùng rất lớn (400M+ WAU), ARR cao, thương hiệu top-of-mind; nhưng vẫn chịu áp lực đổi mới liên tục từ Claude/Gemini.

- **Perplexity: Promising**
  - Lý do: có khác biệt rõ ở AI search có citation và đang tăng nhanh, nhưng distribution moat yếu trước Google/Bing.

### S5.2 — User base + tăng trưởng

- **ChatGPT**:
  - 400M weekly active users (tháng 2/2025)
  - Nguồn tham chiếu: phát ngôn công khai từ OpenAI/Sam Altman, báo công nghệ (14/02/2025)
  - Paid subscribers: khoảng ~100M (ước tính, không phải số công bố chính thức)
  - Tăng trưởng: từ 100M users (01/2023) lên 400M WAU (02/2025)

- **Perplexity**:
  - MAU ước tính khoảng 15-20M (giai đoạn 2024-2025)
  - Nguồn: báo chí tài chính/công nghệ, chưa có số chính thức từ công ty
  - Tăng trưởng từ base nhỏ nhưng nhanh (ước tính 10M → 15-20M trong năm 2024)
  - Ghi chú: công ty tư nhân nên dữ liệu người dùng công khai hạn chế

### S5.3 — Doanh thu / pricing power

- **ChatGPT**:
  - ARR khoảng $3.4B cuối 2024 (theo nguồn báo chí)
  - Kế hoạch doanh thu 2025 từng được báo cáo ở mức rất cao (~$11.6B)
  - Pricing strategy: freemium đẩy lên Plus/Team/Enterprise, bán theo capability

- **Perplexity**:
  - ARR ước tính khoảng $20-50M (2024), không có công bố chính thức
  - Valuation reported khoảng $9B ở vòng gọi vốn đầu 2025
  - Pricing strategy: freemium giới hạn tần suất advanced usage, upsell lên Pro

### S5.4 — Moat phân tích (5 loại)

| Moat | ChatGPT | Perplexity |
|---|---|---|
| Data moat | **Mạnh** — tín hiệu RLHF khổng lồ từ lượng user lớn | **Trung bình** — có query/click data nhưng quy mô nhỏ hơn nhiều so với big tech |
| Network effects | **Trung bình** — có hệ sinh thái API/GPTs nhưng phần lớn vẫn là single-user interaction | **Yếu** — các phiên search khá độc lập, hiệu ứng mạng trực tiếp thấp |
| Switching cost | **Trung bình** — history, projects, workflow tạo lock-in nhất định | **Yếu** — chuyển qua công cụ search khác tương đối dễ |
| Brand | **Mạnh** — mức nhận diện đại chúng rất cao | **Trung bình** — mạnh trong cộng đồng tech/research hơn là đại chúng |
| Distribution | **Mạnh** — web/app/API và hệ sinh thái tích hợp rộng | **Yếu** — không nắm kênh phân phối nền tảng như Google/Microsoft |

### S5.5 — Data flywheel + feedback loop

- **ChatGPT**:
  - Hành vi user feed loop: prompt, follow-up, thumbs up/down, regenerate.
  - Loop có compounding rõ: nhiều user → nhiều tín hiệu → model tốt hơn → giữ/chốt thêm user.
  - Memory + Project làm tăng mức gắn bó và chi phí rời bỏ.

- **Perplexity**:
  - Hành vi feed loop: query, click nguồn, follow-up.
  - Loop có nhưng phụ thuộc vào tầng model phía dưới (OpenAI/Anthropic/Google), nên lợi thế cốt lõi không mạnh bằng nền tảng tự huấn luyện model.
  - Điểm khác biệt chính vẫn là chất lượng orchestration + retrieval hơn là model moat riêng.

### S5.6 — Niche Down + AI Feature Map (BẮT BUỘC)

- **ChatGPT**
  - Niche: trợ lý AI đa dụng cho cá nhân + doanh nghiệp (viết, code, học, phân tích).
  - User Value: **cao** (output tốt, đa năng).
  - User Alignment: **cao** (UI đơn giản, vào dùng nhanh).
  - Business Value: **cao** (paid base lớn, upsell rõ).

- **Perplexity**
  - Niche: AI search có citation cho người dùng cần kiểm chứng.
  - User Value: **trung bình-cao** (độ tin cậy tăng nhờ nguồn).
  - User Alignment: **trung bình** (learning curve cao hơn do UI và workflow).
  - Business Value: **trung bình** (user base nhỏ hơn, đang mở rộng vertical để tăng ARPU).

### S5.7 — Spark → Loop → System (BẮT BUỘC)

- **ChatGPT: System**
  - Vì sao: đã ở quy mô người dùng cực lớn, doanh thu lớn, hệ sinh thái nhiều lớp (app + API + enterprise), không còn là giai đoạn thử nghiệm loop cơ bản.
  - Dự báo 12 tháng: tiếp tục mở rộng agent use cases và enterprise adoption; rủi ro chính là đối thủ vượt capability với tốc độ cao.

- **Perplexity: Loop**
  - Vì sao: đã chứng minh PMF ở AI search và đang mở rộng tính năng, nhưng chưa có distribution moat kiểu nền tảng.
  - Dự báo 12 tháng: áp lực lớn từ Google AI Overviews; cần bám các ngách chuyên sâu (academic, enterprise research, vertical intelligence) để tránh đối đầu trực diện.

### S5.8 — Liên hệ Lab 1 (BẮT BUỘC)

- **Rủi ro của ChatGPT**: dù đang ở vị thế mạnh, vẫn có nguy cơ bị "nén" như các case từng dẫn đầu nếu để đối thủ vượt capability + UX trong một chu kỳ ngắn.

- **Rủi ro của Perplexity**: khá giống pattern đã phân tích ở Lab 1 về việc bị big tech bundle tính năng tương đương vào nơi người dùng đã hiện diện sẵn. Nếu không có moat phân phối riêng, tăng trưởng dễ bị bóp nghẹt.

- **Bài học áp dụng**:
  1. Khi thiết kế sản phẩm AI, moat phân phối là điểm cần phòng thủ đầu tiên.
  2. Cần phân biệt rõ "feature tốt" với "vị trí sản phẩm trong hệ sinh thái"; feature có thể bị copy nhanh, vị trí phân phối mới khó thay thế.
  3. Luôn chuẩn bị phương án niche-down cho kịch bản Big Squeeze xảy ra.

---

## Checklist trước khi build slide

- [x] Đã điền đầy đủ S1 → S4.
- [x] Đã hoàn tất S5.1 + S5.6 + S5.7 + S5.8 (mục bắt buộc).
- [x] Đã có nội dung S5.2 → S5.5, chỗ nào ước tính đều ghi rõ.
- [x] Mỗi nhận định nối được về ảnh/log/số liệu cụ thể.
- [x] Verdict đồng nhất với phân tích moat và giai đoạn Spark/Loop/System.
- [ ] Cần hai thành viên rà và xác nhận lần cuối trước khi xuất PDF.

---

## Sau khi xong outline

1. Mở PowerPoint/Keynote/Google Slides/Figma.
2. Dựng 12-15 slide theo cấu trúc S1 → S5.
3. Mỗi slide đặt tối thiểu 1 ảnh chứng cứ từ `screenshots/`.
4. Xuất file `analysis-report.pdf` trong cùng thư mục.
5. Nếu có bản Google Slides public, lưu thêm `analysis-report-link.md` (tùy chọn).
6. Cả hai thành viên copy `analysis-report.pdf` và `group-members.md` về repo cá nhân.

> Nếu cần AI hỗ trợ dựng slide từ outline, tham chiếu `prompts/08-analysis-report.md`.

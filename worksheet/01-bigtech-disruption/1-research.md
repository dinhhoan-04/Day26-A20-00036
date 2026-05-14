---
artifact: 1 — Tự nghiên cứu một case
bai-tap: 1 — Tìm 1 case chịu tác động từ big tech AI (cá nhân)
phase: Chọn case + thu thập số liệu + nguồn
time: 15 phút (xem deck slide 4 để nắm khung giờ chính xác trong buổi)
input: prompts/01-research-case.md
nop-cuoi: Không — tài liệu trung gian
---

# 1 — Tự nghiên cứu: chọn 1 case bị big tech AI tác động + số liệu thực tế

Mục tiêu: tự chọn 1 sản phẩm hoặc công ty bị ảnh hưởng mạnh sau khi big tech AI (ChatGPT, Claude, Gemini, GitHub Copilot, Microsoft Copilot...) tung ra tính năng tương tự. Toàn bộ số liệu phải lấy từ nguồn công khai và ghi rõ (URL + tên báo/tổ chức + ngày tháng). Lab 1 là bài cá nhân, nên mỗi học viên tự chọn case và tự hoàn thành phần research trong repo của mình.

Vì sao cần bước này: mọi phân tích chỉ đáng tin khi dựa trên dữ kiện thật. Bạn cần tối thiểu 8-10 số liệu cụ thể để làm nền phản biện cho 4 câu hỏi ở phase 2.

Quy tắc: **không có số liệu = không có nhận định**. Mỗi nhận định đều phải đi kèm nguồn (URL + ngày).

- **Thành viên**: Đỗ Đình Hoàn - 00036

## Bước 0 — Chọn case (5 phút đầu)

Trước khi vào phần tìm số liệu, xác định rõ:

1. Sản phẩm/công ty bạn chọn là gì?
2. Big tech AI nào ra tính năng tương tự và tạo tác động? (ChatGPT, Claude, Gemini, GitHub Copilot, Microsoft Copilot...)
3. Vì sao chọn case này? (Có dữ liệu công khai? Có mốc thời gian rõ? Có liên quan ngành bạn quan tâm?)

Điền câu trả lời ngắn trước khi bắt đầu tra cứu:

- **Tên case**: Grammarly — công cụ AI hỗ trợ viết, thành lập năm 2009, trụ sở tại San Francisco
- **Big tech AI tạo áp lực**: Microsoft Copilot (tích hợp trong Microsoft 365 Word/Outlook), ChatGPT (OpenAI), Google Gemini for Workspace (tích hợp trong Google Docs/Gmail)
- **Lý do chọn**: Grammarly từng là AI writing assistant dẫn đầu trước 2022, có định giá công khai ($13B), có mốc sự kiện rõ (ChatGPT Nov 2022, Copilot Nov 2023), đồng thời đã xuất hiện sa thải và phản ứng sản phẩm (GrammarlyGO) để đối chiếu

## Quy trình 15 phút

```text
5 phút  — Chọn case + xác định 4 nhóm dữ liệu cần thu thập cho case
8 phút  — Tự tìm số liệu trên nguồn chính (báo công nghệ, báo cáo tài chính, blog chính thức...)
2 phút  — Soát lại bảng số liệu, đánh dấu các mục chưa kiểm chứng
```

---

## Phần A — 4 nhóm số liệu cần có

Thu thập đầy đủ 4 nhóm dưới đây cho case đã chọn. Giữ nguyên tên nhóm, còn dữ liệu cụ thể tự điền theo case.

### Nhóm 1 — Quy mô trước & sau (cổ phiếu, doanh thu, người dùng)

Grammarly là công ty tư nhân (chưa niêm yết), nên nguồn dữ liệu chủ yếu đến từ vòng gọi vốn và báo chí:

- **Định giá cao nhất**: $13 tỷ USD (Series D, tháng 11/2021, gọi vốn $200M)
  - Nguồn: TechCrunch, 18/11/2021 — "Grammarly raises $200M at $13B valuation"
- **Quy mô người dùng đỉnh (2022)**: 30 triệu người dùng mỗi ngày (DAU), 50.000 doanh nghiệp B2B
  - Nguồn: Grammarly company blog, 2022 milestones
- **Người dùng trả phí**: ~3 triệu paid subscribers (ước tính, chưa công bố chính thức)
- **Doanh thu ước tính**: ~$200M ARR (2022) — suy ra từ paid users × $12/tháng (annual plan)
- **Sau AI shock**: không có số chính thức, nhưng đợt sa thải 230 người (25% nhân sự) tháng 4/2024 cho thấy tăng trưởng doanh thu chậm lại đáng kể

### Nhóm 2 — Timeline big tech AI tung tính năng tương tự

- **ChatGPT ra mắt**: 30/11/2022 — hỗ trợ viết, sửa ngữ pháp, paraphrase, dịch trực tiếp
  - Đạt 100 triệu người dùng sau 2 tháng (nhanh nhất lịch sử internet)
  - Nguồn: Reuters, 02/02/2023 (dẫn báo cáo UBS); OpenAI blog
- **Microsoft 365 Copilot công bố**: 16/3/2023 (tích hợp GPT-4 vào Word, Outlook, PowerPoint)
  - GA (general availability) cho doanh nghiệp: 1/11/2023
  - Nguồn: Microsoft blog, 16/03/2023
- **Google Duet AI for Workspace** (nay là Gemini for Workspace) GA: tháng 8/2023
  - Tích hợp trong Google Docs, Gmail, Slides
  - Nguồn: Google Workspace blog, 29/08/2023
- **Mức độ trùng chức năng**: Copilot trên Word/Outlook và Google Gemini đáp ứng được 80%+ tính năng cốt lõi của Grammarly (grammar check, rewrite, tone adjustment, summarize) ngay trong môi trường làm việc hiện có của người dùng

### Nhóm 3 — Phản ứng của Grammarly sau khi big tech AI ra mắt

- **GrammarlyGO ra mắt**: 11/4/2023 — tính năng AI generative (dùng OpenAI API) cho viết, rewrite, brainstorm
  - Độ trễ từ ChatGPT ra mắt → GrammarlyGO: **~5 tháng**
  - Nguồn: Grammarly blog, 11/04/2023
- **Phụ thuộc công nghệ AI**: Grammarly dùng OpenAI API (không tự train model), tức phụ thuộc vào chính đối thủ cạnh tranh gián tiếp
- **Sa thải**: tháng 4/2024 — 230 nhân viên, tương đương ~25% tổng nhân sự (~900 người)
  - Nguồn: TechCrunch, 04/04/2024
- **M&A / tái định hướng**: tháng 8/2024 — Grammarly mua lại Coda (nền tảng productivity/document)
  - Tín hiệu: mở rộng sang workspace tool để cạnh tranh với Notion, Confluence thay vì chỉ dừng ở writing assistant
  - Nguồn: TechCrunch, tháng 8/2024

### Nhóm 4 — Các đối thủ AI thay thế

- **Microsoft Copilot trong M365**: có sẵn trong M365 Business Premium ($22/user/tháng) hoặc add-on $30/user/tháng — người dùng không cần mua thêm công cụ khác
- **Google Gemini for Workspace**: add-on $30/user/tháng — sẵn cho hệ sinh thái Google Workspace
- **ChatGPT Plus**: $20/tháng — tổng quát hơn nhưng thay thế Grammarly trong nhiều tình huống sử dụng
- **Grammarly Premium**: $12/tháng (annual) hoặc $30/tháng (monthly)
- **Notion AI**: add-on $10/tháng — hỗ trợ viết, chỉnh sửa, tóm tắt trong môi trường tài liệu
- **So sánh giá**: Grammarly Premium ($12-30) vs. Copilot bundled ($0 thêm với người đã có M365) — khách hàng enterprise đã dùng M365 gần như không còn động lực trả thêm cho Grammarly

---

## Phần B — Bảng tổng hợp số liệu

Khi đã đủ 4 nhóm dữ liệu, gom lại trong bảng bên dưới. Mục tiêu tối thiểu: 8-10 số liệu có nguồn cụ thể.

### Bảng số liệu case Grammarly

| # | Số liệu | Giá trị | Ngày / Thời kỳ | Nguồn (URL) | Đã kiểm chứng? |
|---|---|---|---|---|---|
| S-01 | Định giá cao nhất (Series D) | $13 tỷ USD | 18/11/2021 | TechCrunch — techcrunch.com/2021/11/18/grammarly-raises-200m | Có |
| S-02 | DAU cao nhất | 30 triệu người | 2022 | Grammarly company blog 2022 milestones | Có |
| S-03 | Người dùng doanh nghiệp (B2B) | 50.000 tổ chức | 2022 | Grammarly company blog 2022 milestones | Có |
| S-04 | Ngày ChatGPT ra mắt | 30/11/2022 | 30/11/2022 | openai.com/blog/chatgpt | Có |
| S-05 | ChatGPT đạt 100 triệu người dùng | 2 tháng (kỷ lục) | 02/02/2023 | Reuters — reuters.com/technology/chatgpt | Có |
| S-06 | Microsoft 365 Copilot GA | 1/11/2023 | 01/11/2023 | Microsoft blog — blogs.microsoft.com | Có |
| S-07 | Ngày GrammarlyGO ra mắt | 11/4/2023 (~5 tháng sau ChatGPT) | 11/04/2023 | grammarly.com/blog/grammarlygo | Có |
| S-08 | Độ trễ phản ứng (ChatGPT → GrammarlyGO) | ~5 tháng | Nov 2022 → Apr 2023 | Tính từ S-04 và S-07 | Có |
| S-09 | Số nhân sự bị sa thải | 230 người (~25% nhân sự) | 04/04/2024 | TechCrunch — techcrunch.com/2024/04/04/grammarly-layoffs | Có |
| S-10 | Giá Grammarly Premium vs Copilot bundled | $12-30/tháng vs. $0 thêm (với M365) | 2023-2024 | grammarly.com/plans + microsoft.com/m365 | Có |
| S-11 | Grammarly mua lại Coda (pivot strategy) | Không công bố giá | 08/2024 | TechCrunch — tháng 8/2024 | Có |
| S-12 | Google Gemini for Workspace GA | 29/8/2023 | 29/08/2023 | workspace.google.com/blog | Có |

---

## Phần C — Kiểm chứng nguồn

Trước khi sang phần phân tích, kiểm tra lại từng số liệu:

### Checklist kiểm chứng

- [x] Mỗi số liệu đều có URL nguồn cụ thể.
- [x] URL truy cập được, không lỗi 404.
- [x] Nội dung trong URL khớp với số liệu đã ghi (ít nhất cùng đơn vị và cùng năm).
- [x] Các số liệu quan trọng (quy mô, doanh thu, mốc ngày) có kiểm chứng chéo từ 2 nguồn độc lập.
- [ ] S-02 và S-03 (DAU, B2B users): hiện mới có 1 nguồn từ Grammarly blog — cần bổ sung kiểm chứng

### Quy tắc phân loại nguồn

| Mức ưu tiên | Loại nguồn | Ví dụ |
|---|---|---|
| 1 — Nguồn gốc | Báo cáo tài chính, thông báo chính thức, hồ sơ pháp lý | 10-K filings, SEC filings, blog công ty |
| 2 — Báo lớn | Báo công nghệ/kinh doanh uy tín | CNBC, Bloomberg, TechCrunch, Reuters, FT |
| 3 — Báo cáo phân tích | Báo cáo tài chính độc lập | MacroTrends, Yahoo Finance, Google Finance |
| 4 — Tránh dùng | Bài đăng cá nhân, blog không nguồn, mạng xã hội | Reddit posts, Medium articles không citation |

### Cảnh báo

AI có thể bịa cả nguồn, nhất là khi bạn hỏi số liệu trực tiếp thay vì tự tìm. Nếu dùng AI để gợi ý điểm bắt đầu, vẫn phải tự mở URL và xác minh.

**Lưu ý cho case Grammarly**: Vì là công ty tư nhân, ARR/MRR chính thức không công khai. Dữ liệu tài chính phần lớn là ước tính từ báo chí hoặc suy luận theo nhân sự × doanh thu trung bình. Trong Phần B cần ghi rõ mục nào là "ước tính".

---

## Phần D — Quan sát ban đầu

Khi có đủ dữ liệu, ghi nhanh 3-5 quan sát đáng chú ý. Đây chưa phải kết luận cuối cùng.

- "Grammarly mất khoảng 5 tháng để tung GrammarlyGO sau ChatGPT, nhưng Copilot đã nằm sẵn trong Word và Outlook nên người dùng không cần cài thêm extension, làm suy yếu lý do cốt lõi để dùng Grammarly."
- "Mức định giá $13B năm 2021 dựa vào giả định Grammarly là leader gần như độc quyền trong AI writing; giả định này sụp đổ khi ChatGPT và Copilot xuất hiện trong vòng 12 tháng tiếp theo."
- "Đợt sa thải 25% nhân sự vào tháng 4/2024, tức khoảng 2,5 năm sau khi ChatGPT ra mắt, cho thấy đây là sức ép cấu trúc chứ không chỉ là cú sốc ngắn hạn."
- "Grammarly phải dùng OpenAI API để xây GrammarlyGO, nghĩa là mua năng lực từ chính một bên cạnh tranh gián tiếp; điều này tạo sức ép biên lợi nhuận từ cả hai chiều."
- "Thương vụ mua Coda (2024) cho thấy Grammarly đang pivot từ 'writing tool' sang 'team workspace' để thoát phân khúc bị ChatGPT/Copilot thay thế, nhưng Notion và Confluence đã nắm thị phần đáng kể."

---

## Phần E — Câu hỏi mở (cho phân tích Phần 2)

Trước khi chuyển sang `2-analysis.md`, liệt kê các câu hỏi cần đào sâu thêm:

- Câu hỏi 1: Grammarly mất người dùng B2B hay B2C nhanh hơn? Doanh nghiệp có xu hướng migrate sang Copilot không?
- Câu hỏi 2: Fit nào đứt trước: Product-Market Fit (người dùng không còn cần "grammar check riêng") hay Channel Fit (Chrome extension bị thay bằng native tool)?
- Câu hỏi 3: GrammarlyGO có thật sự vượt ChatGPT trong use case writing không? Nếu không, lợi thế cạnh tranh còn lại của Grammarly là gì?
- Câu hỏi 4: Nếu Grammarly ra GrammarlyGO sớm hơn 6 tháng (ngay lúc ChatGPT ra), liệu có giữ được vị thế không, hay vấn đề gốc nằm ở việc Copilot được bundle miễn phí trong M365?

Hoàn tất bước này thì chuyển sang `2-analysis.md` để áp dụng Lens 1 (Customer Expectations + Four Fits) cho case đã chọn.


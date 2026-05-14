---
artifact: group-members — Danh sách nhóm Lab 2
bai-tap: 2 — Phân tích sản phẩm AI (làm theo nhóm)
phase: Khai báo nhóm
nop-cuoi: Có — bắt buộc (nộp cùng analysis-report.pdf)
---

# Thành viên nhóm Lab 2

Lab 2 thực hiện theo nhóm 2 học viên. Mỗi người giữ repo riêng (`Day26-MãHọcViên`), nhưng bộ tài liệu Lab 2 (slide deck + screenshots + notes) là sản phẩm dùng chung, sau đó copy về từng repo cá nhân.

File này dùng để khai báo thông tin 2 thành viên và phần việc chính của từng người.

---

## Danh sách thành viên

| # | Mã học viên | Họ tên đầy đủ | Phân công chính |
|---|---|---|---|
| 1 | 00036 | Đỗ Đình Hoàn | Phụ trách tổng hợp phân tích, hoàn thiện bảng so sánh và outline báo cáo |
| 2 | 00240 | Nguyễn Viết Hùng | Phụ trách test sản phẩm, chụp screenshot, đối chiếu nguồn và kiểm chứng log |

---

## Nhiệm vụ thử nghiệm chung

Cả hai thành viên cùng chạy một prompt để so sánh công cụ AI cho use case viết email công việc, sau đó đối chiếu trải nghiệm, chất lượng output và tín hiệu trust giữa hai sản phẩm.

**Ngành chọn**: A — Tìm kiếm

**Sản phẩm A**: ChatGPT Plus (GPT-5.5 instant) — https://chatgpt.com/share/6a0576d7-0920-83ec-868b-4f1c26200572

**Sản phẩm B**: Perplexity.ai (Free) — https://www.perplexity.ai/search/374205bc-35cb-44db-8549-76c3a1e29179

---

## Phân chia screenshot

- Sản phẩm A → Đỗ Đình Hoàn - 00036 phụ trách chụp và chú thích
- Sản phẩm B → Nguyễn Viết Hùng - 00240 phụ trách chụp và chú thích

---

## Ghi chú

- Mỗi thành viên sao chép toàn bộ folder `02-product-comparison/` (đã hoàn thiện) vào repo cá nhân.
- `analysis-report.pdf` và `analysis-report-link.md` (nếu có) là tài liệu chung, cần ghi đủ tên 2 thành viên trong phần credits.
- `group-members.md` phải đồng nhất ở cả hai repo cá nhân (nội dung giống nhau, đúng 2 mã học viên).

---

## Cấu trúc Analysis Report — S5 mở rộng

Deck Analysis Report gồm 5 mục bắt buộc (S1 → S5). Trong đó S5 (Product Judgment) được mở rộng thành 8 mục con để bám sát phân tích định lượng đã làm ở Lab 1 Phần B.

- **S5.1 Verdict** — gán nhãn Strong / Promising / Weak / At Risk cho từng sản phẩm, kèm lý do 1 câu.
- **S5.2 User base + tăng trưởng** — ghi số liệu công khai (MAU, DAU, paid users, growth) của cả hai sản phẩm + nguồn.
- **S5.3 Doanh thu / pricing power** — phân tích mức giá, ARR/MRR (nếu có), và chiến lược freemium/premium/enterprise.
- **S5.4 Moat phân tích** — chấm 5 moat (data / network / switching cost / brand / distribution), nêu moat mạnh và moat dễ bị sao chép.
- **S5.5 Data flywheel + feedback loop** — xác định hành vi user nào feed model, loop có compounding không, và mức độ thu thập feedback có hệ thống.
- **S5.6 Niche Down + AI Feature Map** — xác định niche và map User Value / User Alignment / Business Value cho từng sản phẩm.
- **S5.7 Spark → Loop → System** — định vị giai đoạn hiện tại của mỗi sản phẩm và dự báo 12 tháng tới.
- **S5.8 Liên hệ Lab 1 case** — đối chiếu rủi ro disruption của 2 sản phẩm với case Lab 1 và rút bài học áp dụng.

Yêu cầu tối thiểu: hoàn tất **S5.1, S5.6, S5.7, S5.8**.  
Phần nâng cao: hoàn tất thêm S5.2–S5.5; nếu thiếu dữ liệu công khai, ghi rõ "không có nguồn công khai".

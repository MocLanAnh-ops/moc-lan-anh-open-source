# C2 - Templates / Mẫu

## Mục đích (Purpose)

Thư mục này chứa các **template chuẩn** để tạo nội dung nhất quán trong toàn bộ repository.

---

## Các loại Template

### 1. **Training Templates** (Đào tạo)
Dành cho nội dung phân tích, học tập, phát triển năng lực.

**Đặc điểm:**
- Tone trung lập, khách quan
- Focus vào logic decomposition
- Không có call-to-action thương mại
- Audience: Học viên, trainers, HR

**Files:**
- `template_field_case_training_v1.md` - Phân tích tình huống thực địa
- `template_lyric_co-listening_v1.md` - Hướng dẫn đồng nghe nhạc
- `template_style_prompt_v1.md` - Thiết lập style cho AI

---

### 2. **Application Templates** (Ứng dụng)
Dành cho sản phẩm, dự án, công bố công khai.

**Đặc điểm:**
- Tone inspiring, poetic nhưng technical
- Focus vào philosophy + specs + collaboration
- Có call-to-action rõ ràng
- Audience: Khách hàng, partners, public (LinkedIn, GitHub)

**Files:**
- `template_field_case_application_v1.md` ✨ NEW - Product/Project documentation

---

## So sánh 2 loại Template

| Tiêu chí | Training Template | Application Template |
|----------|-------------------|----------------------|
| **Mục đích** | Phân tích để học | Công bố để hợp tác |
| **Tone** | Trung lập | Inspiring + Technical |
| **Cấu trúc** | Logic decomposition | Philosophy + Specs + Invitation |
| **Audience** | Internal (học viên) | External (public) |
| **Platform** | Internal docs | LinkedIn, GitHub README, Conferences |
| **Ví dụ** | "Tại sao candidate này phù hợp?" | "Why this wooden island matters?" |

---

## Khi nào dùng Template nào?

### ✅ Dùng **Training Template** khi:
- Phân tích tình huống thực tế để rút kinh nghiệm
- Tạo bài tập cho học viên
- Document quyết định nội bộ
- Không công bố ra ngoài (hoặc chỉ công bố sau khi anonymize)

**Ví dụ:**
- "Hiring Signal Detection" - Phân tích quy trình tuyển dụng
- "Co-listening Session Analysis" - Đánh giá buổi nghe nhạc với AI

---

### ✅ Dùng **Application Template** khi:
- Launch sản phẩm/dự án mới
- Viết bài LinkedIn/blog công khai
- Tạo README cho GitHub project
- Tìm kiếm partners/collaborators

**Ví dụ:**
- "Wooden Medicinal Island Technical Brief" - Product documentation
- "Bio-Computing Architecture" - Research project announcement

---

## Quy tắc sử dụng Template

### Training Template:
1. ❌ Không thêm mục mới nếu không cần thiết
2. ❌ Không kể lại toàn bộ hội thoại
3. ❌ Không dùng ngôn ngữ kết luận đạo đức
4. ✅ Mỗi case = 1 câu hỏi chạm
5. ✅ Viết để 5 năm sau đọc lại vẫn hiểu

### Application Template:
1. ❌ Không oversell bằng marketing jargon
2. ❌ Không hide technical limitations
3. ❌ Không skip philosophy section
4. ✅ Keep technical specs in tables
5. ✅ End with invitation, not sales pitch
6. ✅ Make closing poetic but grounded

---

## Cấu trúc file Template

```
template_<type>_<purpose>_v<version>.md

Examples:
- template_field_case_training_v1.md
- template_field_case_application_v1.md
- template_lyric_co-listening_v1.md
```

**Version naming:**
- v1.0 = Stable release
- v1.1 = Minor improvements
- v2.0 = Major restructure

---

## Examples / Ví dụ điền sẵn

Xem thư mục `C1_field_cases` để thấy các ví dụ thực tế:

**Training examples:**
- `2026-01-22_hiring-signal-detection.md`
- `2026-01-23_lyric_co-listening_v1.md`

**Application examples:**
- `2026-01-29_wooden-medicinal-island-technical-brief.md` ✨
- `2026-01-30_wooden-medicinal-island-discovery.md`

---

## Contribution Guidelines

Khi tạo template mới:

1. **Identify need:** Có pattern lặp lại ≥3 lần → Cần template
2. **Create draft:** Copy từ template gần nhất, modify
3. **Test with 2 real cases:** Thử điền nội dung thật
4. **Refine:** Bỏ phần không dùng, add phần thiếu
5. **Publish:** Move vào C2_templates với version v1.0
6. **Document:** Update README này

---

## Template Maintenance

**Review schedule:** Mỗi 6 tháng hoặc khi có ≥5 cases mới

**Criteria for update:**
- Có ≥3 documents bỏ qua 1 section → Remove section
- Có ≥3 documents thêm cùng 1 section → Add to template
- Feedback từ users: "Khó hiểu" hoặc "Thiếu X"

**Version history:**
- 2026-01-22: v1.0 - Initial training templates
- 2026-01-30: v1.0 - Added application template ✨

---

*Cập nhật lần cuối: 30/01/2026*

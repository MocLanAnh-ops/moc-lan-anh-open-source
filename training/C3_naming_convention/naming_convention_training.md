---
title: "Naming Convention & File Structure – Training"
date: 2026-01-22
domain: Training
type: Standard
status: Published
source: Mộc Lan Anh Open Source
---

## 🎯 Mục đích của tài liệu này

Tài liệu này xác lập **quy ước đặt tên và tổ chức thư mục**  
cho toàn bộ nội dung thuộc mảng **Đào Tạo**.

Mục tiêu:
- Giữ repo **đọc được – mở rộng được – không rối**
- Cho phép nhiều người cùng viết mà **không phá cấu trúc**
- Đảm bảo tài liệu vẫn hiểu được **sau nhiều năm**

---

## 🧱 Nguyên tắc cốt lõi

1. **Tên file phải tự nói lên bản chất**
2. **Ngày tháng dùng để định vị thời gian, không dùng để kể chuyện**
3. **Một file = một đơn vị tư duy**
4. **Không dùng tên người trong tên file**
5. **Không dùng từ cảm xúc hoặc phán xét**

---

## Phân tách tầng Đào Tạo và tầng Hệ Thống

Trong repo này, không phải mọi thư mục đều là học phần.

- Các thư mục bắt đầu bằng **C** (Curriculum) là nội dung đào tạo công bố.
- Các thư mục bắt đầu bằng **S** (System) là cấu phần nội bộ của hệ thống,
  tồn tại để hỗ trợ vận hành và mở rộng về sau.

Việc một thư mục tồn tại không đồng nghĩa với việc nó đã được đưa vào chương trình đào tạo.

---

## 📁 Cấu trúc thư mục chuẩn – Đào Tạo

```txt
/training
│
├── README.md
├── update_log.md
│
├── C1_field_cases
│   └── YYYY-MM-DD_<case-name>.md
│
├── C2_templates
│   └── template_field_case_v1.md
│
├── C3_naming_convention
│   └── naming_convention_training.md
│
├── S_logic_decomposition
├── S_exercises
├── S_responsibility_matrix
├── S_decision_records
└── S_system_support
```

---

🏷️ Quy ước đặt tên file

### 1. Field Case

**Cú pháp:**
`YYYY-MM-DD_<case-name>.md`

**Ví dụ:**
`2026-01-22_hiring-signal-detection.md`

**Lưu ý:**
- `<case-name>` dùng **kebab-case**
- Phải phản ánh **câu hỏi chạm**, không phải chủ đề chung
- Không dùng từ “case”, “study”, “example” trong tên file

---

### 2. Template / Standard

**Cú pháp:**
`<content>-<type>_v<version>.md`

**Ví dụ:**
`template_field_case_v1.md`
`naming_convention_training.md`

**Lưu ý:**
- Luôn có version
- Không gắn ngày nếu không gắn với sự kiện cụ thể

---

### 3. Decision Record

**Cú pháp:**
`YYYY-MM-DD_<decision-name>.md`

**Ví dụ:**
`2026-01-22_training-first.md`

**Lưu ý:**
- Ghi nhận **đã quyết**
- Không ghi lý do dài dòng
- Không chỉnh sửa lại lịch sử

---

🧾 Quy ước cập nhật (Update Protocol)

- **Không sửa bài công bố gốc**
- Mọi cập nhật được ghi tại:
  - `/training/update_log.md`
  - hoặc comment ngắn trên nền tảng công bố

**Ví dụ update log:**
`2026-02-03 – Added new Field Case: hiring-signal-detection`
`2026-02-15 – Added Exercise 02: responsibility matrix`

---

🚫 Những điều không làm

- Không đổi tên file đã công bố
- Không gộp nhiều case vào một file
- Không viết “hướng dẫn sử dụng con người”
- Không tối ưu cho SEO hay truyền thông

---

✅ Khi nào cần tạo file mới?

Tạo file mới khi:
- Xuất hiện **câu hỏi chạm mới**
- Có **quyết định hệ thống mới**
- Có **bài tập mới để kiểm tra năng lực**

Không tạo file mới chỉ để “giải thích thêm”.

---

🧩 Kết luận

Quy ước này tồn tại để:
- Giữ cho Đào Tạo là **không gian học tập trung lập**
- Cho phép năng lực tự lộ qua cách đọc – hiểu – làm
- Tránh việc tài liệu bị chiếm dụng bởi cảm xúc hoặc quyền lực

---

> *“Cấu trúc rõ ràng là điều kiện để tư duy được tự do.”*

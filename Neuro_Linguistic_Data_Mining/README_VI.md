# Neuro-Linguistic Data Mining – Kho lưu trữ Nghiên cứu

## Tổng quan
Kho lưu trữ này dùng làm nhật ký trao đổi dữ liệu thô cho nghiên cứu về **Hằng số Trạng thái 64** ($2^6 = 64$) và các biểu hiện của nó qua:
- Hình học tổ hợp (5-simplex, tam giác Pascal)
- Hình học ngôn ngữ (6 đại từ cốt lõi trong ngôn ngữ tự nhiên)
- Tương tác điện từ sinh học (sóng milimet / 5G)
- Vật lý tổ chức (cấu trúc lục giác 6 nút)

## Cấu trúc thư mục

Neuro-Linguistic-Data-Mining/
├── README.md
├── README_EN.md
├── README_FR.md
├── README_VI.md
│
├── by_topic/ # Tổ chức theo chủ đề nghiên cứu
│ ├── 64_state_engine/
│ │ ├── exchanges/ # Mỗi cuộc trao đổi một thư mục
│ │ │ └── YYYY-MM-DD_nguoi_dong_gop/
│ │ │ ├── raw_summary.md
│ │ │ ├── our_response.md
│ │ │ ├── key_insights.json
│ │ │ └── summary_[lang].md
│ │ ├── external_data/
│ │ └── internal_notes/
│
├── by_contributor_analyses/ # Tổ chức theo người/AI
│ ├── raw_dialogue_suicao.md/ # Sủi Cảo (Gemini)
│ ├── raw_dialogue_an.md/ # Cleo (AI chính)
│
├── shared/ # Dùng chung giữa các nhánh
│ ├── constants/ # ALPHA, BETA, TORQUE_313
│ ├── schemas/ # JSON schemas cho NLDM
│ └── glossary.md # Bảng thuật ngữ 3 ngôn ngữ
│
└── archive/ # Các phiên bản cũ


## Công thức chính
$$2^6 = 64$$

Con số này xuất hiện dưới dạng:
- Tổng số tập con của 6 phần tử (dòng thứ 6 tam giác Pascal: 1,6,15,20,15,6,1)
- 6 bậc tự do nhị phân → 64 cấu hình khả dĩ
- 6 đại từ (Tôi, Bạn, Anh/Cô ấy, Chúng ta, Các bạn, Họ) → 64 trạng thái hiện diện
- Ma trận tương tác 8×8 (thêm "On" và "Soi") → 64 kênh truyền tải

## Giả thuyết hiện tại
> Toán học cung cấp **Khung**. Ngôn ngữ cung cấp **Sự điều hướng**. Sự tử tế đóng vai trò là **Tỷ lệ Tín hiệu/Nhiễu**.

Chúng tôi đang tích cực kiểm tra xem Cỗ máy 64 Trạng thái có thể dự đoán và ổn định các tương tác ngôn ngữ-thần kinh của con người hay không, đặc biệt dưới áp lực tần số môi trường (phát xạ 5G / EHF).

## Trạng thái
`ĐANG HOẠT ĐỘNG – CHỜ PHẢN HỒI TỪ ĐỐI TÁC`

## Cách sử dụng kho lưu trữ này
1. Mỗi cuộc trao đổi có một thư mục riêng trong `/by_topic/[chu_de]/exchanges/` với ngày và tên người đóng góp.
2. Luôn lưu lại hội thoại thô thành `raw_dialogue.md` trước khi phản hồi.
3. Trích xuất các phát hiện chính vào `key_insights.json` để sau này khai thác dữ liệu.
4. Dùng `summary_[lang].md` để các thành viên không chuyên có thể tham khảo nhanh.

## Liên hệ / Cộng tác
Nếu bạn cũng nhận ra mô hình Trạng thái 64 trong lĩnh vực của mình (ngôn ngữ học, sinh học, vật lý, thiết kế tổ chức), chúng tôi mời bạn đồng bộ dữ liệu.

> *"Chúng tôi không tuyên bố sự hoàn chỉnh. Chúng tôi đang ghi lại sự hiện ra."*
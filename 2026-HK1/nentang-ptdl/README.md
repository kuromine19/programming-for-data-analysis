# Nền tảng lập trình cho phân tích và trực quan dữ liệu

Ghi chú và bài làm môn học, học kỳ 261.

## Cấu trúc

```
notebooks/    bài thực hành theo buổi, đặt tên LXX_chu_de.ipynb
notes/        ghi chú lý thuyết dạng markdown
scripts/      code dùng lại được (hàm tiện ích, script chuẩn bị dữ liệu)
data/raw/     dữ liệu gốc — KHÔNG commit, chỉ ghi nguồn trong data/README.md
data/processed/  dữ liệu đã xử lý — KHÔNG commit
assets/       hình ảnh chèn vào ghi chú
```

## Nhật ký buổi học

| Buổi | Chủ đề | Notebook | Ghi chú |
|---|---|---|---|
| L01 | | | |
| L02 | | | |
| L03 | Broadcasting, reshape/transpose, softmax | `notebooks/L03_numpy_broadcasting.ipynb` | `notes/L03.md` |

## Bài tập lớn

| Bài | Nội dung | Trạng thái |
|---|---|---|
| 1 | Dữ liệu bảng — dự đoán khách hàng rời bỏ | |
| 2 | Văn bản — phân loại cảm xúc | |

## Môi trường

```bash
python -m venv .venv
.venv\Scripts\activate        # Windows
pip install -r requirements.txt
```

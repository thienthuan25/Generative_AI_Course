# Generative AI – Elevate Data Science Career

Kho lưu trữ này tổng hợp tài nguyên và bài thực hành cho khóa học về Generative AI ứng dụng trong Data Science. Nội dung được tổ chức theo từng module với dữ liệu mẫu (CSV) và notebook để bạn có thể thực hành ngay trong VS Code/Jupyter.

## Cấu trúc dự án

```
.
├─ module1_data_science_and_generative_ai/
│  ├─ dataset.csv
│  ├─ insurance_dataset.csv
│  ├─ jupyter_lite_for_test.jupyterlite.ipynb
│  └─ synthetic-csv-data/
│     └─ insurance_dataset/
│        └─ insurance_dataset.csv
├─ module2_use_of_generative_ai_for_data_science/
│  ├─ electronics_dataset.csv
│  └─ jupyter_lite_for_test.jupyterlite.ipynb
└─ README.md
```

## Dữ liệu (CSV)

- `module1_data_science_and_generative_ai/dataset.csv`: Bộ dữ liệu mẫu dùng cho các bài thực hành EDA/cơ bản.
- `module1_data_science_and_generative_ai/insurance_dataset.csv`: Dữ liệu bảo hiểm tổng hợp (bản dữ liệu chính).
- `module1_data_science_and_generative_ai/synthetic-csv-data/insurance_dataset/insurance_dataset.csv`: Phiên bản synthetic của insurance dataset dùng để thử nghiệm/không nhạy cảm.
- `module2_use_of_generative_ai_for_data_science/electronics_dataset.csv`: Dữ liệu sản phẩm điện tử để minh họa use case ở Module 2.

Lưu ý: Các tệp CSV có thể không có mô tả chi tiết cột. Khi làm việc, bạn nên đọc nhanh 5–10 dòng đầu để nắm sơ bộ schema và kiểu dữ liệu.

## Notebook

- Module 1: `module1_data_science_and_generative_ai/jupyter_lite_for_test.jupyterlite.ipynb`
- Module 2: `module2_use_of_generative_ai_for_data_science/jupyter_lite_for_test.jupyterlite.ipynb`

Bạn có thể mở và chạy trực tiếp trong VS Code (Jupyter extension) hoặc JupyterLab cục bộ.

## Yêu cầu hệ thống

- Python 3.10+ (khuyến nghị) và `pip`
- VS Code với các extension: Python, Jupyter (khuyến nghị), hoặc JupyterLab

## Thiết lập nhanh (Windows PowerShell)

```powershell
# 1) Tạo môi trường ảo
python -m venv .venv

# 2) Kích hoạt môi trường
.\.venv\Scripts\Activate.ps1

# 3) Cài đặt gói cần thiết
pip install --upgrade pip
pip install jupyter pandas numpy matplotlib seaborn scikit-learn pyarrow openpyxl

# 4) Chạy Jupyter Lab (tuỳ chọn) hoặc dùng VS Code để mở notebook
jupyter lab
```

Trong VS Code, mở notebook và chọn kernel trỏ tới môi trường `.venv` để chạy.

## Các thành phần khác trong module

### Module 1 – Data Science & Generative AI


### Module 2 – Use of Generative AI for Data Science
- Hands-on Lab: Generative AI for Data Visualization: https://www.zoho.com/analytics/





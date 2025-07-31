# 📊 Phân Tích Tình Trạng Tài Chính FPT từ Vietstock

## 🧠 Giới Thiệu Dự Án

Dự án này nhằm thu thập và phân tích báo cáo tài chính của Công ty Cổ phần FPT (mã chứng khoán: FPT) từ trang web [Vietstock](https://finance.vietstock.vn), sử dụng Python. Dữ liệu được crawl tự động từ trình duyệt web không giao diện bằng công cụ Playwright, xử lý bằng Pandas, và hiển thị qua Jupyter Notebook.  

Mục tiêu là đánh giá tình hình tài chính doanh nghiệp qua các năm dựa trên 3 loại báo cáo chính:
- Báo cáo cân đối kế toán  
- Báo cáo kết quả kinh doanh  
- Các chỉ số tài chính

Kết quả phân tích giúp nhà đầu tư hoặc nhà quản trị có cái nhìn tổng quan và chính xác hơn về hiệu quả hoạt động và sức khỏe tài chính của doanh nghiệp.

---

## 🛠️ Công Nghệ Sử Dụng

- **Python 3.8+**
- **Playwright** – Tự động hóa trình duyệt web để thu thập dữ liệu.
- **BeautifulSoup4** – Phân tích cấu trúc HTML.
- **Pandas** – Xử lý dữ liệu dạng bảng.
- **Jupyter Notebook** – Trình bày và trực quan hóa kết quả.

---

## ⚙️ Hướng Dẫn Chạy Dự Án

```bash
# 1. Cài đặt thư viện
pip install pandas beautifulsoup4 playwright
playwright install chromium

# 2. Mở notebook và chạy từng bước
jupyter notebook "Phân tích tình trạng FPTvietstock.ipynb"

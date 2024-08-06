#ĐỀ TÀI: Hệ hoạch định nguồn lực dựa trên CÔNG TY CP ACECOOK VIỆT NAM. 
#CÁC THÀNH VIÊN THỰC HIỆN ĐỀ TÀI
  Phạm Ngọc Yến Nhi
  Vũ Thị Nhung
#Yêu cầu
  ODOO 17
#Hướng dẫn cài đặt
1. **Clone dự án:**
    ```bash
    git clone https://github.com/ynhi10923/ACECOOK-.git
    cd du-an-quan-ly
    ```

2. **Tạo và kích hoạt môi trường ảo:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # Trên Windows, sử dụng: venv\Scripts\activate
    ```

3. **Cài đặt phụ thuộc:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Cấu hình Odoo:**
   - Tạo một tập tin cấu hình `odoo.conf` với các thiết lập sau:
     ```ini
     [options]
     ; Đây là tập tin cấu hình Odoo cho dự án ACECOOK
     db_host = localhost
     db_port = 5432
     db_user = odoo
     db_password = 12345
  5. **Chạy Odoo:**
    ```bash
    ./odoo-bin -c odoo.conf
    ```

FRAMIX – BẢN CHẠY LOCAL

Cách chạy (cần mở qua máy chủ web, KHÔNG mở thẳng file index.html bằng double-click,
vì trình duyệt chặn tải mô hình AI khi mở bằng file://):

Cách 1 – Python (có sẵn trên đa số máy):
    cd framix
    python -m http.server 8000
  rồi mở http://localhost:8000

Cách 2 – Node.js:
    cd framix
    npx serve -l 8000
  rồi mở http://localhost:8000

Cách 3 – VS Code: cài extension "Live Server", mở thư mục framix, bấm "Go Live".

Ghi chú:
- Thử kính ảo dùng camera: trình duyệt chỉ cho bật camera trên http://localhost hoặc https.
  Không có camera thì dùng nút tải ảnh chân dung.
- Chat "Hỏi Framix": bản local trả lời bằng bộ câu hỏi thường gặp và tìm kiếm trong
  danh mục sản phẩm. Phần trả lời bằng AI chỉ chạy khi mở trên claude.ai.
- Font chữ (Plus Jakarta Sans, Fraunces) tải từ Google Fonts; không có mạng thì trình
  duyệt dùng font thay thế, mọi chức năng khác vẫn chạy offline.
- Giỏ hàng lưu trong localStorage của trình duyệt.

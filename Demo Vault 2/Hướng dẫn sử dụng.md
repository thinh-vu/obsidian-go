>[!hint] Đây là cấu hình thư mục Obsidian mới nhất mà tôi đang sử dụng, cập nhật tháng 8/2023.

# Cấu trúc thư mục
Tên thư mục | Chi tiết
--- | ---
JOURNAL | Lưu trữ Daily Notes (các ghi chú hàng ngày) một cách ngăn nắp. Ghi chú trong thư mục này sẽ sử dụng template Daily Journal.
PROJECT | Lưu trữ các ghi chú cho dự án cụ thể.
RESOURCE | Ngôi nhà chung cho các mẫu ghi chú, danh mục, file đính kèm giúp cho Vault của bạn trông gọn gàng và ngăn nắp, bạn chọn muốn được thấy những ghi chú nào
ARCHIVED | Kho lưu trữ các ghi chú đã tạm thời không có nhu cầu sử dụng liên tục, chỉ cần lưu trữ để lúc nào đó có thể tìm lại.
VISUAL NOTES | Đây là thư mục lưu trữ tất cả các ghi chú dạng sketch note, flowchart được tạo bởi Excalidraw plugin. Tôi nhận thấy đây là một thành phần cần thiết cho Vault. Ngoài ghi chú Excalidraw, bạn có thể nhóm chung các Canvas vào đây cho gọn.

# Hướng dẫn cấu hình
- Copy tất cả các thành phần trong Demo Vault 2 ra thư mục chính `obsidian-pre-config` Nếu bạn yêu thích cấu trúc này và chọn sử dụng.
- Tùy chỉnh phần cài đặt `Files & Links` > `Attachments Folder Path`để cập nhật thư mục `/2. RESOURCE/attachments` làm thư mục lưu trữ các file đính kèm thay cho `/src` 
- Tùy chỉnh cấu hình cho Community Plugin `Periodic Notes` cho các mục   `Daily Notes`, `Weekly Notes`, và `Monthly Notes` để cập nhật đường dẫn thư mục chứa template note tại địa chỉ mới là `/2. RESOURCE/template`, chọn đúng template cho từng mục này, ví dụ Template cho `Daily Note Template` phải là `Daily Journal`.
  ![[Pasted image 20230810083336.png]]
# Nguyên tắc sử dụng

> [!info] Cấu trúc thư mục này hướng đến sự loại bỏ cách lưu trữ ghi chú bị phân mảnh theo các thư mục, thay vào đó bạn chỉ sử dụng thư mục để chứa các ghi chú đặc thù giúp Vault được ngăn nắp.
- Trình tự tạo ghi chú:
	- Tạo 1 ghi chú mới, sử dụng phím tắt Ctrl + N hoặc Cmd + N cho macOS
	- Chèn template cho ghi chú. Sử dụng slash command `/Templates: Insert Template`. Khi gõ `/` và bắt đầu nhập template thì tùy chọn này xuất hiện đầu tiên. Bạn cũng có thể sử dụng icon `Insert Template` ở thanh công cụ bên trái màn hình
	- Chèn wiki link cho lĩnh vực ghi chú này thuộc về
	- Soạn ghi chú và chèn các wiki link đến các ghi chú khác liên quan.
- Tất cả ghi chú mới sẽ được chèn Wiki Link đến các ghi chú Index trong thư mục `2.RESOURCE/index` để có thể liên kết các chủ đề liên quan với ghi chú bạn đang viết. Ví dụ [[Community]] bởi ghi chú này tôi viết để chia sẻ cho cộng đồng. Bạn có thể sử dụng nhiều Wiki Link khác cho các chủ đề nhỏ hơn để liên kết các dòng suy nghĩ của mình và kết hợp chúng với nhau qua thời gian.
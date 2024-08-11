# 🧪 **Danh sách các flag khuyên dùng cho các trình duyệt Chromium** 🧪

![Chromium](../Images/chromium.jpg)

## 😍 Dành cho Google Chrome

| Tên | Trạng Thái | Miêu tả |
|:---|:---|:---|
| `#ignore-gpu-blocklist` | `Enabled` |  Để chạy đồ hoạ với onboard/discrete GPU thay vì với CPU
| `#smooth-scrolling` | `Enabled` | Để scroll animation mượt mà hơn |
| `#temporary-unexpire-flags-m1xx (xx: number)` | `Enabled` | Tạm thời liệt kê các flags của các phiên bản trước |
| `#enable-gpu-rasterization` | `Enabled` | Cho phép GPU "vẽ" content trên web |
| `#enable-zero-copy` | `Enabled` | Content sau khi "vẽ" sẽ cache thẳng vào bộ nhớ GPU |
| `#enable-quic` | `Enabled` | Cho phép hỗ trợ giao thức QUIC (thử nghiệm), duyệt web nhanh hơn |
| `#tab-groups-save-v2` | `Enabled` | Sử dụng tính năng save nhóm tab v2 (thử nghiệm) |
| `#enable-parallel-downloading` | `Enabled` | Cho phép download nhiều luồng song song |
| `#tab-hover-card-images` | `Enabled` | Kích hoạt ảnh preview khi hover vào tab |
| `#calculate-native-win-occlusion` |  `Disabled` | Không biết dịch ra sao nhưng tắt nó đi sẽ bớt lag hơn |
| `#use-angle` | `OpenGL` nếu là NVDIA, còn lại `Default` | Chọn loại backend cho việc render |
| `#back-forward-cache` | `Enabled` | Cache cho việc navigate trang trước và sau, nên bật vì tăng tốc độ đáng kể |
| `#heavy-ad-privacy-mitigations` | `Disabled` | Chặn các banner quảng cáo lớn từ các bên thứ ba |
| `#prerender2` | `Enabled` | Sử dụng tính năng pre-render trang web (Thử nghiệm) |
| `#enable-drdc` | `Enabled` | Cho phép Chrome sử dụng cả 2 loại card onboard/rời song song |
| `#canvas-oop-rasterization` | `Enabled` | "Vẽ" content canvas 2D bằng tiến trình GPU |
| `#ui-enable-shared-image-cache-for-gpu` | `Enabled` | Chia sẻ cache hình ảnh giữa các bên GPU |
| `#discard-ring-improvements` | `Enabled` | Cải thiện tính năng discard tab |
| `#memory-saver-aggressiveness` | `Enabled` | Cho phép tuỳ chỉnh mức độ tính năng Memory Saver |
| `#use-gpu-scheduler-dfs` | `Disabled` | Không biết dịch ra sao nhưng tắt nó đi sẽ bớt lag hơn |
| `#enable-lens-overlay` | `Enabled` | Hiển thị nút dùng Google Lens trên thanh search |

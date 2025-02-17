---

# Vue Pure Admin - CineBoo

![Vue.js](https://img.shields.io/badge/Vue.js-3.x-brightgreen.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

## 🌟 Giới thiệu
---
**Vue Pure Admin** là một dự án quản trị mạnh mẽ, được xây dựng trên nền tảng **Vue.js 3** và **Vite**. Với kiến trúc dễ tùy biến, giao diện người dùng tinh gọn và thân thiện, nó được thiết kế để phù hợp với mọi loại ứng dụng quản trị, đặc biệt là **CineBoo** – hệ thống quản lý và điều hành bán vé xem phim trực tuyến.

## 🎯 Tính năng nổi bật

- **Vue.js 3** với Composition API: Tận dụng công nghệ hiện đại từ Vue để xây dựng UI linh hoạt và mạnh mẽ.
- **Quản lý Role và Quyền Hạn**: Dễ dàng thiết lập các quyền hạn và vai trò cho từng người dùng.
- **Quản lý Route**: Định tuyến thông minh với `meta.requiresAuth` và `beforeEnter` để bảo mật và điều hướng dựa trên vai trò.
- **Giao diện Tối Giản**: Dễ sử dụng và tối ưu trải nghiệm người dùng với thiết kế đơn giản mà hiệu quả.
- **Quản lý Đặt Vé**: Chức năng cho phép người dùng xem lịch chiếu, chọn ghế và đặt vé trực tuyến.
- **Quản lý Báo Cáo và Cài Đặt**: Trang báo cáo và cài đặt được quản lý tốt, giúp bạn dễ dàng theo dõi và điều chỉnh hệ thống.
  
## 🛠️ Công nghệ sử dụng

- **Vue.js 3**
- **Vite** - công cụ xây dựng nhanh
- **Vue Router** - định tuyến cho ứng dụng
- **Pinia** - quản lý trạng thái dễ dàng
- **Axios** - kết nối và xử lý API
- **CSS** - tạo giao diện đẹp mắt và dễ dàng tùy biến

## 📦 Cài đặt

Clone dự án từ GitHub:

```bash
(https://github.com/dangkhoa2004/frontend-cineboo.git
cd frontend-cineboo
npm install
npm install axios@^1.7.7
npm install js-cookie@^3.0.5
npm install leaflet@^1.9.4
npm install nprogress@^0.2.0
npm install vue@^3.5.10
npm install vue-i18n@^10.0.4
npm install vue-router@^4.4.5
npm install vue3-leaflet@^1.0.50
npm install vuex@^4.1.0
npm install path
npm install date-fns
```

Chạy dự án:

```bash
npm run serve
```

## 🔐 Xác thực và phân quyền

Ứng dụng có các chức năng bảo mật thông qua xác thực người dùng và phân quyền dựa trên vai trò. Các trang quản trị như Admin, Settings và Reports được bảo vệ bằng `meta.requiresAuth` và kiểm tra quyền hạn qua `beforeEnter` để đảm bảo chỉ những người có quyền mới được truy cập.

## 📁 Cấu trúc thư mục
```bash
src/
├── api/            # Các thành phần quản lý nạp api
├── assets/         # Các tài nguyên như hình ảnh, font
├── components/     # Các thành phần tái sử dụng
├── config/         # Các thành phần cấu hình cho dự án
├── directives/     # Các thành phần cấu hình chỉ thị UI
├── layout/         # Các layout chính của ứng dụng
├── plugins/        # Các tiện ích, cấu hình khác cho dự án
├── router/         # Định tuyến của ứng dụng
├── store/          # Quản lý trạng thái với Pinia
├── style/          # Quản lý css trọng điểm dự án
├── utils/          # Các hàm tiện ích (utility functions)
├── views/          # Các trang hiển thị chính
└── App.vue         # Thành phần root của ứng dụng
```

## 🎨 Tùy chỉnh giao diện

Bạn có thể dễ dàng thay đổi giao diện theo phong cách của **CineBoo** bằng cách cập nhật tệp SCSS trong thư mục `src/style/...`. Dự án cũng hỗ trợ **Dark Mode** để phù hợp với trải nghiệm người dùng.

## 📝 Đóng góp

Mọi đóng góp cho dự án đều được hoan nghênh! Bạn có thể tạo Pull Request hoặc mở Issues để trao đổi các vấn đề gặp phải.

---

💻 **Vue Pure Admin - CineBoo** là giải pháp toàn diện để xây dựng hệ thống quản trị mạnh mẽ và hiệu quả cho bán vé xem phim trực tuyến. Cùng khám phá và cải thiện nó ngay hôm nay!

---

## 📄 Giấy phép

Dự án được cấp phép theo [MIT License](LICENSE).

---

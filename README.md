# Marketing Analytics Dashboard

Dashboard phân tích marketing hiện đại với bảng thống kê chi tiết và biểu đồ trực quan.

## ✨ Tính năng

- 📊 Bảng thống kê chiến dịch marketing đầy đủ
- 📈 Biểu đồ hiệu suất theo tháng
- 🎯 KPI cards với số liệu thời gian thực
- ⚡ Animation mượt mà
- 📱 Responsive design
- 🎨 UI/UX hiện đại

## 🚀 Deploy lên Vercel

### Cách 1: Deploy qua Vercel CLI

```bash
# Cài đặt Vercel CLI
npm i -g vercel

# Deploy
vercel
```

### Cách 2: Deploy qua GitHub

1. Tạo repository mới trên GitHub
2. Upload các file: `index.html`, `vercel.json`, `package.json`
3. Vào [vercel.com](https://vercel.com)
4. Click "New Project"
5. Import repository từ GitHub
6. Click "Deploy"

### Cách 3: Deploy trực tiếp

1. Vào [vercel.com](https://vercel.com)
2. Kéo thả folder chứa các file vào trang
3. Đợi vài giây để deploy

## 📁 Cấu trúc file

```
marketing-analytics-dashboard/
├── index.html       # File chính
├── vercel.json      # Cấu hình Vercel
├── package.json     # Metadata project
└── README.md        # File này
```

## 🛠️ Công nghệ sử dụng

- HTML5
- CSS3 (với animations & gradients)
- Vanilla JavaScript
- Google Fonts (Syne & JetBrains Mono)

## 📝 Lưu ý

- File `index.html` là trang chủ (bắt buộc phải tên là index.html)
- File `vercel.json` cấu hình routing để tránh lỗi 404
- Không cần build process, deploy trực tiếp được

## 🎨 Tùy chỉnh

Bạn có thể tùy chỉnh:
- Màu sắc trong `:root` variables
- Dữ liệu trong bảng thống kê
- Biểu đồ và KPI numbers
- Fonts và typography

## 📞 Hỗ trợ

Nếu gặp lỗi 404:
1. Đảm bảo file tên là `index.html` (không phải marketing-dashboard.html)
2. Kiểm tra file `vercel.json` có trong cùng thư mục
3. Redeploy lại project

Enjoy! 🎉

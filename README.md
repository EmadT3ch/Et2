# 🛠️ EmadTech Toolbox

> جعبه ابزار کامل - بهترین نرم‌افزارها و ابزارهای کاربردی برای ویندوز و اندروید

## 🌟 ویژگی‌ها

- **150+ نرم‌افزار** در دسته‌بندی‌های مختلف
- **پشتیبانی از RTL** برای زبان فارسی
- **طراحی واکنش‌گرا** برای همه دستگاه‌ها
- **بروزرسانی مداوم** محتوا
- **جستجوی قدرتمند** در محتوا

## 📋 محتوای سایت

### 🛠️ ابزارها و نرم‌افزارها
- 🌐 مرورگرها
- 🎬 پخش‌کننده‌های مدیا
- 💬 پیام‌رسان‌ها
- 🛠️ ابزارهای کاربردی
- 🔐 VPN و امنیت
- 📂 اشتراک‌گذاری فایل
- 🛡️ نرم‌افزارهای امنیتی

### 🤖 هوش مصنوعی
- 💻 نرم‌افزارهای AI
- 🌐 وبسایت‌های هوش مصنوعی

### 🌐 وبسایت‌های کاربردی
- 🔎 جستجو و تحقیق
- 🎨 طراحی و گرافیک
- 📚 آموزش و یادگیری
- 🛠️ ابزارهای آنلاین
- ☁️ فضای ابری

### 📢 کانال‌های تلگرامی
- 📰 تکنولوژی و IT
- 📚 آموزش و یادگیری
- 🌍 اخبار و تحلیل
- 🛠️ ابزار و منابع

## 💻 نصب و راه‌اندازی

### پیش‌نیازها
- Node.js (نسخه 16 یا بالاتر)
- npm یا pnpm

### نصب
```bash
# کلون کردن پروژه
git clone [repository-url]
cd toolbox-site

# نصب وابستگی‌ها
npm install

# اجرای سرور توسعه
npm run dev

# ساخت نسخه پروداکشن
npm run build

# پیش‌نمایش نسخه ساخته شده
npm run preview
```

## 📁 ساختار پروژه

```
toolbox-site/
├── .vitepress/
│   ├── config.js          # تنظیمات اصلی
│   └── theme/
│       ├── index.js       # تم سفارشی
│       └── style.css      # استایل‌های RTL
├── public/                # فایل‌های استاتیک
├── index.md              # صفحه اصلی
├── tools/                # ابزارها و نرم‌افزارها
├── ai/                   # هوش مصنوعی
├── websites/             # وبسایت‌های کاربردی
├── channels/             # کانال‌های تلگرامی
└── package.json          # تنظیمات پروژه
```

## 🎨 شخصی‌سازی

### تغییر رنگ‌ها
فایل `.vitepress/theme/style.css` را ویرایش کنید:

```css
:root {
  --vp-c-brand-1: #646cff;
  --vp-c-brand-2: #747bff;
  --vp-c-brand-3: #535bf2;
}
```

### افزودن محتوای جدید
1. فایل `.md` جدید بسازید
2. به فایل `config.js` اضافه کنید
3. در navigation و sidebar لینک کنید

## 🌐 استقرار

### GitHub Pages
```bash
npm run build
# محتوای پوشه dist را در GitHub Pages قرار دهید
```

### Netlify
1. پروژه را به گیت‌هاب push کنید
2. Netlify را به repository متصل کنید
3. Build command: `npm run build`
4. Publish directory: `dist`

### Vercel
```bash
npx vercel
# دستورات را دنبال کنید
```

## 🔧 تنظیمات پیشرفته

### فعال‌سازی PWA
```javascript
// .vitepress/config.js
export default {
  // ... سایر تنظیمات
  pwa: {
    outDir: '.vitepress/dist',
    registerType: 'autoUpdate',
    workbox: {
      globPatterns: ['**/*.{js,css,html,ico,png,svg}']
    }
  }
}
```

### تنظیمات SEO
```javascript
// .vitepress/config.js
head: [
  ['meta', { name: 'description', content: 'توضیحات سایت' }],
  ['meta', { property: 'og:title', content: 'عنوان سایت' }],
  ['meta', { property: 'og:description', content: 'توضیحات' }],
  ['meta', { property: 'og:image', content: '/og-image.png' }]
]
```

## 🤝 مشارکت

1. پروژه را Fork کنید
2. برانچ جدید بسازید (`git checkout -b feature/AmazingFeature`)
3. تغییرات را commit کنید (`git commit -m 'Add some AmazingFeature'`)
4. برانچ را push کنید (`git push origin feature/AmazingFeature`)
5. Pull Request بسازید

## 📄 مجوز

این پروژه تحت مجوز MIT منتشر شده است. فایل [LICENSE](LICENSE) را مطالعه کنید.

## 👨‍💻 سازنده

**EmadTech**
- کانال تلگرام: [@EmadT3ch](https://t.me/EmadT3ch)
- GitHub: [لینک گیت‌هاب]

## 🙏 تشکر

- از تیم VitePress برای ساخت این ابزار فوق‌العاده
- از جامعه متن‌باز برای ابزارها و منابع ارائه شده
- از تمام کاربرانی که بازخورد می‌دهند

---

<p align="center">
  ساخته شده با ❤️ توسط EmadTech
</p>
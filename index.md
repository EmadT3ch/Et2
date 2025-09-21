---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "EmadTech Toolbox"
  text: "جعبه ابزار کامل"
  tagline: "بهترین و پرکاربردترین نرم‌افزارها برای ویندوز و اندروید"
  image:
    src: /logo.png
    alt: EmadTech Logo
  actions:
    - theme: brand
      text: 🚀 شروع کنید
      link: /tools/
    - theme: alt
      text: 📋 مشاهده لیست کامل
      link: /tools/browsers

features:
  - icon: 🌐
    title: مرورگرهای قدرتمند
    details: بهترین مرورگرهای وب برای تجربه مرور سریع و امن
    link: /tools/browsers
  - icon: 🎬
    title: پخش‌کننده‌های مدیا
    details: ابزارهای حرفه‌ای برای پخش انواع فایل‌های صوتی و تصویری
    link: /tools/media-players
  - icon: 💬
    title: پیام‌رسان‌های محبوب
    details: بهترین اپلیکیشن‌های ارتباطی و پیام‌رسانی
    link: /tools/messengers
  - icon: 🛠️
    title: ابزارهای کاربردی
    details: مجموعه کاملی از ابزارهای ضروری برای کار روزانه
    link: /tools/utilities
  - icon: 🔐
    title: VPN و امنیت
    details: ابزارهای امنیتی و VPN برای حفاظت از حریم خصوصی
    link: /tools/vpn
  - icon: 🤖
    title: هوش مصنوعی
    details: جدیدترین ابزارها و وبسایت‌های هوش مصنوعی
    link: /ai/
---

<div class="home-content">

## 🎯 چرا جعبه ابزار EmadTech؟

<div class="features-grid">
  <div class="feature-card">
    <div class="feature-icon">⚡</div>
    <h3>به‌روزرسانی مداوم</h3>
    <p>تمامی نرم‌افزارها و ابزارها به‌طور مرتب بررسی و به‌روزرسانی می‌شوند</p>
  </div>
  
  <div class="feature-card">
    <div class="feature-icon">🔍</div>
    <h3>انتخاب دقیق</h3>
    <p>هر نرم‌افزار با دقت انتخاب شده و قابلیت‌های آن بررسی شده است</p>
  </div>
  
  <div class="feature-card">
    <div class="feature-icon">🎨</div>
    <h3>طراحی زیبا</h3>
    <p>رابط کاربری زیبا و سازگار با زبان فارسی برای تجربه بهتر</p>
  </div>
</div>

## 📊 آمار سایت

<div class="stats-grid">
  <div class="stat-card">
    <div class="stat-number">150+</div>
    <div class="stat-label">نرم‌افزار</div>
  </div>
  
  <div class="stat-card">
    <div class="stat-number">10</div>
    <div class="stat-label">دسته‌بندی</div>
  </div>
  
  <div class="stat-card">
    <div class="stat-number">2</div>
    <div class="stat-label">پلتفرم</div>
  </div>
  
  <div class="stat-card">
    <div class="stat-number">24/7</div>
    <div class="stat-label">پشتیبانی</div>
  </div>
</div>

## 🚀 دسترسی سریع

<div class="quick-access">
  <a href="/tools/browsers" class="quick-link">
    <span class="quick-icon">🌐</span>
    <span class="quick-text">مرورگرها</span>
  </a>
  
  <a href="/tools/utilities" class="quick-link">
    <span class="quick-icon">🛠️</span>
    <span class="quick-text">ابزارها</span>
  </a>
  
  <a href="/tools/vpn" class="quick-link">
    <span class="quick-icon">🔐</span>
    <span class="quick-text">VPN</span>
  </a>
  
  <a href="/ai/" class="quick-link">
    <span class="quick-icon">🤖</span>
    <span class="quick-text">هوش مصنوعی</span>
  </a>
  
  <a href="/websites/" class="quick-link">
    <span class="quick-icon">🌍</span>
    <span class="quick-text">وبسایت‌ها</span>
  </a>
  
  <a href="/channels/" class="quick-link">
    <span class="quick-icon">📢</span>
    <span class="quick-text">کانال‌ها</span>
  </a>
</div>

## 💡 نکات مهم

::: tip توجه
تمامی نرم‌افزارهای معرفی شده از منابع رسمی و معتبر دریافت شده‌اند. همیشه از دانلود از منابع رسمی اطمینان حاصل کنید.
:::

::: warning هشدار
قبل از نصب هر نرم‌افزاری، حتماً از سیستم خود بک‌آپ تهیه کنید و آنتی‌ویروس خود را به‌روز نگه دارید.
:::

</div>

<style scoped>
.home-content {
  max-width: 1200px;
  margin: 0 auto;
  padding: 2rem 1rem;
}

.features-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin: 2rem 0;
}

.feature-card {
  background: var(--vp-c-bg-soft);
  border: 1px solid var(--vp-c-divider);
  border-radius: 12px;
  padding: 2rem;
  text-align: center;
  transition: all 0.3s ease;
}

.feature-card:hover {
  border-color: var(--vp-c-brand-1);
  box-shadow: 0 8px 32px rgba(100, 108, 255, 0.1);
  transform: translateY(-4px);
}

.feature-icon {
  font-size: 3rem;
  margin-bottom: 1rem;
}

.feature-card h3 {
  color: var(--vp-c-text-1);
  margin-bottom: 1rem;
}

.feature-card p {
  color: var(--vp-c-text-2);
  line-height: 1.6;
}

.stats-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1.5rem;
  margin: 2rem 0;
}

.stat-card {
  background: linear-gradient(135deg, var(--vp-c-brand-1), var(--vp-c-brand-2));
  border-radius: 12px;
  padding: 2rem;
  text-align: center;
  color: white;
}

.stat-number {
  font-size: 2.5rem;
  font-weight: bold;
  margin-bottom: 0.5rem;
}

.stat-label {
  font-size: 1.1rem;
  opacity: 0.9;
}

.quick-access {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
  gap: 1rem;
  margin: 2rem 0;
}

.quick-link {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 1.5rem;
  background: var(--vp-c-bg-soft);
  border: 1px solid var(--vp-c-divider);
  border-radius: 12px;
  text-decoration: none;
  color: var(--vp-c-text-1);
  transition: all 0.3s ease;
}

.quick-link:hover {
  border-color: var(--vp-c-brand-1);
  background: var(--vp-c-brand-soft);
  transform: translateY(-2px);
}

.quick-icon {
  font-size: 2rem;
  margin-bottom: 0.5rem;
}

.quick-text {
  font-weight: 500;
}

@media (max-width: 768px) {
  .features-grid {
    grid-template-columns: 1fr;
  }
  
  .stats-grid {
    grid-template-columns: repeat(2, 1fr);
  }
  
  .quick-access {
    grid-template-columns: repeat(2, 1fr);
  }
}
</style>
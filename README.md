# ⚡ ProxyPulse — Premium MTProto Proxy Dashboard

<p align="center">
  <a href="#english-version">English Document</a> •
  <a href="#راهنمای-فارسی">راهنمای فارسی (Persian)</a>
</p>

---

<div id="english-version"></div>

## 🚀 Overview (English)

**ProxyPulse** is a lightweight, premium, and intelligent monitoring dashboard designed to test, benchmark, and sort Telegram MTProto proxies in real-time. It ensures high availability by utilizing an automated failover repository system, filtering out duplicates, and sorting the fastest proxies directly in your browser.

Live Demo: `https://<your-username>.github.io/<your-repo-name>/`

### ✨ Key Features

1. **🔄 Automated Failover Sources:** Intelligent mechanism that tries fetching proxies from a secure CDN first (`jsDelivr`). If blocked or failed, it automatically switches to a secondary direct source (`GitHub Raw`) within milliseconds without breaking the UX.
2. **⚡ Real-Time Ping Checker:** Benchmarks proxy latency (`ms`) natively based on your current network operator.
3. **📊 Smart Sorting & Tagging:** Automatically bubbles up alive and ultra-fast proxies to the top, labeled with performance tags (`Excellent ⚡`, `Good 🟢`, `Average 🟡`).
4. **📱 Instant QR Code Generator:** Generate on-the-fly scannable QR codes for each proxy to easily connect your mobile devices.
5. **🌐 Network Status Monitor:** Displays your public IP address and ISP provider automatically at the top of the dashboard.
6. **📋 Bulk Copying:** Copy all verified alive proxies sorted by speed into your clipboard with a single click.

---

### 🗄️ Data Source & Copyright

The proxy database used in this project is automatically fetched from the open-source repository of [SoliSpirit/mtproto](https://github.com/SoliSpirit/mtproto). 

> **🙏 Special Thanks:** Huge thanks to **SoliSpirit** for maintaining the live and updated proxy database. This project complies with open-source reuse standards by giving full credits to the original data provider.

---

### 🛠️ Built With

* [Tailwind CSS](https://tailwindcss.com) - Sleek Glassmorphism UI.
* [QRious](https://github.com/neocotic/qrious) - Pure JavaScript QR code generator.
* [Vazirmatn](https://github.com/rastikerdar/vazirmatn) - Premium Persian typography.

---

## راهنمای فارسی

<div dir="rtl">

## 🚀 معرفی پروژه (Persian)

پروژه **ProxyPulse** یک داشبورد مانیتورینگ سبک، لوکس و هوشمند برای سنجش پینگ، اعتبارسنجی و مرتب‌سازی لحظه‌ای پروکسی‌های MTProto تلگرام است. این ابزار بهترین و سریع‌ترین پروکسی‌ها را متناسب با اپراتور اینترنت شما استخراج کرده و به صورت خودکار از سریع‌ترین به کندترین مرتب می‌کند.

### ✨ قابلیت‌های کلیدی

۱. **🔄 سوئیچ خودکار مخازن (Failover):** سیستم هوشمند ابتدا دیتای پروکسی را از CDN ضد فیلتر لود می‌کند؛ در صورت مسدود بودن، در کسری از ثانیه روی لینک مستقیم گیت‌هاب سوئیچ خواهد کرد.
۲. **⚡ پینگ‌سنجی آنی:** سنجش دقیق میزان تأخیر (Ping) پروکسی بر حسب میلی‌ثانیه متناسب با اینترنت فعلی شما.
۳. **📊 مرتب‌سازی و تگ‌گذاری هوشمند:** چیدمان خودکار پروکسی‌های زنده و اعطای تگ‌های کیفیت هوشمند (`عالی ⚡`، `خوب 🟢`، `معمولی 🟡`).
۴. **📱 تولید خودکار QR Code:** ایجاد بارکد اسکن‌شدنی برای هر پروکسی جهت اتصال سریع گوشی به تلگرام.
۵. **🌐 مانیتورینگ وضعیت شبکه:** تشخیص و نمایش آی‌پ‌ی عمومی (Public IP) و شرکت ارائه‌دهنده اینترنت شما (ISP) در بالای صفحه.
۶. **📋 کپی گروهی (Bulk Copy):** امکان کپی یکجای تمام پروکسی‌های سالم به ترتیب سرعت با یک کلیک.

---

### 🗄️ منبع داده‌ها و حق کپی‌رایت

دیتا و لیست پروکسی‌های این برنامه به صورت خودکار و زنده از مخزن سورس‌باز و عمومی **[SoliSpirit/mtproto](https://github.com/SoliSpirit/mtproto)** دریافت می‌شود.

> **🙏 تقدیر و تشکر:** صمیمانه از توسعه‌دهنده محترم مخزن **SoliSpirit** برای جمع‌آوری و آپدیت نگه‌داشتن این مخزن قدرتمند سپاسگزاریم. این پروژه با ذکر منبع، تمام قوانین اخلاقی و کپی‌رایت دنیای متن‌باز (Open Source) را رعایت کرده است.

---

### 📦 نحوه راه‌اندازی و استفاده

۱. کدهای فایل `index.html` را در مخزن گیت‌هاب خود قرار دهید.
۲. به بخش **Settings > Pages** بروید.
۳. بخش Source را روی **Deploy from a branch** تنظیم کرده، شاخه اصلی (`main`) را انتخاب و دکمه **Save** را بزنید.
۴. پروژه شما آماده استفاده است!

</div>

---

## 👨‍💻 Author / توسعه‌دهنده

Made with ♥️ by **Saeed**
